# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.0] - 2020-10-14

### Added
-   Support for `int64` (#9)
-   Support for registering `void` methods (#8)

### Changed
-   Differ between empty lists and calls with no params (#12)
-   Enable and fix compiler warnings (#11)

### Fixed
-   Remove `#include "common.h"` inside `"common.h"`
-   Allow strings as error object


## [0.1.0] - 2019-07-02

### Added
-   Initial implementation of 1.0 and 2.0 server
-   Initial implementation of 1.0 and 2.0 client
-   Test suite for server and client
-   Example Application with HTTP client and server connectors
