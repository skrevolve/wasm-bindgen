# Closure examples

This directory is an example of using the `#[wasm_bindgen]` macro with closures
to interact with the DOM.

You can build the example with:

```
$ ./build.sh
```

(or running the commands on Windows manually)

and then opening up `index.html` in a web browser should show a hello message on
the web page generated by the wasm.

For more information about this example be sure to check out
[`hello_world`][hello] which also has more comments about caveats and such.

[hello]: https://github.com/alexcrichton/wasm-bindgen/tree/master/examples/hello_world