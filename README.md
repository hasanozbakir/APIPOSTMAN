# APIPOSTMAN

### Installing and running Newman

To get started using Newman, install Node.js, then Newman. Then you can run your collections.

Install Newman from npm globally on your system, which allows you to run it from anywhere:

```
$ npm install -g newman
```
In order to get a fancy report install newman-reporter-htmlextra

[![Htmlextra Reporter](https://github.com/DannyDainton/newman-reporter-htmlextra/blob/HEAD/examples/NewmanHtmlextraReporterLogo.png)](https://www.npmjs.com/package/newman-reporter-htmlextra)

```
npm install -g newman-reporter-htmlextra
```

Download **Collection**, **Environment** by using **Export** option on **Share**. 

Finally, you can use the following command

```
newman run rickandmorthy.postman_collection.json -e rickandmorty.postman_environment.json -r htmlextra
```
:white_square_button: Then open the result by using web browser
