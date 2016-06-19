# This Repo is Deprecated

But don't fret! It turns out exporting/importing workflows from Alfred works a whole lot better than managing this in git. Download the latest version of Alfred Workflow [here](https://github.com/jsteiner/trelfred/releases).

# Trelfred Workflow

A Trello Workflow for Alfred

Uses the [trelfred script] to cache and search Trello boards.

[trelfred script]: https://github.com/jsteiner/trelfred

![Trelfred demo](https://cloud.githubusercontent.com/assets/466493/14092917/223ea38e-f518-11e5-9ced-0ef55bb2cad9.gif)

## Features

* Caches boards for instant search.
* Fuzzy search for easy searching.
* Stores board hits and sorts appropriately for even faster searching.

## Install

1. Clone this repo and symlink it in your Alfred workflows directory.
1. Create a `.env` file in this repo with the following structure:

   ```
   TRELLO_USERNAME=your-username
   TRELLO_API_KEY=your-key
   TRELLO_API_TOKEN=your-token
   ```

1. Get your [Trello developer key] and add it to your `.env`.
1. Get your Trello token from the following URL and add it to your `.env`.
   Be sure to **replace the developer key** in the URL:

    https://trello.com/1/authorize?key=REPLACE_WITH_YOUR_DEVELOPER_KEY&name=Trelfred&expiration=never&response_type=token

[Trello developer key]: https://trello.com/1/appKey/generate
