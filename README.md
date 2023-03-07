# Learning CI-CD with sonarcloud and github

This is a downloaded vulnerable python Flask app.

The main objective of this repo is to only push the code to the main branch once the code passes its SAST.

We would have three branches:

  - main
  - security
  - development

We will be working in development branch. Then push code to security and run sonarcloud. If it passes all the analysis, a pull request will be generated.
