# Webpack

För att få applikationen att bygga med webpack:

Kör följande kommandon för att installera allt du behöver:

```
# initiera npm
npm init -y

# installera webpack (-D = --save-dev)
npm install -D webpack webpack-cli webpack-dev-server webpack-merge

# installera loaders och plugins
npm install -D style-loader css-loader file-loader html-loader html-webpack-plugin

# installera lodash
npm install lodash
```

Lägg in följande skript i package.json:

```
"serve": "webpack-dev-server --config webpack.dev.js",
"build": "webpack --config webpack.prod.js"
```
