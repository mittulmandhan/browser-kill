# browser-kill

[![Build](https://img.shields.io/travis/com/arshadkazmi42/browser-kill.svg)](https://travis-ci.com/arshadkazmi42/browser-kill/)

Kill browser process in Mac, Linux, Windows

## Install

```
npm i browser-kill
```

## Usage

```javascript

const Brkill = require('browser-kill');

(async () => {

  // Kills chrome process
  await Brkill.chrome();

  // Kills firefox process
  await Brkill.firefox();
})

```

## API

- ##### `chrome()`
  - Kills the chrome process, throws error if chrome process is not running

- ##### `firefox()`
  - Kills the chrome process, throws error if chrome process is not running

## Contributing

Interested in contributing to this project?
You can log any issues or suggestion related to this library [here](https://github.com/arshadkazmi42/browser-kill/issues/new)

Read our contributing [guide](CONTRIBUTING.md) on getting started with contributing to the codebase

## Contributors

Thank you to all the contributors who have helped us in making this project better :raised_hands:

<a href="https://github.com/arshadkazmi42"><img src="https://github.com/arshadkazmi42.png" width="30" /></a>
