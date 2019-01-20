# build-a-bot

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
or
npm run build -- --mode=production

npm run build -- --mode=staging
```

In server index.js add
```
app.use('/', express.static('dist', { index: 'index.html' }));
```

Copy dist folder from an app to the server:
```
cp -r ../vue-build-a-bot/dist .
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
