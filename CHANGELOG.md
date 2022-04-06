# Changelog

Scribe-Data tries to follow [semantic versioning](https://semver.org/), a MAJOR.MINOR.PATCH version where increments are made of the:

- MAJOR version when we make incompatible API changes
- MINOR version when we add functionality in a backwards compatible manner
- PATCH version when we make backwards compatible bug fixes

Emojis for the following are chosen based on [gitmoji](https://gitmoji.dev/).

# Scribe-Data 1.0.0

### 🚀 Deployment

Releasing a Python package so that codes are accessible and the structure is set for future project iterations.

### ✨ Features

- Data updates are done via a single file that loads new formatted data into each Scribe application.

### 🗃️ Data

- Data extraction and formatting scripts for each of Scribe's current languages as well as those with significant data on Wikidata are included.

### 🐞 Bug Fixes

- The data update process has been fixed to work for all queries.

### ♻️ Code Refactoring

- The data update process now updates files in Android and Desktop directories if they're present.
