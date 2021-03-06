# Changelog

## Next

## 1.2.4
#### Bug fix
* `yagg cli`
  * fix list, not choosing a template error

## 1.2.1
#### Bug fix
* `yagg core & yagg cli`
  * add missing file

## 1.2.0
#### Enhancement
* `yagg cli`
  * Update command names and docs
  * new project using current directory
  * choose a template from the list command
#### Bug fix
* `yagg core`
  * fix install dependencies
#### Internal
* `yagg core & yagg cli`
  * add git pre-commit hook
  * add prettier-eslint
## 1.1.0
#### Enhancement
* `yagg core`
  * able to install dependencies & devDependencies

## 1.0.0
#### Enhancement
* `yagg cli`
  * add option -p to run command, to specify a path of your template
* `yagg core`
  * change how to write a template
  * ask questions feature

## 0.5.6 (2017-08-15)
#### Enhancement
* `yagg cli`
  * add -v option to display version
* `yagg core`
  * friendly error reponse
  * debug flags
#### Internal
* `yagg cli & core`
  * lint code
  * add travis ci
  * refactor

## 0.5.5 (2017-08-14)
#### Internal
* `yagg core`
  * refactor utils

## 0.5.3 (2017-08-14)
#### Bug fix
* `yagg core`
  * check if file is an image

## 0.5.1 (2017-08-14)
#### Internal
* `yagg cli`
  * refactor run command
  * add message to list command

## 0.5.0 (2017-08-13)
#### Enhancement
* `yagg cli`
  * new feature install dependencies
#### Internal
* `yagg core`
  * Refactor, move getDeps to utils
  * remove envInfo
  * update Error codes
  * add test for install deps

## 0.4.1 to 0.4.4 (2017-08-13)
#### Bug fix
* `yagg cli`
  * fix typo
  * dumn fix
  * add package.json to files
  * fix typo, removed trailing coma

## 0.4.0 (2017-08-13)
#### Enhancement
* `yagg cli`
  * you can now add a custom generator from cli
  * you can now remove a custom generator from cli

## 0.3.0 (2017-08-13)
 - add cli

## 0.1.0 (2017-08-13)
 - can declare variables in files to be replaced #{token}
 - created node module to handle tree cloning
 - created bash script
