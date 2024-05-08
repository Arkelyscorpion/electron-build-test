1. install angular and electron \
`npm install @angular/cli` \
`npm install electron@latest`

2. install electron-builder to build .exe\
`npm install electron-packager --save-dev`

3. Run `npm install`
4. Run `electron-packager <sourcedir> <appname> --platform=win32 --arch=x86_64`

Refer:\
https://stackoverflow.com/questions/40615837/how-to-compile-an-electron-application-to-a-exe \
https://buddy.works/tutorials/building-a-desktop-app-with-electron-and-angular