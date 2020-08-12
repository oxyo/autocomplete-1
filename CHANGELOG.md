# Change Log

All notable changes to this project will be documented in this file.

## 2020-08-12
### Added
- Use Promises instead of async/await to avoid @babel/runtime
- adding a new 'onSearch' function where you can decide for yourself how the data will be downloaded [jquery, axios, fetch, ...]
- aria-describedby -> [attribute](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-describedby_attribute)
- new API for testing -> [breakingbadapi](https://breakingbadapi.com/documentation)

### Changed
- reducing library size by removing babel-runtime
- remove noResult (temporarily?)
- remove prettier
- update changelog
- update dependencies
- update readme
- update eslintrc
- update webpack.config.js

## 2020-08-04
### Added
- changelog
- noResult
- accessible for ARIA attributes and keyboard interactions

### Changed
- fix the 'x' button is not hidden fixed
- fix no reset of settings
- update dependencies
- update readme
- update webpack.config.js

## 2020-08-01
### Changed
- update dependencies
- update example wikipedia

## 2020-06-22
### Changed
- fix: many spaces

## 2020-06-20
### Changed
- simplification of configuration

## 2020-06-19
### Added
- improved sorting

## 2020-06-18
### Changed
- update example

## 2020-05-21
### Added
- Button 'x' removes text from the input field
- improving the position of the 'x' button

### Changed
- update devDependencies

## 2020-05-10
### Added
- adding the option of choosing a search method

## 2020-05-09
### Added
- improve bundle size

## 2019-12-06
### Added
- adding BundleAnalyzerPlugin

### Changed
- removal @babel/polyfill

## 2019-11-07
### Added
- adding the ability to download data locally/API

### Changed
- correction of errors with the number of characters
- update devDependencies

## 2019-06-29
### Changed
- upgrade to core-js 3

## 2019-06-07
### Added
- adding license
- the appearance of the error


## 2019-05-27
### Changed
- update dependencies
- changing libraryTarget to umd

## 2019-05-14
### Changed
- fixing issue with fast typing
- a small change that improves the look

## 2019-05-07
### Added
- adding license
- the appearance of the error

### Changed
- fixing a problem with several elements of inputs
- changing class name

## 2019-05-06
### Added
- specific output template

### Changed
- fixed IE10/11
- update specificOutput compatible IE10/11

## 2019-05-05
### Added
- remove special characters from input
- searchBy - searching by element

## 2019-05-04
### Added
- eslint and prettier adding
- source-map dev/prod