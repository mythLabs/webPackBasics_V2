Sample application with Webpack 3 configuration file enabled bundling [loader] for ES6 js and SCSS files while css gets written to a new file dynamically and running using webpack-dev-server. 


#run
npm install
npm run build  //run server
npm run build:prod //gives files

dev-dep used
sass-loader   //loading sass 
node-sass    //compiling sass
css-loader   //loading css
extract-text-webpack-plugin   //writing css to file
babel-core   //convert es6
babel-loader   //load es6
babel-preset-env //conversion rules preset
html-loader //loading html
html-webpack-plugin  //displaying file
file-loader //loading file