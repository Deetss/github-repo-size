# This is forked and updated to work with GitHub's new layout. It seems the original repo was dead and has not received any updates. Its last changes were made in 2021.
# A Firefox addon to display a Github repository's size

[![Mozilla Add-on](https://img.shields.io/amo/v/deetss-github-repo-size.svg?style=flat-square)][amo]

Add repository size to the Github's summary.

![Addon screenshot](art/screenshot.png)

**⚠ This addon use the size as returned by the GitHub API and may be
innacurate due to how GitHub stores git repositories!**

## Usage

Download the addon from **[addons.mozilla.org][amo]**

### Private Repositories

A **Personal Access Token** from an account with access to the private repository is
required for this addon to work. You can create a Personal Access Token
[here][ghsettings]. **Don't forget to check the `repo` scope.**

You can also show the dialog to save your token by clicking on the element added
by the addon on any repository, public or private, or you can visit the addon's
settings page.

## Building

- Use `npm run build` to build the Firefox webextension
- Use `npm run watch` to have an automated build on changes and `npm run webext:run` to test the addon

[amo]: https://addons.mozilla.org/firefox/addon/deetss-github-repo-size/
[ghsettings]: https://github.com/settings/tokens
