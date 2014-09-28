# Emote server

A [Sails](http://sailsjs.org) application. Simple CRUD operations for emoticons.

Please see the independent [reddit_emote_scraper](reddit_emote_scraper) sub-application for scraping emotes from Reddit.

The emote server is designed to import the results from the reddit_emote_scraper and acts as a complete replacement to using reddit as a emoticon hosting site.

## Motivation

Reddit is not designed as a emote hosting site and never will be. There are limitations set on images (no .gif or .svg's allowed) and a limit amount of emoticons per subreddit. Adding emotes can be unnecessary complicated and error-prone. And there is no ability to tag or search emoticons.

Also, it can be considered rude to use someone's CDN for something it was never intended for.

This server has most of the expected operations you may expect from a CRUD application. There are forms for submitting and editing and there is a JSON api for searching.

The server will not be a replacement for grading emoticons for submission, nor will this project contain any material to consume the emoticons.

## Running

The subproject reddit_emote_scraper must be run at least once to fill the `reddit_emote_scraper/output` directory. Please see the subdirectory for running this script.

To download all requirements for the emote server, do `npm install`. To run the server do `npm start`.
