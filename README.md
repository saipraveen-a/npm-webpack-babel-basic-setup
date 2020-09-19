# NPM, Webpack and Babel basic setup

    npm init

**Webpack**
    
    npm install webpack webpack-cli webpack-dev-server --save-dev 
    (--save-dev is not required if using Node 5 or higher)
    
**Babel**

    npm install @babel/cli @babel/core @babel/node @babel/preset-env @babel/preset-react @babel/register --save-dev
    
**JS/JSX & CSS Loaders, HTML, SASS Loaders**

    npm install babel-loader style-loader css-loader sass-loader html-loader


**Building and starting server**

    npm install
    
    npm run build

    npm start

**References**

    https://medium.com/@jeffrey.allen.lewis/the-ultimate-2018-webpack-4-and-babel-setup-guide-npm-yarn-dependencies-compared-entry-points-866b577da6a

    https://www.valentinog.com/blog/babel/
