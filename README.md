# AngularElectron

Build a native desktop timer app with Angular and Electron 

![](https://firebasestorage.googleapis.com/v0/b/firestarter-96e46.appspot.com/o/assets%2Fangular-electron-timer.gif?alt=media&token=597f37b8-8983-414c-8b08-c038621f12d7)

- Angular v4.2
- Electron v1.7
- Angular CLI v1.4 

## Basic Usage

```shell
git clone
cd angular-electron-timer
npm install

# build the app
npm run electron-build
```

Can be made into an OS specific exectable by use of [Electron Packager](https://www.npmjs.com/package/electron-packager)

```
npm install electron-packager --save-dev
electron-packager . --platform=win32
```

