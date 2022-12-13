# LaTeX-Unterlagen


> In diesem Repository befinden sich die LaTeX-Unterlagen zum Modul.

## Inhalt

Der Inhalt entspricht dem Text der Aufgabe 2 des Modul.

Es kann sinnvoll sein, sich die PDF zur Aufgabe zwei noch einmal
anzusehen.


## PDF erstellen


Das geht ganz schnell und einfach:

* Zuerst installieren wir LaTeX (tug.org/texlive/)
* Dann nutzen wir PDFLaTeX zum Erstellen des PDF
	_"pdflatex ./task.tex"_ (Das muessen wir mehrfach machen, damit die PDF auch fertig wird)
* Alternativ koennen wir auch einfach LaTeX Mk nutzen 
	_"latexmk -pdf ./task.tex"_


**!!ACHTUNG!!**
LaTeX erstelle einige nervige Dateien (.aux, .log). Diese muss man loeschen bevor
man einen Commit mit seinen Aenderungen macht!
