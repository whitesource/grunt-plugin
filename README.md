# whitesource

> whitesource grunt plugin

## Getting Started
This plugin requires Grunt.

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install whitesrc --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('whitesrc');
```

## The "whitesource" task

### Overview
In your project's Gruntfile, add a section named `whitesource` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  whitesrc: {
    options: {
          'apiKey':'',
          'https':'',
          'baseURL':'',
          'port' :'',
          'productName':'',
          'productVersion':'',
          'productToken':'',
          'projectName':'',
          'projectVer':'',
          'projectToken':''
    },
    your_target: {
      // Target-specific file lists and/or options go here.
    },
  },
})
```


### Usage Examples

#### Default Options
In this example, the default options are used to do something with whatever. So if the `testing` file has the content `Testing` and the `123` file had the content `1 2 3`, the generated result would be `Testing, 1 2 3.`

```js
grunt.initConfig({
  whitesrc: {
    options: {
      'apiKey':'AAA-BBB-CCC-DDD',
    }
  },
})
```

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
_(Nothing yet)_

## License
Copyright (c) 2015 Doron Gour. 
License Apache-2.0. (http://www.apache.org/licenses/LICENSE-2.0.html)
