# FUCKING MAGNETS HOW DO THEY WORK?

This project is designed to be a modular image grabber/crawler written in node.js.

It's main purpose is derived from this XKCD quote:

> With the collapse of the dollar the government has endorsed an alternate currency.
> Your monetary worth is now determined by the number of funny pictures saved to your hard drive.

[Quote from XKCD](http://xkcd.com/512/)

The name was borrowed from [the 'fucking magnets' meme](http://knowyourmeme.com/memes/f-cking-magnets-how-do-they-work).


## FEATURES

- download all the funny pictures on the internet directly to your hard disk
- extensible plugin facility with multi-module support
- modules for high-quality funny pics 
    - icanhascheezburger-network like failblog and lolcats
    - soup.io
    - kqe 
    - bildschirmarbeiter
    - ... more
- FUNNY PICTURES ALL THE WAY

## Dependencies

For managing dependencies we recommend [NPM >= 1.0](http://npmjs.org):

    npm install . #inside your magnets directory

## Usage

TODO: ADD THIS!

## TODO:

  * Live Ticker (scheduler) - partly implemented
  * Other Plugins (recently added cheezburger network)
  * Add debugging and inspection howto
  * Support commandline options like loglevel  (partly implemented)
  * Use node-htmlparser instead of own regex (used in cheezburger as first plugin)
  * meta data for every picture


