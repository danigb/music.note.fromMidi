# music.note.fromMidi

[![Build Status](https://travis-ci.org/danigb/music.note.fromMidi.svg?branch=master)](https://travis-ci.org/danigb/music.note.fromMidi)
[![Test Coverage](https://codeclimate.com/github/danigb/music.note.fromMidi/badges/coverage.svg)](https://codeclimate.com/github/danigb/music.note.fromMidi/coverage)
[![Climate](https://codeclimate.com/github/danigb/music.note.fromMidi/badges/gpa.svg)](https://codeclimate.com/github/danigb/music.note.fromMidi)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
[![npm version](https://img.shields.io/npm/v/music.note.from-midi.svg)](https://www.npmjs.com/package/music.note.from-midi)
[![license](https://img.shields.io/npm/l/music.note.from-midi.svg)](https://www.npmjs.com/package/music.note.from-midi)
[![music.kit](https://img.shields.io/badge/music-kit-yellow.svg)](https://www.npmjs.com/package/music.kit)

`music.note.fromMidi` is a tiny function (231 bytes minified) to get the note name from a midi number (using [MIDI Tuning Standard](https://en.wikipedia.org/wiki/MIDI_Tuning_Standard) where 'A4' is midi number 69):

```js
var fromMidi = require('music.note.from-midi')
fromMidi('69') // => 'A4'
fromMidi('36') // => 'C2'
```

This is part of [music.kit](https://github.com/danigb/music.kit)

## Installation

Install via npm: `npm install --save music.note.from-midi` and require it.

## Documentation

[Generated documentation here](https://github.com/danigb/music.note.fromMidi/blob/master/API.md)

## License

MIT License
