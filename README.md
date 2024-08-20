# Alfred-workflow-Firefox-basic-Google-search
Use Firefox to search Google excluding AI results with option to use verbatim search

# Introduction

The purpose of this workflow is to allow a search of Google which excludes from the results Google AI generated results. In the workflow configuration you can also choose whether or not to exclude from the search Amazon, eBay and/or YouTube.

You can optionally specify a verbatim search (which makes Google use your exact search inputs instead of fuzzy searching everything).

The search results will open in a Firefox private window.

# Usage

Select in the configuration which Google domain you wish to use for your searches (the default is https://google.com but https://google.co.uk is provided as an alternative). Choose which listed domains (if any) you wish to exclude from the search.

Either:

1. Type the keyword (the default is `goo`) followed by a space and your search term then press <kbd>⏎</kbd>.

![Firefox search basic Google](Images/Search.png)

Or:

2. Select some text, press your Universal Actions hotkey, start typing "Firefox", select from the list of results `Firefox basic Google search`then press <kbd>⏎</kbd>.

![Firefox basic Google search](Images/UA.png)

The search results open in a new Firefox private tab.

For a verbatim search in either case press <kbd>⌥</kbd><kbd>⏎</kbd> instead of simply <kbd>⏎</kbd> and the modifier subtext willl change accordingly. For example:

![Firefox search basic Google](Images/VerbatimSearch.png)

The workflow ReadMe contains instructions for adding exclusions in addition to those for Amazon, eBay and YouTube.
