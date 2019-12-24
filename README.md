# LaTeX-Vorlage für wissenschaftliche Ausarbeitungen
Das folgende Repository beinhaltet eine LaTeX Vorlage für wissenschaftliche Ausarbeitungen. Die Vorlage enthält Musterbeispiele zu Abbildungen, Tabellen und Verweise. Weiterhin ist eine kompilierte .PDF-Datei innerhalb des Projektes zu finden, welches den Umfang des Projektes darstellen soll.

![GitHub](https://img.shields.io/github/license/EminYagmahan/LaTex_Thesis_Template)
![GitHub Repo Size](https://img.shields.io/github/repo-size/EminYagmahan/LaTex_Thesis_Template)

## Screenshots

<p align="center">
  <img title="Titelseite" src="https://imgur.com/Dc7Aae5.png" width="300"/>
  <img title="Text_01" src="https://imgur.com/M6i6IbG.png" width="300"/>
  <img title="Text_02" src="https://imgur.com/IEMUiR9.png" width="300"/>
  <img title="Quellenverzeichnis" src="https://imgur.com/jO488KU.png" width="300"/>
</p>


## Installationsanleitung
Entwickelt und getested wurde die Vorlage unter TeXstudio Ver. 2.12.16. Als Standardkompiler dient PDFLaTeX sowie Biber als Standardbibliographiesoftware. (DIe Nutzung der empfohlenen IDE TeXStudio ist optional. DIe Nutzung von IDEs wie Atom und VS Code mit esprenchenden LaTeX Plugins, ermöglichen ebenso einen guten Workflow)

### Voraussetzungen

1. LaTeX Umgebung für die Betriebssysteme Linux, Mac OS und Windows (Installationsanleitung: [The LaTeX Project](https://www.latex-project.org/get/))
2. Schreib- bzw. Entwicklungsumgebung wie TeXStudio (Linux, Mac OS und Windows) (Installationsanleitung: [TeXStudio][https://www.texstudio.org/])


### Einrichtung von TeXStudio

Unter `Optionen > TeXStudio konfigurieren...` ist nach der Installation der LaTeX Umgebung der Installationsort von PDFLaTeX mit folgenden Parametern hinzuzufügen:

- `"*PATH/pdflatex" -synctex=1 -interaction=nonstopmode %.tex`

Ebenso ist der Installationspfad von Biber hinzuzufügen, sofern TeXStudios Standardparametern, nicht den korrekten Werten entsprechen.

<p align="center">
  <img title="Titelseite" src="https://imgur.com/iVfgS5J.png" width="700"/>
</p>









```latex
%------------------------------------------------------------------------------------------------------------------
%  Title Page Configuration (modify this section only!)
%------------------------------------------------------------------------------------------------------------------
\newcommand{\DegreeThesisType}{Masterthesis}
\newcommand{\TitleOfWork}{Ethisch Aspekte der künstlichen Intelligenz in der Medizin}
\newcommand{\DegreeType}{Master of Science}
\newcommand{\Faculty}{Fachbereich Gesundheit}
\newcommand{\Organisation}{Technischen Hochschule Musterstadt}
\newcommand{\AuthorName}{Emin Yagmahan}
\newcommand{\PublicDateMY}{Januar 2020}
\newcommand{\Referent}{Prof. Dr. Max Mustermann}
\newcommand{\Korreferent}{Dr. Max Mustermann}
```
