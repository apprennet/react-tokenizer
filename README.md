# What is this?

A React.js component that parses user input in a ContentEditable element and
displays them as individual tokens.

Example use cases include:
- Entering a list of email addresses
- Tagging

## To run the example

Run `npm install` followed by `gulp webserver`. Open your browser and visit
`http://localhost:8080`.

Note that Jest tests are breaking on Node v0.12.0 and IO.js v1.5.0

## TODO

- Cross browser compatibility
- Typing in between tokens
- Remove tokens other than the last token
- Handle paste events
- Better test suite
