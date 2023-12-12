# Node & Express Bug Hunt!

**READ ALL INSTRUCTIONS BEFORE STARTING**

There are 10 bugs in total, can you find them all? There are hints throughout (???), you should only need to make minor modifcations to 10 lines of code.

**Don't race through the files looking for the issues!** They should all have a console log or error that help you identify them. Read the console so that you know what error will cause each bug. The last one is tricky since it doesn't throw any errors. Document the error, line number and your fix in this README for each of the bugs.

## Setup
```
npm install
npm start
```

> NOTE: A couple of bugs prevent the server from starting.

## Error List

TODO: Add the error here followed by the line of code you fixed.

### Bug 0

`ReferenceError: app is not defined`

Fixed `quote.router.js` line 28: switch `app` to `router`. _This is the solution to the first bug._

### Bug 1
Server JS line 7 changed port to 5001 as per the comments
### Bug 2
event.preventDefault() added to index.html form
### Bug 3
added module.exports = router; to quote.router.js
### Bug 4
changed location of res.send
### Bug 5
//changed from {} to []
let quoteList = [];
### Bug 6
// changed to listen on /quotes
// router.post '/quotes'
### Bug 7
 //changed to quoteList from quote(s)List
    quoteList.push(quoteToAdd);
### Bug 8
 <!-- Stylesheet added /--> to HTML
### Bug 9

### Bug 10

### Bug 11?
https://fonts.google.com/specimen/Roboto instead of the incorrect URL in index.html
...

## Extra Practice (Optional)

Complete the JS debugging exercises at:

- https://education.launchcode.org/intro-to-professional-web-dev/chapters/errors-and-debugging/exercises.html
