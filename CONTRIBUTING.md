# Contributing

## Guidelines for hack articles
* Include a "Last updated" datestamp. This allows future readers to determine what browsers and versions were current at the time the article was last updated, and therefore what additional later browsers or versions they will need to test themselves.
* Include a live testcase.
* Include an explanation (or at least give your theory/conjecture) for how the hack works.
* Test results **must** include screenshots. Whenever possible, include the browser's "About" or "Version" screen in the screenshot to clarify the exact version number that you tested. An exception is made for mobile browsers, where it's usually impossible to display both the "About" screen and the webpage simultaneously in a single screenshot; also, on mobile, the browser is often not versioned separately from the OS, so the OS version will be more useful/relevant.
* Unless no current browser versions are affected by the hack (i.e. unless it's completely in the past), **don't** attempt to summarize the browser versions affected by the hack (e.g. "Firefox 20+", "IE10-11"). These summaries have a tendency to become outdated/ambiguous/inaccurate when new browser versions are released that unexpectedly fix or unexpectedly leave broken the CSS bug(s) that hacks rely on. It's simple enough for readers to glean the same information themselves by reading the compatibility table, without any ambiguity or inaccuracy.
* If you aren't sure or are unable to test exactly how far back a hack goes, then include an entry with status "Unknown" for the version prior to the lowest version that you did test. This helps clarify the situation to readers.
* Unless a browser has reached end-of-life, include an entry with status "Unknown" for the next, as-yet-unreleased stable version of the browser. Again, this clarifies to the reader which versions have and haven't been tested.
* Even if a hack is presumed to not apply at all to a particular browser, you are encouraged to test against at least 1 "ancient" version of the browser, if possible, in case it did suffer from the hack's bug in the distant past.

## Licensing
By contributing to this project/repository, you agree to dual-license your contribution under the disjunction of [the MIT License](https://github.com/browser-bugs/browser-bugs.github.io/blob/gh-pages/LICENSE-MIT.txt) and the [Creative Commons Attribution 4.0 International Public License](https://github.com/browser-bugs/browser-bugs.github.io/blob/gh-pages/LICENSE-CC-BY.txt).
