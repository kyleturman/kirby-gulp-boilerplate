# Kirby Gulp Boilerplate

Will run a PHP server on Kirby CMS with BrowserSync, Sass support, and ES6 Javascript with jQuery.

Kirby (2.5.7) is pulled from https://github.com/getkirby/starterkit

#### Install your modules
```
npm install
```

#### Local development
```
gulp
```

#### Build files for production
```
NODE_ENV=production gulp build
```

#### Deploy

You'll need to add the SFTP information in `gulpfile.js/local.config.js`

```
NODE_ENV=production gulp deploy
```
