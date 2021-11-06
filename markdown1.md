---
title: "Mein Markdown Meilenstein"
author: "Niclas Ketterer (nk139)"
output:
  html_document:
    toc: true
    toc_depth: 3
    number_sections: true
---
 


# Erste Erfahrungen im Bereich Data Literacy
Bereits im **ersten Meilenstein** habe ich einiges über Sicherheit und Gefahren im Netz gelernt. Ich bin mir des Risikos, welches eigentlich *immer und tagtäglich* lauert, jetzt durchaus noch stärker bewusst. Gleichzeitig weiß ich aber jetzt, auch Dank der hilfreichen Selbsttests, mich gut vor den potenziellen Gefahren zu schützen und schon eine Art Absicherung im Vorraus machen zu können.
Stichworte sind hier vor allem **sichere Passwörter** und diese möglichst **nicht überall** zu verwenden.

\tableofcontents

## Mein Datenmanifest
Das **Datenmanifest** wurde auf Grundlage der vorrausgegangen Aufgaben erstellt und basierte vor allem auf den **Digitalen Selbsttest** von *oncampus*.

*Folgende Fragen galt es im Zuge dieses Datenmanifests zu beantworten:*

### Wem gehören meine Daten?

![Wem gehören meine Daten? Hier eine Definition. (https://www.eitie.com/)](../Documents/Bildschirmfoto 2021-11-02 um 10.22.28.png)

### Datensicherheit und ich?

### Was hat sich verändert?


# Kleine Einführung in Variablen
Bitte ergänzen Sie in dem kleinen Skript unten ihr Geburtsjahr. 

```{r Wie lange muss ich bis zur Rente arbeiten?}
geburt <- 1976 # bitte Geburtsjahr eingeben [YYYY eingeben]
alter <- 2021 - geburt
# wir berechnen Ihr Alter im Jahr 2020 (für das gesamte Jahr)
alter

# Wir berechnen Ihr Rentenalter und gehen davon aus, dass Sie mit 69 in  Rente gehen können.
rentenalter <- geburt + 69
rentenalter

# Wir gehen davon aus, dass Sie in drei Jahren anfangen werden zu arbeiten.
arbeitsbeginn <- 2023
arbeitsjahre <- rentenalter - arbeitsbeginn

# Voila: wenn alles klappt, arbeiten Sie so lange.
arbeitsjahre

```
# Variablen im Reporting verwenden
## Variablen in Dokumente einbauen.
Wir können die Ergebnisse von Variablen direkt in unseren Report einbetten, wenn der codechunk zuvor ausgeführt wurde. Schauen Sie sich das Beispiel unten an und ersetzen Sie die letzte Variable davon. 

### Einsatz von dynamischen Variablen im Dokument
Ich bin im Jahr `r geburt` geboren und werde im Jahr 2021 `r alter` Jahre alt sein. Das bedeutet, dass ich wahrscheinlich `r arbeitsjahre` Jahre arbeiten darf. Wenn Sie mal nachdenken, wie das Leben vor `r arbeitsjahre` Jahren, also im Jahr `r 2021-arbeitsjahre` aussah (ohne Smartphone oder Netflix), dann kommt in den nächsten `XX ersetzen Sie hier den richtigen Wert` Jahren ganz schön viel Veränderung auf mich zu!  

### Eine kleine Geschichte mit Text- und Zahlen-Variablen

Schreiben Sie eine  kleine Geschichte mit den Werten, die Sie in dieses Dokument einbauen. 

```{r Mini-Geschichte}
hund_name <- "dog"
katze_name <- "cat"
google_trefferanzahl <- 3847

```

