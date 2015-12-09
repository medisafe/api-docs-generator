# api-docs-generator
API docs generator written in Go, and it's simple

The generator, takes `api.json` that was created by you with all endpoints definitions and creates the final html page.

#### Clone and run
`go run generator.go api-example/`

Sample [`api.json`](https://github.com/Medisafe/api-docs-generator/blob/master/api-example/api.json)<br>
Output looks like this:
[Demo](http://medisafe.github.io/api-docs-generator/)

#### Generator options

- $1 - source of `api.json` (required)
- $2 - destination to copy the `api.json` (optional)

[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/Medisafe/api-docs-generator)
