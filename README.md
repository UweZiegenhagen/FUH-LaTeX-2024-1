# FUH-LaTeX-2024-1

Kursmaterialien für den ersten LaTeX-Kurs an der Fernuni Hagen im Jahr 2024

Die Materialien können frei von jedermann genutzt und verändert werden, entsprechende Hinweise auf meine Urheberschaft werden aber gern gesehen.

## Wie kommt man an die Materialien?

git installieren und dann auf der Kommandozeile

git clone https://github.com/UweZiegenhagen/FUH-LaTeX-2024-1.git

Updates holt man wie folgt, lokal geänderte Dateien werden dabei überschrieben!

git fetch --all
git reset --hard origin/main

In den nächsten Monaten wird das Repository noch öffentlich zugänglich sein, 
irgendwann werde ich es auf privat setzen. Ihr könnt es gern forken, aber dann
vorzugsweise in ein privates Repo da ich gern Wildwuchs verhindern möchte.

## Anmeldung für FUH-Student*innen

Via https://cryptpad.fr/form/#/2/form/view/rkMor59InKpcxcIonC42tgs0YhmJ3feIjTRYURl8k6M/

## Der Kurs

Der Kurs findet an mehreren Samstagen online statt, als Plattform nutzen wir BigBlueButton von senfcall.de, der Link wird vorab per E-Mail versandt.

* **Tag 1**: 14.05.2024
* **Tag 2**: 21.05.2024
* **Tag 3**: 23.05.2024
* **Tag 4**: 28.05.2024

Jeweils grundsätzlich von 19:00 Uhr bis 22:00 Uhr, in Summe also 12 Stunden.

## Was wird benötigt

* Ein Rechner (Laptop, Desktop) mit Windows, MacOS oder Linux
* TeX Live 2024 herunterladen und installieren von tug.org/texlive. Eine Anleitung (für TeX Live 2022, es hat sich aber fast nichts geändert) habe ich unter https://www.youtube.com/watch?v=k9KhuZz7k-Q veröffentlicht.
* Wenn ihr unter Linux arbeitet: Bitte nicht aus den Distributionsquellen nehmen, sondern auch von tug.org installieren. Das TeX Live in den Distributionen ist oft nicht aktuell. 
* Mac-User installieren bitte MacTeX (auch auf der tug.org Seite frei verfügbar)
* Ein Editor zur Bearbeitung der TeX-Dateien: TeX Live bringt für Mac und Windows TeXworks mit, einen guten und einfach zu bedienenden Editor, den ich gern benutze. TeX Studio und Visual Studio Code (mit der ``LaTeX Workshop`` Erweiterung von James Yu) kann ich ebenfalls sehr empfehlen.
* Grundkenntnisse von Git bzw. Github sind nicht verkehrt, da alle meine Dateien im Github liegen.

## Kursinhalte

Die Kursinhalte sind flexibel und orientieren sich am Bedarf und Tempo der Teilnehmerinnen und Teilnehmer, mit dem folgenden Ablauf plane ich:

### Tag 1 - Grundlagen

* Vorstellung der Beteiligten, wer bin ich und wer seid ihr, was sind eure Lernziele?
* Historie von TeX und LaTeX
* Vorstellung von DANTE e.V.
* Check der Umgebungen bzw. Installationen mittels "Hallo \LaTeX" Dokument
* Klassen, Pakete, Umgebungen und Befehle
* Warum man article, report und book nicht unbedingt nutzen sollte -- die KOMA-Klassen
* Strukturierte Dokumente, ``\chapter``, ``\section`` & Co, Inhaltverzeichnisse
* Referenzen mit ``\label`` und ``\ref``
* Float-Objekte in LaTeX
* Einfache Bilder einbetten, Bilderverzeichnisse
* Einfacher Tabellensatz und Tabellenverzeichnisse


### Tag 2 - Tabellen, Mathematik, und mehr

* Wiederholung vom 1. Tag, Fragen beantworten
* Wie ich git und github nutze
* Schneller TeX mit Autohotkey & Co
* LaTeX automatisieren mit ``Arara``
* Wir bauen eine Vorlage für Seminar- und Abschlussarbeiten: ``titlepage``
* Mathematiksatz (mit ``amsmath``)
* Einheitensatz mit ``siunitx``
* Präsentationen mit ``Beamer``
* Briefe setzen mit ``scrlttr2``
* Quellcode-Listings einfügen mit dem ``Listings`` Paket


### Tag 3 - Bibliografien und Präsentationen

* Zusammenfassung vom 2. Termin, Wiederholung
* Das Paket ``nicematrix``
* Flyer basteln mit ``leaflet``
* Lebensläufe erstellen mit LaTeX
* Seitenränder einstellen mit ``geometry``
* Kopf/Fußzeilen anpassen mit ``scrpage``
* Mehr zum Bilder einbetten: ``subcaption`` 
* Mehr zu Referenzen
* Fonts für ``pdflatex``, der LaTeX Font Katalog (https://tug.org/FontCatalogue/)
* Von ``pdflatex`` zu ``lualatex``, Systemschriften nutzen
* Einfache Bibliografien -- die ``thebibliography`` Umgebung
* Bitte Jabref von www.jabref.org installieren, kostet nichts und ist sehr gut. Alternativ kann man die entsprechenden Dateien auch mit dem Texteditor bearbeiten.
* Komplexe Bibliografien mit ``biblatex``, ``biber`` und ``jabref``

### Tag 4 - TikZ und Sonstiges

* git und github
* Einzelne Seiten drehen im PDF mit dem ``pdflscape`` Paket
* Kopf/Fußzeilen anpassen mit ``scrpage``
* Mehrere Schriftarten im Dokument
* Syntaxhighlighting mit pygments
* Grafiken erstellen mit LaTeX-Paketen, kurze Einführung in ``TikZ``
* Grundlagen der Satzautomatisierung von Textsatz mit Python (Ein Weg, Serienbriefe zu erzeugen...)
* Umrahmte (farbige) Boxen mit ``tcolorbox`` (``texdoc tcolorbox``), alternativ siehe das ``mdframed`` Paket
* Editoren: ``TeXworks`` versus ``Visual Studio Code`` 
* Frage-und-Antwort-Teil: was fehlt euch noch, was wolltet ihr schon immer mal TeXen?

## Literaturempfehlungen

Empfohlen werden:

* Alle Bücher von Herbert Voß (https://www.lehmanns.de/search/quick?PHPSESSID=mi28bh61dhv2nu8keg4hjnkunumgi5ah&mediatype_id=&q=herbert+vo%C3%9F), insbesondere die Einführung
* Der LaTeX Companion in der 3. Auflage, wenn man mehr wissen möchte
 
## Weitere Links

* https://open.hpi.de/courses/git2020 Git Kurs beim HPI
* Meine Briefvorlage https://www.uweziegenhagen.de/?p=3290
* Biblatex Cheat Sheet, https://www.ctan.org/tex-archive/info/biblatex-cheatsheet

