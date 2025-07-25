
# Simple Test Github Packages

## Installation

1. Erstelle einen GitHub Personal Access Token mit `read:packages`.
2. Füge in deinem Projekt eine `.npmrc` ein:

   ```sh
   @philthy-phil:registry=https://npm.pkg.github.com/
   //npm.pkg.github.com/:_authToken=<DEIN_TOKEN>
   ```

3. Installiere das Paket:

   ```sh
   npm install @philthy-phil/ghp-test-pkg
   ```
