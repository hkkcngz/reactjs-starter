## reactjs-starter

### install ReactJS quick app 
  - npx create-react-app my-app


  Creating a TypeScript app#
    You can start a new TypeScript app using templates. To use our provided TypeScript template, append --template typescript to the creation command.

  - npx create-react-app my-app --template typescript

### Scripts

  #### Run
    npm start or yarn start

  #### Test
    npm test or yarn test

  #### Build
    npm run build or yarn build
  
  
### HTML to React Components
  1. npm i -g html-to-react-components
  2. add data-components="component-name" to all tags that you want to convert to a component. 
  3. Open terminal and write path of your html => html2react "./html/index.html"
    - if you have more than index.html, multi way to make component => html2react "./src/*.html"
  
  
### Adding SASS 
  1. npm install node-sass or yarn add node-sass
  2. Rename .css to .scss
  3. @import './sass/main.scss';
  
  
  ### Issues 
  
  - Error: Node Sass version 5.0.0 is incompatible with ^4.0.0
      - npm uninstall node-sass
      - npm install node-sass@4.14.1
        Or
      - yarn remove node-sass
      - yarn add node-sass@4.14.1

### First Debug: <a href="#" ==> <Link to="/"
  npm install react-router-dom
  or
  yarn add react-router-dom
             
  - then change all <a href="#" to <Link to="/". 
  
  
### Second Debug: CSS @Font-face not found
  - You need to change all url OR just move fonts folder to "scss" folder. 


#### Thanks 
  - roman01la
  
  
#### Sources:
  - https://reactrouter.com/web/guides/quick-start
  - https://scotch.io/@micwanyoike/how-to-add-fonts-to-a-react-project
  - https://github.com/roman01la/html-to-react-components
