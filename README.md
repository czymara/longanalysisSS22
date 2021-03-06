
# Forschungspraktikum I&II: Längsschnittdatenanalyse in R

## Kursbeschreibung

Längsschnittdaten, also die wiederholte Beobachtung der gleichen Einheiten, bieten verschiedene Vorteile gegenüber Querschnittsdaten. So lassen sich nicht nur Trends und zeitliche Entwicklungen analysieren, sondern (unter bestimmten Voraussetzungen) auch Aussagen über die Kausalität von Effekten treffen - ein Hauptziel quantitativer Forschung. Zunehmende Dauer und Verfügbarkeit von Längsschnittdaten zu verschiedenen Themengebieten eröffnen eine Vielzahl neuer Möglichkeiten für die empirischen Sozialwissenschaften. Das Forschungspraktikum wird das Werkzeug zur Aufbereitung und Analyse von Längsschnittdaten vermitteln (Datentypen, Methoden, Annahmen) und die Implementierung in der Programmiersprache R zeigen.

*Es handelt sich um einen fortgeschrittenen Methodenkurs - statistisches Grundwissen, Kenntnisse in code-basierter Datenanalyse (z. B. mit R, Stata oder Python) sowie generelles Interesse an quantitativer Forschung werden vorausgesetzt.* Die Kurssprache ist Deutsch, Hausarbeiten können gerne auf Englisch geschrieben werden.


## Organisatorisches

### Ablauf
Jede Sitzung besteht aus einem Vorlesungsteil und einem Tutorial, in dem die Studierenden alleine oder in Gruppen das Gelernte praktisch anwenden sollen. Die Lösungen werden in der Folgesitzung gemeinsam besprochen.

Das Forschungspraktikum ist als Präsenzveranstaltung geplant. Falls die Pandemieentwicklung dies verlangt, wird die Veranstaltung ins Onlineformat überführt.

### Kursmaterialien & Software
Folien und Code werden über GitHub bereitgestellt (unter [czymara.com/FoPra](https://czymara.com/FoPra)). *Zur Kommunikation tragen sie sich bitte unter [czymara.com/FoPra-mail](https://czymara.com/FoPra-mail) in die Mailingliste für diesen Kurs ein.*

Zur Bearbeitung der Aufgaben werden [R](https://cloud.r-project.org/) (Programmiersprache) und [RStudio](https://www.rstudio.com/products/rstudio/download/) (Entwicklungsumgebung) benötigt. [Dieses Video](https://www.youtube.com/watch?v=lVKMsaWju8w) ist eine Anleitung speziell zum Installieren von R und RStudio. Eine Einführung in R gibt es beispielsweise [hier](https://www.cspoerlein.com/files/rtutorial#prerequisites) und in [unzähligen weiteren Tutorials](https://www.google.com/search?q=r+introduction).

### Leistungsnachweis
Erfolgreiche Kursteilnahme erfordert eine aktive Teilnahme und Bearbeitung der einzelnen Tutorials. Die Hausarbeit soll eine selbstdurchgeführte Längsschnittdatenanalyse zu einem Thema nach Wahl sein. Der Schwerpunkt dieser Arbeit wird auf der Datenauswertung liegen. Abgabedatum ist der _01. September 2022_ per E-Mail an [cc(at)soz.uni-frankfurt.de](mailto:cc@soz.uni-frankfurt.de).

### Tutorin
Für Fragen und Probleme (insbesondere zu R) steht Subin Chang zur Verfügung unter [s1786518(at)stud.uni-frankfurt.de](mailto:s1786518@stud.uni-frankfurt.de).

## Sessions

- Data for all tutorials are available [here](https://github.com/czymara/longanalysisSS22/blob/main/data/longanalysis_datasets.zip?raw=true) (password will be made available via e-mail).

| # | Date | Topic | Lecture | Tutorial | Literature |
| --- | --- | --- | --- | --- | --- |
| 01 | 14.04. | Welcome & introduction to R | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_01.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_01.html) | Wickham & Grolemund (2017). [R for Data Science.](https://r4ds.had.co.nz/) O'Reilly. |
| 02 | 21.04. | Directed acyclic graphs | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_02.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_02.html) |  Elwert (2013). [Graphical causal models](https://link.springer.com/chapter/10.1007/978-94-007-6094-3_13). In: Handbook of causal analysis for social research (245 - 273). Springer Science & Business Media. |
| 03 | 28.04. | Linear regression with cross-sectional and longitudinal data | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_03.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_03.html) | Cinelli, Forney & Pearl (forthcoming). [A crash course in good and bad controls](https://ftp.cs.ucla.edu/pub/stat_ser/r493.pdf). Sociological Methods and Research. |
| 04 | 05.05. | Preparing panel data | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_04.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_04.html) | Andreß, Golsch & Schmidt (2014). [Applied panel data analysis for economic and social surveys](https://link.springer.com/book/10.1007/978-3-642-32914-2). Chapter 2 (15 - 48). Springer Science & Business Media |
| 05 | 12.05. | Fixed Effects | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_05.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_05.html) | Andreß, Golsch & Schmidt (2014). Applied panel data analysis for economic and social surveys. Chapter 4.1 (119 - 174). Springer Science & Business Media. |
| 06 | 19.05. | Mundlak & Within-Between models | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_06.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_06.html) | Bell, Fairbrother & Jones (2019). [Fixed and random eﬀects models: making an informed choice](https://link.springer.com/article/10.1007/s11135-018-0802-x). Quality & Quantity 53 (2). 1051 - 1074. |
| - | 26.05. | Christi Himmelfahrt | - | - | - |
| 07 | 02.06. | Linear and non-linear probability models | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_07.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_07.html) | Mood (2010). [Logistic regression: Why we cannot do what we think we can do, and what we can do about it](https://academic.oup.com/esr/article/26/1/67/540767). European Sociological Review 26 (1). 67 - 82. |
| 08 | 09.06. | Research on potential data sets | - | - | [Overview of data sets](https://github.com/czymara/longanalysisSS22/blob/main/data/datasources.md) |
| - | 16.06. | Fronleichnam | - | - |  - |
| 09 | 23.06. | Logistic Fixed & Random Eﬀects models | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_09.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_09.html) | Andreß, Golsch & Schmidt (2014). Applied panel data analysis for economic and social surveys. Chapter 5.1. Springer Science & Business Media |
| 10 | 30.06. | Natural experiments | [Slides](https://github.com/czymara/longanalysisSS22/blob/main/slides/ALD_slides_10.pdf) | [Solution](https://htmlpreview.github.io/?https://github.com/czymara/longanalysisSS22/blob/main/exercises/ALD_tutorial_10.html) & [Video](https://youtu.be/03K-aX17x1k) |  Muñoz, Falcó-Gimeno & Hernández (2020). [Unexpected event during survey design: Promise and pitfalls for causal inference](https://cambridge.org/core/journals/political-analysis/article/unexpected-event-during-survey-design-promise-and-pitfalls-for-causal-inference/E9DB24A62172D1EB2116FEFFEAE45998). Political Analysis 28 (2). 186 - 206. |
| 11 | 07.07. | Specify research question | - | - | - |
| 12 | 14.07. | Abschlusssitzung | Link via e-mail | - |  Academy of Sociology (2020). [Checklist for Quantitative Social Science Articles](https://osf.io/mw59u/). |

