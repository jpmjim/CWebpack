# CWebpack
Curso de Webpack

Instalación de los paquetes "dependencia de desarrollo -D"

- npm install webpack webpack-cli -D

- npm install babel-loader @babel/core @babel/preset-env @babel-plugin-transform-runtime -D

- npm install html-webpack-plugin -D

- npm install mini-css-extract-plugin css-loader -D

- npm install stylus stylus-loader -D

- npm install copy-webpack-plugin -D

- npm install url-loader file-loader -D

- npm install css-minimizer-webpack-plugin terser-webpack-plugin -D

- npm install dotenv-webpack -D

- npm install clean-webpack-plugin -D

- npm install webpack-dev-server -D

- npm install webpack-bundle-analyzer -D
  "para generar un reporte de la compilación con webpack"
    npx webpack --profile --json > stats.json
  "para ver el reporte visualmente"
    npx webpack-bundle-analyzer stats.json