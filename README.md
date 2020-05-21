# urlbar-richsuggestion-tester
Installs an experimental search engine in Firefox for testing purposes.

## Installation
1. Install Firefox Nightly, version 78 or greater.
2. Build the add-on with `web-ext build` or download the .zip from the GitHub Releases page.
3. In about:debugging, go to This Nightly in the sidebar. Click `Load Temporary Add-on...` and load the add-on's .zip file.
4. Accept the prompt to make `Google (firefox-dev)` your default search engine. Alternatively, you can deny the prompt and set it as your search engine in `about:preferences#search`.
5. In `about:config`, search for `"browser.urlbar.richsuggestions"` and enable the prefs for whichever search features you're interested in.
6. Search! Highlighted suggestions should read `Search with Google (firefox-dev)`.