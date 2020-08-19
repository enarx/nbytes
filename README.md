[![Workflow Status](https://github.com/enarx/nbytes/workflows/test/badge.svg)](https://github.com/enarx/nbytes/actions?query=workflow%3A%22test%22)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/enarx/nbytes.svg)](https://isitmaintained.com/project/enarx/nbytes "Average time to resolve an issue")
[![Percentage of issues still open](https://isitmaintained.com/badge/open/enarx/nbytes.svg)](https://isitmaintained.com/project/enarx/nbytes "Percentage of issues still open")
![Maintenance](https://img.shields.io/badge/maintenance-activly--developed-brightgreen.svg)

# nbytes

Welcome to nbytes!

The `nbytes` crate exists to provide compile-time evaluation of various
unit conversions to bytes. For example:

```rust
use nbytes::bytes;

assert_eq!(bytes![2; KiB], 2048);
assert_eq!(bytes![2; kB], 2000);
```

License: Apache-2.0
