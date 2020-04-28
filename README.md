# swagger-ui-desktop

**A desktop wrapper application for swagger-ui**

This is a [swapper-ui](https://github.com/swagger-api/swagger-ui) wrapper application built using [Electron](http://electron.atom.io/) application based on the  within the Electron documentation.

## To run the application locally without building
```bash
# Clone this repository
git clone https://github.com/shirishp/swagger-ui-desktop.git
# Go into the repository
cd swagger-ui-desktop
# Install dependencies and run the app
npm install && npm start
```

## To build application locally
```bash
# Clone this repository
git clone https://github.com/shirishp/swagger-ui-desktop.git
# Go into the repository
cd swagger-ui-desktop
# Install dependencies
npm install
# Install electron-packager
npm install electron-packager -g
# Build application for Mac OS X
electron-packager . "Swagger UI Desktop" --platform=darwin --arch=x64 --app-version=0.35.6 --icon=images/icon.icns --out=dist
```

Read full documentation on how to use [electron-packager](https://github.com/electron-userland/electron-packager)

## Screenshot
![Screenshot of Swagger-UI-Desktop running on Mac OS X](swagger-ui-desktop-screenshot.png?raw=true)

#### License [CC0 (Public Domain)](LICENSE.md)
