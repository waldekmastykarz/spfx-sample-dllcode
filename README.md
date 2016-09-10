# Building dll-code in SharePoint Framework

This sample illustrates how you can add custom tasks to the build process of SharePoint Framework projects.

## Minimal Path to Awesome

- clone this repo
- `$ npm i`
- `$ gulp update-greetings-typings`
- `$ gulp bundle`

## Features

This sample illustrates the following concepts on the SharePoint Framework:

- separating shared code from Web Parts into a Library
- building SharePoint Framework Library
- adding support for working with a SharePoint Framework Library both design- and runtime
- loading SharePoint Framework Library from an external URL
- using Gulp for defining additional build-automation tasks
- building ambient module definitions from code typings using a custom Gulp task
- building custom Gulp pipe function for processing file contents
- combining multiple file streams into one using Gulp
- building watcher task using Gulp to automatically execute tasks on file changes