![Seneca](http://senecajs.org/files/assets/seneca-logo.png)
> A [Seneca.js][] plugin

# @seneca/browser

| ![Voxgig](https://www.voxgig.com/res/img/vgt01r.png) | This open source module is sponsored and supported by [Voxgig](https://www.voxgig.com). |
|---|---|

## Install

```sh
npm install seneca-browser
```

## Quick Example

```js
var seneca = Seneca()
seneca.use('browser')
```

## More Examples

See [test/](test/) for usage examples.

## Motivation

Allows Seneca to run in the browser, enabling microservice communication via WebSockets.

## Support

If you're using this module and need help, you can:

- Post a [github issue][]
- Tweet to [@senecajs][]

## API

* Builds against Seneca p4.0.0 - fix adjustments when Seneca 4.x is out
* Use yarn to avoid npm peer dep issue

## Contributing

The [Senecajs org][] encourages open participation. If you feel you can help in any way, be it with documentation, examples, extra testing, or new features please get in touch.

### Running tests

```sh
npm run test
```

## Background

Experimental plugin for browser-side Seneca usage.


