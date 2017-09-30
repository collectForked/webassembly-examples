## webassembly-examples

A small collection of examples on [webassembly](http://webassembly.org/).

## Usage

For 1 - 8:

```sh
# start
node ./#-path-to-example/index.js

# rebuild
cd #-path-to-example && wast2js script-name.wat -o script-name.js
```

For 9+ see readme.

##### Ordered list of examples

* [simple function](%231-simple-function)
* [variables](%232-variables)
* [conditions](%233-conditions)
* [memory](%234-memory)
* [loop](%235-loop)
* [block, br, br_if and labels](%236-crc32)
* [call_indirect](%237-call-indirect)
* [shared library](%238-shared-library)
* [simple native function](%239-native-build)
* [emscripten](%2310-emscripten)
* [emscripten (synchronous initialization)](%2313-emscripten-synс-require)
* [webassembly (npm module)](%2311-webassembly)
* [data structures](%2312-data-structures)
* [browser](%2314-browser)
* [working with webpack](%2315-webpack)

### License

MIT, 2017+ Dmitriy Tsvettsikh
