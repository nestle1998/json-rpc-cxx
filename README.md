**THIS IS A WORK IN PROGRESS PROJECT**

#json-rpc-cxx
![json-rpc-cxx-icon](doc/icon.png)

A [JSON-RPC](https://www.jsonrpc.org/) (1.0 & 2.0) framework implemented in C++17 using the [nlohmann's json for modern C++](https://github.com/nlohmann/json).

- JSON-RPC 1.0 and 2.0 compliant client
- JSON-RCP 1.0 and 2.0 compliant server
- Transport agnostic interfaces
- Compile time type mapping (using [nlohmann's arbitrary type conversion](https://github.com/nlohmann/json#arbitrary-types-conversions))
- Runtime type checking
- Cross-platform (Windows, Linux, OSX)

## Usage
TBD

### Installation
TBD, probably vcpkg and header only
### Examples
Examples can be found in [src/examples](src/examples)

## Design goals
- Easy to use interface
- Type safety where possible
- Avoid errors at compile time where possible
- Test driven development
- Choose expressiveness over speed
- Minimal dependencies

## License
This framework is licensed under [MIT](LICENSE).

### Dependencies
- [nlohmann's JSON for modern C++](https://github.com/nlohmann/json) is licensed under MIT.
- [Catch](https://github.com/catchorg/Catch2) is licensed under BSL-1.0.

## Developer information
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CHANGELOG.md](CHANGELOG.md)