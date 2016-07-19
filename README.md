Buildpack for [asset-matrix-go](https://github.com/jvatic/asset-matrix-go)
==========================================================================

(**NOTE:** This buildpack has only been tested with [Flynn](https://flynn.io).)

## Usage

- Ensure [asset-matrix-go](https://github.com/jvatic/asset-matrix-go) is vendored.
- Ensure you have a Go package that compiles to `bin/assets` (e.g. `assets/compile.go`) and invokes [asset-matrix-go](https://github.com/jvatic/asset-matrix-go).
- Ensure your project is configured to use the Go buildpack, then this buildpack.
