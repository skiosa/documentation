# documentation
Documentation for Skiosa in LaTeX

# Create Release
To create a Release with the PDF File you have to do the following steps
- Commit and Push your Changes
- Create a Tag like ``git tag -a v0.0.3 -m "My Tag Message"``
- Push the new Tag ``git push --tags``

After that the CI/CD – Pipeline will be triggered by the created Tag and will publish a new PDF File.
