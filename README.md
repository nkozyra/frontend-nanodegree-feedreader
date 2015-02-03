# RSS Feedreader Testing

This application is a simple RSS feedreader that comes equipped with some pre-packaged tests.  To run the tests, find or modify the following Jasmine tests in /jasmine/spec/feedreader.js:

* describe('RSS Feeds') -> tests that feeds exist, are loaded, have names and have items
* describe('The menu') -> tests that the menu renders properly and responds to clicks
* describe('Initial Entries') -> tests that there is at least one entry on load
* describe('New Feed Selection') -> tests that new content is loaded with new feed

Additional tests should be added here per the Jasmine BDD spec: http://jasmine.github.io/
