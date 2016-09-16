# Feed Reader Testing using Jasmine

Tests were added in `jasmine/spec/feedreader.js` to test for functionality of the website.  The following tests are included:

- RSS feeds are defined in `allFeeds` and are not empty.
- Each feed in `allFeeds` has a defined and valid (simple RegExp) URL.
- Each feed has a defined and non-blank name.
- The navigation menu is hidden by default (on page load).
- The nav. menu toggles visibility after clicking the menu icon.
- The first feed has at least one entry.
- The feed changes content after selecting a new feed.


## To Run

Download/ Clone the repo, and open index.html in your browser locally. Jasmine libraries have already been
included. Test results are shown at the bottom of the page.