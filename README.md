"These are not the droids you are looking for."

This repo is simply a "test fixture" for github-export.
github-export is a library to assist in exporting items from github.

Yes, I know they have an [api](http://developer.github.com/v3/).  Think of github-export as a helpful wrapper for that.

We created this ensure our tests work against an actual repo.
We are minimizing access to this repo via [vcr](https://github.com/myronmarston/vcr).
