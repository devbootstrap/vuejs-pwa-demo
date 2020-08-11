# Demo Vue JS PWA App

Basic app that shows how to setup and install a PWA app on a Macbook and iPhone all in a local development environment.

## Documentation

Please refer to this [document](./Technology Architecture PWA Serverless Notes.pdf) here. This explains all about the process to create this app as well as creating the CA Root certificate, installing it on a Macbook and iPhone, creating a Domain SSL Certificate from that Root certificate using the [createDomainCertfromCA.sh](./createDomainCertfromCA.sh) script and serving the app via HTTPS on your Macbook and loading / installing the PWA on your iPhone using a custom local devevelopment domain.

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
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
