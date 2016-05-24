Rdcli
===

[![npm version](https://badge.fury.io/js/rdcli.svg)](https://badge.fury.io/js/rdcli)
[![Build Status](https://travis-ci.org/jcherqui/rdcli.svg?branch=master)](https://travis-ci.org/jcherqui/rdcli/)
[![npm download](https://img.shields.io/npm/dt/rdcli.svg)](https://www.npmjs.com/package/rdcli)

> A simple CLI tool to unrestrict links with real-debrid.com

Download links, magnets and torrent files.

[![asciicast](https://asciinema.org/a/7cv523xguuby2rgpwjw7drlug.png)](https://asciinema.org/a/7cv523xguuby2rgpwjw7drlug)

## Installation

`npm i -g rdcli`

## Usage

`rdcli <url|magnet|torrent>`

### Download DDL file

`rdcli http://uptobox.com/1gdncohxbqkp`

### Download magnet file

`rdcli magnet:?xt=urn:btih:33130de5c14a8bb5410746ee5a9604cdfb9538ef`

### Download torrent file

`rdcli Back.to.the.Future.Trilogy.1080p.BluRay.x264.torrent`

## Development

Install dependencies:

`make install`

Start project:

`make run`

# TODO

- [ ] Handle Ctrl+u and backspace in prompt password
- [x] Add [ora](https://www.npmjs.com/package/ora) spinner
- [ ] Update text errors
- [ ] Handle multi-link
- [x] Add asciinema

License
---

MIT

**Free Software, Hell Yeah!**
