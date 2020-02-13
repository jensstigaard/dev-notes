## ElectronJS+VueJS project with following tech/plugins
 - Vuex - state
 - Vue Router
 - Pug - easy templating
 - SASS - CSS pre-processor
 - TypeScript
 - ESLint
 - Prettier
 - Jest
 
 Prerequisites: [Node](https://nodejs.org/en/) + [Yarn](https://yarnpkg.com/)
 
 How to setup project:
 ```sh
 vue create {projectname}
 ```
### Initialization selections
1) Please pick a preset: Manually select features
2) Check the features needed for your project: (Select only these) 
 - Typescript
 - Router
 - Vuex
 - CSS Pre-processors
 - Linter / Formatter
 - Unit Testing

3) Use class-style component syntax? **Yes** (not mandatory)

4) Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)? **No**

5) Use history mode for router? (Requires proper server setup for index fallback
in production) **No** (does not make sense in ElectronJS app)

6) Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported
by default): **Sass/SCSS (with dart-sass)**

7) Pick a linter / formatter config: **Prettier**

8) Pick additional lint features: (Press `<space>` to select, `<a>` to toggle all, `<i>` to invert selection) **Lint on save**

9) Pick a unit testing solution: **Jest**

10) Where do you prefer placing config for Babel, ESLint, etc.? **In dedicated config files**

11) Save this as a preset for future projects? (y/N) **n**

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

```sh
yarn electron:serve
```
