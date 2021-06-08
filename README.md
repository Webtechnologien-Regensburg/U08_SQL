---
title: SQL Grundlagen
author: Jakob Fehle
documentclass: scrartcl
classoption:
  - a4paper
header-includes: |
    \usepackage{german} 
	\usepackage{xcolor}
    \usepackage[a4paper,left=2.5cm, right=2.5cm,top=2.5cm, bottom=3cm]{geometry}
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Webtechnologien}
    \lhead{Übungsblatt}
    \fancypagestyle{plain}{
      \fancyhf{}
      \rhead{Webtechnologien}
      \lhead{Übungsblatt}}





---


# 09 | Einfache SQL-Abfragen

In dieser Aufgabe sollen Sie einfache SQL-Abfragen stellen, um die gewünschten Daten aus der Ihnen zur Verfügung gestellten _MovieDatabase_ auszulesen. Verwenden Sie das in der Vorlesung besprochene Tool  [\textcolor{blue}{DB Browser für SQLite}](https://sqlitebrowser.org/), um die Datenbank zu importieren und ihre SQL-Abfragen zu formulieren. Schreiben Sie anschließend SQL-Queries, mit welchen Sie

1. alle Filmtitel auflisten.

2. alle Filmtitel und die dazugehörigen Erscheinungsjahre auflisten.
3. alle amerikanischen Filme ausgeben.
4. das Jahr herausfinden, in dem der Film Avatar erschienen ist.
5. alle Filme, die länger als 150 Minuten dauern, auflisten.
6. alle Filme, die im Jahr 2020 erschienen sind, ausgeben.
6. alle Filme, die vor dem Jahr 2000 erschienen sind, auflisten.
7. die Anzahl aller in der Datenbank gespeicherten Filmen ausgeben.
8. die Anzahl aller in der Datenbank gespeicherten amerikanischen Filme ausgeben.
9. alle Filme, die zwischen 160 und 180 Minuten dauern, auflisten.
10. alle amerikanischen Filme, die länger als 110 Minuten und weniger als 160 Minuten dauern, ausgeben.

------

*Abgabekriterien:*

Laden Sie Ihre Antworten bis spätestens 17.06.2020 (23:59 Uhr) als zip-komprimierten Ordner auf GRIPS hoch. Benennen Sie die einzelnen Dateien pro Aufgabe sinnvoll und verwenden Sie geeignete Formate:

- Aufgabe: Eine SQL-Datei (.sql) mit allen Queries


Der Name der Datei ergibt sich aus dem Präfix „Übung_WT_SS21“, der Nr. des Übungsblattes, ihrem Vor- und Nachnamen jeweils getrennt durch _ .

 

Beispiel: **Übung_WT_SS21_9_Max_Mustermann.zip**

