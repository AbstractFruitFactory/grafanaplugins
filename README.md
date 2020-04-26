# Grafana plugins

Grafana plugins can be built using either React or Angular, two popular front-end javascript frameworks.

It is highly recommended to use React for Grafana 6+.

[Typescript](https://www.typescriptlang.org/ "Typescript") should also be used, which is a javascript transpiler for building type-checked and maintainable code. 

Example grafana plugin: https://github.com/grafana/clock-panel


# General NodeJS development

NodeJS projects use either [NPM](https://www.npmjs.com/ "NPM") or [Yarn](https://yarnpkg.com/ "Yarn") for managing the project and mainly its dependencies. It does not matter much which one is used.

Any open source project should have a README.md file (like this one), which describes how to install/run/build/use the project. See the example grafana plugin. Projects usually also have a CHANGELOG.md file, like [this](https://github.com/grafana/clock-panel/blob/master/CHANGELOG.md "this") one.

Files should have unit tests, which can be written using any testing framework. A popular one is [Mocha](https://mochajs.org/ "Mocha").


