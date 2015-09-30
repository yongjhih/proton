# proton

```sh
asar pack --exclude-hidden . proton.asar
npm install electron-prebuilt --save-dev
rm -fr node_modules/electron-prebuilt/dist/resources/default_app
mv proton.asar node_modules/electron-prebuilt/dist/resources/
mv node_modules/electron-prebuilt/dist/electron node_modules/electron-prebuilt/dist/proton

node_modules/electron-prebuilt/dist/proton
```
