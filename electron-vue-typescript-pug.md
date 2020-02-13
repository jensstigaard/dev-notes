## ElectronJS+VueJS project with following tech/plugins
 - Vuex - state
 - Vue Router
 - Pug - easy templating
 - SASS - CSS pre-processor
 - TypeScript
 - ESLint
 - Prettier
 - Jest
 
 How to setup project:
 ```sh
 vue create {projectname}
 ```
### Initialization selections
1) Select only following features: 
 - Typescript
 - Router
 - Vuex
 - CSS Pre-processors
 - Linter / Formatter
 - Unit Testing
 
2) Pick a linter / formatter config: *Select option "ESLint + Prettier"*


3) Pick additional lint features: *Select only "Lint on save"*


4) Pick a unit testing solution: *Select only "Jest"*

5) Where do you prefer placing config for Babel, ESLint, etc.? *Select "In dedicated config files"*

6) Save this as a preset for future projects? *Type "N" to deny saving as preset*


You are now ready to open the project in e.g. VSCode.
```sh
cd {projectname}
```

### Add electron-builder to project
```sh
vue add electron-builder
```
Select latest ElectronJS version - e.g. 6.0.

### Add pug to project
```sh
vue add pug
```

### Update dependencies
The project is now setup, however, the ElectronJS version is not the latest. You can update this yourself.
Open `package.json`, and move the electron-dependency line to the "dependency" section. Also update the version declaration to `^8.0.0` or latest.

### Ready to launch
You are now ready to launch
