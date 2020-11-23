<p align="center">
  <h3 align="center"> ChatterBox</h3>

  <p align="center">
    Springboot+Netty+Mybatis+Mysql+hibernate-JPA+WebSocket+A private real time chatting tool
    <br>
    <br>
    :clap::clap::tada::tada::tada::tada::clap::clap:
    <br>
    <br>
    Base project made with much :heart:. Contains CRUD, patterns, generated library, and much more!
    <br>
    <br>
    <img src="https://github.com/Casperoazanda/gif/blob/main/4.gif" alt="Demo example"/>
    <br>
    <br>
  </p>
</p>

## Table of contents

- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Creators](#creators)
- [Thanks](#thanks)
- [Copyright and license](#copyright-and-license)
<!-- - [Quick start](#quick-start) -->

## What's included

- [x] Developed chatting mobile application with SpringBoot, Netty, Websocket,FastDFS, Nginx, MyBatis, and MySQL
- [x] -Registered different Interceptors into Channel through pipelines and set up the Netty server.
- [x] Implemented communication over single TCP connection with Websocket to realize realtime chatting.
- [x] Generated Mybatis to determine the mapping rules of SQL through configuration and store chunk data into MySQL.
- [x] -Collaborated Nginx with FDFS to optimize large volume file storage.


### MySQL

This repo is using MySQL. We use MySQL to handle CRUD operations over
the messages and to store media files.

<!-- ## Quick start -->

<!-- **WARNING** -->

<!-- > Verify that you are running node 12.4.0 by running node -v in a terminal/console window. Older
> versions produce errors, but newer versions are fine.

```bash
npm i
npm start
```

| Tasks                      | Description                                                                                          |
| -------------------------- | ---------------------------------------------------------------------------------------------------- |
| npm start                  | Start the app in development mode with the english language only                                     |
| npm start:es               | Start the app in development mode with the spanish language only                                     |
| dev:ssr                    | Start the server like SSR                                                                            |
| extract-i18n               | Extract all messages from templates and ts files and update the language files with new translations |
| npm run lint               | Run the linter (tslint)                                                                              |
| npm run test               | Run all unit tests with karma and jasmine                                                            |
| npm run test:app:watch     | Run app unit tests and wait for changes                                                              |
| npm run test:library:watch | Run library unit tests and wait for changes                                                          |
| npm run e2e                | Run end to end tests with protractor                                                                 |
| npm run build:prod         | Build the app for production with english translations                                               |
| npm run build:prod:es      | Build the app for production with spanish translations                                               |
| npm run builds:prod        | Builds both configurations                                                                           |
| npm run build:ssr:prod     | Builds the server with universal in SSR mode                                                         |
| npm run serve:ssr          | Start the node server for angular universal                                                          |
| npm run build:library      | Build the library                                                                                    |
| npm run bundle-report      | Build and run webpack-bundle-analyzer over stats json                                                |
| npm run release:minor      | Create a new minor release using standard-version                                                    |
| npm run release:major      | Create a new major release using standard-version                                                    |
| npm run ci                 | Execute linter, tests and production builds 
-->                                                      
## Bugs and feature requests

Have a bug or a feature request? Please first read the
[issue guidelines](https://github.com/Casperoazanda/ChatterBox/blob/master/CONTRIBUTING.md)
and search for existing and closed issues. If your problem or idea is not addressed yet,
[please open a new issue](https://github.com/Casperoazanda/ChatterBox/issues/new). 

## Creators

**Azanda Lyu**

- <https://github.com/Casperoazanda>

## Thanks

Thanks to all contributors and their support.

If you have an idea or you want to do something, tell me or just do it! I'm always happy to hear
your feedback!

## Copyright and license

Code and documentation copyright 2020 the authors. Code released under the
[MIT License](https://github.com/Ismaestro/angular9-example-app/blob/master/LICENSE).
