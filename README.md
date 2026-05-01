# Search-Hit-Hider

Search-Hit-Hider is a userscript for hiding unwanted domains from targeted search result pages.

## Install

Install the userscript from the raw GitHub URL:

https://raw.githubusercontent.com/Istiaq-Edu/Search-Hit-Hider/main/search-hit-hider.user.js

## Targeted search engines

Search result layouts change frequently, so each target should be tested periodically.

### Explicit engine handling

The userscript has explicit engine detection and/or dedicated handling for:

- Google, including Google Images and Google News result layouts
- Bing
- DuckDuckGo
- Startpage
- Yahoo
- Baidu
- Yandex
- Ecosia

### Generic or partial handling

The userscript also includes match rules and generic selectors for:

- Yahoo Japan
- Searx
- Qwant / Qwant Junior

These may work when their current markup matches the script selectors, but they should be treated as less certain until tested.

## Features

- Block domains directly from search result pages
- Use regular blocked results or Perma-ban mode
- Manage blocked and Perma-ban domain lists
- Import, export, sort, and de-duplicate block lists
- Customize button captions and style rules

## Repository

Project home: https://github.com/Istiaq-Edu/Search-Hit-Hider

Issues: https://github.com/Istiaq-Edu/Search-Hit-Hider/issues

## Credits

Search-Hit-Hider is a continuing improvement based on the original Google Hit Hider by Domain userscript published on Greasy Fork:

https://greasyfork.org/en/scripts/1682-google-hit-hider-by-domain-search-filter-block-sites

Credit and thanks to the original author for the foundation this project builds on.

## License

BSD-3-Clause. Required upstream copyright/license notices are retained in the userscript source.
