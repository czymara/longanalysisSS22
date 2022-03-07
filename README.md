
# Forschungspraktikum I und II: Längsschnittdatenanalyse in R (Goethe University Frankfurt, summer term 2022)

## Kursbeschreibung

Längsschnittdaten, also die wiederholte Beobachtung der gleichen Einheiten, bieten verschiedene Vorteile gegenüber Querschnittsdaten. So lassen sich nicht nur Trends und zeitliche Entwicklungen analysieren, sondern (unter bestimmten Voraussetzungen) auch Aussagen über die Kausalität von Effekten treffen - ein Hauptziel quantitativer Forschung. Zunehmende Dauer und Verfügbarkeit von Längsschnittdaten zu verschiedenen Themengebieten eröffnen eine Vielzahl neuer Möglichkeiten für die empirischen Sozialwissenschaften. Das Forschungspraktikum wird das Werkzeug zur Aufbereitung und Analyse von Längsschnittdaten vermitteln (Datentypen, Methoden, Annahmen) und die Implementierung in der Programmiersprache R zeigen.

*Es handelt sich um einen fortgeschrittenen Methodenkurs - statistisches Grundwissen, Kenntnisse in code-basierter Datenanalyse (z. B. mit R, Stata oder Python) sowie generelles Interesse an quantitativer Forschung werden vorausgesetzt.* Die Kurssprache ist Deutsch, Hausarbeiten können gerne auf Englisch geschrieben werden.


## Organisatorisches

### Ablauf
Jede Sitzung besteht aus einem Vorlesungsteil und einem Tutorial, in dem die Studierenden alleine oder in Gruppen das Gelernte praktisch anwenden sollen. Die Lösungen werden in der Folgesitzung gemeinsam besprochen.

Das Forschungspraktikum ist als Präsenzveranstaltung geplant. Falls die Pandemieentwicklung dies verlangt, wird die Veranstaltung ins Onlineformat überführt.

### Kursmaterialien & Software
Folien und Code werden hier über GitHub bereitgestellt. Zur Bearbeitung der Aufgaben werden [R](https://cloud.r-project.org/) (Programmiersprache) und [RStudio](https://www.rstudio.com/products/rstudio/download/) (Entwicklungsumgebung) benötigt. Eine Einführung in R gibt es beispielsweise [hier](https://www.cspoerlein.com/files/rtutorial#prerequisites) und in [unzähligen weiteren Tutorials](https://www.google.com/search?q=r+introduction). [Dieses Video](https://www.youtube.com/watch?v=lVKMsaWju8w) ist eine Anleitung speziell zum Installieren von R und RStudio.

### Leistungsnachweis
Erfolgreiche Kursteilnahme erfordert eine aktive Teilnahme und Bearbeitung der einzelnen Tutorials. Die Hausarbeit soll eine selbstdurchgeführte Längsschnittdatenanalyse zu einem Thema nach Wahl sein. Der Schwerpunkt dieser Arbeit wird auf der Datenauswertung liegen. Abgabedatum ist der _01. September 2022_ per E-Mail an [cc[at]soz.uni-frankfurt.de](mailto:cc@soz.uni-frankfurt.de).

### Tutorin
Für Fragen und Probleme (insbesondere bezüglich R) steht Subin Chang zur Verfügung.

## Sessions

- Data for all tutorials are available [here (coming soon)](...).

| # | Date | Topic | Lecture | Tutorial | Literature |
| --- | --- | --- | --- | --- | --- |
| 00 | 14.04. | Welcome & introduction to R | [Slides (coming soon)](https://htmlpreview.github.io/?https://github.com/czymara/xxx) | [Task (coming soon)](https://htmlpreview.github.io/?https://github.com/czymara/xxx) | Wickham & Grolemund (2017). [R for Data Science.](https://r4ds.had.co.nz/) O'Reilly. |
| 01 | 21.04. | Directed acyclic graphs | tba | tba |  Elwert (2013). [Graphical causal models](https://link.springer.com/chapter/10.1007/978-94-007-6094-3_13). In: Handbook of causal analysis for social research (245 - 273). Springer Science & Business Media. |
| 02 | 28.04. | Linear regression with cross-sectional and longitudinal data | tba | tba | Wooldridge (2012). [Introductory econometrics: A modern approach](https://economics.ut.ac.ir/documents/3030266/14100645/Jeffrey_M._Wooldridge_Introductory_Econometrics_A_Modern_Approach__2012.pdf). Chapter 3 (68 - 94). Cengage Learning. |
| 03 | 05.05. | Preparing panel data | tba | tba | Andreß, Golsch, & Schmidt (2014). [Applied panel data analysis for economic and social surveys](https://link.springer.com/book/10.1007/978-3-642-32914-2). Chapter 2 (15 - 48). Springer Science & Business Media |
| 04 | 12.05. | Fixed Effects | tba | tba | Andreß, Golsch, & Schmidt (2014). Applied panel data analysis for economic and social surveys. Chapter 4.1 (119 - 174). Springer Science & Business Media. |
| 05 | 19.05. | Random Effects | tba | tba | Andreß, Golsch, & Schmidt (2014). Applied panel data analysis for economic and social surveys. Chapter 4.1 (147 ff.). Springer Science & Business Media. |
| - | 26.05. | Christi Himmelfahrt | - | - | - |
| 06 | 02.06. | Mundlak & Within-Between models | tba | tba | Bell, Fairbrother & Jones (2019). [Fixed and random eﬀects models: making an informed choice](https://link.springer.com/article/10.1007/s11135-018-0802-x). Quality & Quantity 53 (2). 1051 - 1074. |
| 07 | 09.06. | Research on potential data sets | - | - | Overview of data sets |
| - | 16.06. | Fronleichnam | - | - |  - |
| 08 | 23.06. | Linear and non-linear probability models | tba | tba | Mood (2010). [Logistic regression: Why we cannot do what we think we can do, and what we can do about it](https://academic.oup.com/esr/article/26/1/67/540767). European Sociological Review 26 (1). 67 - 82. |
| 09 | 23.06. | Logistic Fixed & Random Eﬀects models | tba | tba | Andreß, Golsch, & Schmidt (2014). Applied panel data analysis for economic and social surveys. Chapter 5.1. Springer Science & Business Media |
| 10 | 30.06. | Natural experiments | tba | tba |  Muñoz, Falcó-Gimeno & Hernández (2020). [Unexpected event during survey design: Promise and pitfalls for causal inference](cambridge.org/core/journals/political-analysis/article/unexpected-event-during-survey-design-promise-and-pitfalls-for-causal-inference/E9DB24A62172D1EB2116FEFFEAE45998). Political Analysis 28 (2). 186 - 206. |
| 11 | 07.07. | Specify research question | - | - | - |
| 12 | 14.07. | Abschlusssitzung | - | - |  Academy of Sociology (2020). [Checklist for Quantitative Social Science Articles](https://osf.io/mw59u/). |

