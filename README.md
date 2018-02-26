# dynomite [![Build Status](https://travis-ci.org/softprops/dynomite.svg?branch=master)](https://travis-ci.org/softprops/dynomite) [![Coverage Status](https://coveralls.io/repos/softprops/dynomite/badge.svg?branch=master&service=github)](https://coveralls.io/github/softprops/dynomite?branch=master) [![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE) [![crates.io](http://meritbadge.herokuapp.com/dynomite)](https://crates.io/crates/dynomite) [![Released API docs](https://docs.rs/dynomite/badge.svg)](http://docs.rs/dynomite)
[![Master API docs](https://img.shields.io/badge/docs-master-green.svg)](https://softprops.github.io/dynomite)

> dynomite makes rusoto_dynamodb fit your types (and visa versa)

## [API Documentation](https://softprops.github.io/dynomite)

## Install

In your Cargo.toml file, add the following under the `[dependencies]` heading

```toml
dynomite = "0.0.0"
```

Optionally, you can install a companion crate which allows you to derive
dynomite types for your structs at compile time

```toml
dynomite-derive = "0.0.0"
```

Doug Tangren (softprops) 2018