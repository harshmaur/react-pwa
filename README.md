## VS Code Settings

```
{
  "eslint.alwaysShowStatus": true,
  "editor.fontSize": 14,
  "editor.fontLigatures": true,
  "editor.fontFamily": "Fira Code",
  "editor.tabSize": 2,
  "editor.renderIndentGuides": true,
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": false
  },
  "eslint.autoFixOnSave": true,
  "eslint.run": "onSave",
  "editor.cursorBlinking": "phase",
  "window.openFilesInNewWindow": "off",
  "explorer.openEditors.visible": 0,
  "javascript.validate.enable": false,
  "files.exclude": {
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/.DS_Store": true,
    "**/node_modules": true
  },
  "files.associations": {
    "*.ejs": "html"
  },
  "git.confirmSync": false,
  "window.zoomLevel": 0,
  "javascript.format.enable": false,
  "files.autoSave": "off",
  // "workbench.colorTheme": "Cobalt2",
  "git.ignoreLegacyWarning": true,
  "extensions.ignoreRecommendations": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "git.enableSmartCommit": true,
  "editor.minimap.enabled": true,
  "importCost.javascriptExtensions": [
    "\\.js",
    "\\.jsx?$"
  ],
  "git.autofetch": true,
  "editor.foldingStrategy": "indentation",
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true
  },
  "workbench.startupEditor": "newUntitledFile",
  "explorer.confirmDelete": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.rendererType": "dom",
  "workbench.colorTheme": "Night Owl",
  "editor.snippetSuggestions": "top",
  "emeraldwalk.runonsave": {
    "commands": [
      {
        "match": "\\.php$",
        "cmd": "prettier ${file} --write"
      }
    ]
  },
  "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
  "javascript.updateImportsOnFileMove.enabled": "never"
}
```

## Update dependencies

```
$ npx npm-check-updates -u
$ npm install 
```

## Plugins 

![Imgur](https://i.imgur.com/BRLtf40.png)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
