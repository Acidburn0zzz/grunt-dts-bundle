# grunt-dts-bundle

> Grunt [plugin](http://gruntjs.com/) to export TypeScript .d.ts files as an external module definition with [dts-bundle](https://github.com/grunt-ts/dts-bundle)

[![Build Status](https://secure.travis-ci.org/grunt-ts/grunt-dts-bundle.png?branch=master)](http://travis-ci.org/grunt-ts/grunt-dts-bundle) [![Dependency Status](https://gemnasium.com/grunt-ts/grunt-dts-bundle.png)](https://gemnasium.com/grunt-ts/grunt-dts-bundle) [![NPM version](https://badge.fury.io/js/grunt-dts-bundle.png)](http://badge.fury.io/js/grunt-dts-bundle)

Wraps [dts-bundle](https://github.com/grunt-ts/dts-bundle)

## Getting Started
This plugin requires Grunt `~0.4.1`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
$ npm install grunt-dts-bundle --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-dts-bundle');
```

## The "grunt-dts-bundle" task

### Default Options

All options are passed directly to [dts-bundle](https://github.com/grunt-ts/dts-bundle)

```js
grunt.initConfig({
	dts_bundle: {
		build: {
			options: {
				name: 'my-project',
				main: 'build/index.d.ts'
			}
		}
	}
});
```

## History

* 0.1.0 - First release

## Contributing

Contributions are very welcome, please create an Issue before doing something major.

In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).
