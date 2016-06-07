TODO
====

## Before internal use

- [x] Fix unit tests ? (furder investigation)
- [x] Fix E2E tests
- [x] Electron Builder
- [ ] Nativescript
- [x] Fix async load components


## Before Open Sourcing

- [x] Change references to @JonnyBGod
- [ ] Docs (docType everything)
- [x] Generate all icons and fix references in index.html
- [ ] Redo readme.md
	- [ ] Mention need for typescript@next
- [ ] CI release all platforms for demo app
- [ ] Make sure all commands work on windows


## Improvements

- [ ] Generate ApiService from swagger endpoint
- [ ] Generate ngrx/store reducer from swagger endpoint
- [ ] Make new repo for nativescript and npm run setup:nativescript
- [ ] Make new repo for electron and npm run setup:electron
- [ ] Make clean extension scripts (npm run clean:nativescript)

## Extras (branches?)

- [ ] Windows Universal App
- [ ] Ionic
- [ ] React Native


### Before commit manual checks

```
npm test
npm start
npm run 2e2
npm run docs

npm start:desktop
npm dist:build:desktop

npm start:ios
npm start:android
... more nativescript related
```