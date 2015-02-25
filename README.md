# Documark Debug

Documark plugin for debugging the build process.

Uses the [`documark-cache`][documark-cache] plugin.

### Usage

1. Add plugin to document configuration and set `debug: true`:

	```yaml
	plugins:
	  - documark-debug
	debug: true
	```

This creates the `document.html` and `config.json` files in the [cache directory][documark-cache] (`.documark/`).

[documark-cache]: https://www.npmjs.com/package/documark-cache
