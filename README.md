getscript-promise
===========

A Javascript Promise based library for fetching scripts asynchronously. To be used in client applications.

Using the Project
-----------------

  - `npm install getscript-promise`
  - `var getScript = require('getscript-promise')`

GetScript
-------------------
getScript returns a [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
  - `getScript(<script address>)`
  - returns a promise and appends script to document.

Example using await/async
-------------------
  - `await getScript('//www.googletagservices.com/tag/js/gpt.js')`

