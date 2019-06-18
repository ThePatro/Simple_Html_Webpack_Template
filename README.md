# Simple_Html_Webpack_Template
Ready-to-use template for the simple HTML website using webpack module. It is configured to minimize HTML, CSS and JS. It works for SCSS and ES6 syntax. Bootstrap is installed by default. All necessary files such as images will be automatically copied into dist directory if needed.

You can check how it looks here: [simple-html-webpack-template](https://simple-html-webpack-template.firebaseapp.com/)

# How to use it
1) Download repository
2) Run 'npm install' command to install all necessary packages
3) To run your website choose one of the options:

* `npm run build:dev` - *to build your website in the development mode*
* `npm run build:prod` - *to build your website in the production mode (with minified CSS and JS)*
* `npm run start:dev` - *to run your website on the localhost using webpack dev server in the development mode*
* `npm run start:prod` - *to run your website on the localhost using webpack dev server in the production mode (with minified CSS and JS)*

4) This project is pre-configured to deploy to the firebase hosting (which is free). To be able to do this, create new project using [firebase console](https://console.firebase.google.com/) and then:
* install firebase cli using `npm install -g firebase-tools` command
* inicialize your new project using `firebase init` command (when asked pick hosting and set '**dist**' as a public directory)

5) To build and deploy your website to the newly created firebase hosting simply run command `npm run deploy`
