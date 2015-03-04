# Documark Debug

[![npm version](https://badge.fury.io/js/dmp-debug.svg)](http://badge.fury.io/js/dmp-debug)
[![dependency status](https://david-dm.org/mauvm/dmp-debug.svg)](https://david-dm.org/mauvm)

> Documark plugin for debugging the build process.

Uses the [`documark-cache`][documark-cache] plugin.

## Usage

1. Add plugin to document configuration and set `debug: true`:

	```yaml
	plugins:
	  - dmp-debug
	debug: true
	```

This creates the `document.html` and `config.json` files in the [cache directory][documark-cache] (`.documark/`).

[documark-cache]: https://www.npmjs.com/package/documark-cache
