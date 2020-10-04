# mygos-node-ts-base

This is a basic typescript template to start new projects from which will create a build folder and set up typescript to transpile to that folder. Additional scripts have been added to automatically watch for changes in typescript and then rerun the build.

The following commands were used to build this project from scratch

```bash
npm i --save-dev @babel/core @babel/node @babel/preset-env @babel/preset-typescript @types/node
npm i --save-dev babel-eslint eslint eslint-config-prettier eslint-plugin-prettier
npm i --save-dev nodemon tsc-watch typescript
```
