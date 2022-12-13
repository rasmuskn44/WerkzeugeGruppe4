# LaTeX-Unterlagen

> In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul.


## Inhalt

Der Inhalt entspricht dem Text der Aufgabe 2 des Modul.

Es kann sinnvoll sein, sich die PDF zur Aufgabe zwei noch einmal
anzusehen.


## PDF erstellen

Das geht ganz schnell und einfach:

* Zuerst installieren wir [LaTeX](tug.org/texlive/)
* Dann nutzen wir PDFLaTeX zum Erstellen des PDF[^1] (Das muessen wir mehrfach machen, damit die PDF auch fertig wird)
* Alternativ koennen wir auch einfach LaTeX Mk nutzen[^2]
	


***!!ACHTUNG!!***
LaTeX erstelle einige nervige Dateien _(.aux, .log)_. Diese muss man loeschen bevor
man einen Commit mit seinen Aenderungen macht!

[^1]:"pdflatex ./task.tex" 
[^2]:"latexmk -pdf ./task.tex"
