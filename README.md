# documentation

Documentation for Skiosa in LaTeX

# Create Release

To create a Release with the PDF File you have to do the following steps

* Commit and Push your Changes
* Create a Tag like `git tag -a v0.0.3 -m "My Tag Message"`
* Push the new Tag `git push --tags`

After that the CI/CD – Pipeline will be triggered by the created Tag and will publish a new PDF File.

# UML Diagramms

UML Diagramms are found in ./uml/ UML Diagramms are each in one File with Fileextension .uxf and are edited with theumletteam.umlet.

## Import UML diagramm in LaTeX

To import the created UML diagramm in LaTeX do the following steps:

* Create your UML Diagramm
* Export as PNG (F1 > Umlet: Export as PNG)
* Import PNG in Latex with figure Enviroment