# Documark Debug

Documark plugin for debugging the build process.

Requires the [`documark-cache`](https://github.com/mauvm/documark-cache) plugin.

### Usage

1. Add plugin to document configuration and set `debug: true`:

	```yaml
	plugins:
	  - documark-debug
	debug: true
	```

This creates the `document.html` and `config.json` files in the Documark cache directory (`./.documark`).
