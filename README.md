# dtn7-rs
Rust implementation of DTN7 Bundle Protocol draft https://tools.ietf.org/html/draft-ietf-dtn-bpbis-12

Plus the Simple TCP Convergency Layer Protocol https://tools.ietf.org/html/draft-burleigh-dtn-stcp-00

This is more or less a port of the dtn7 golang implementation: https://github.com/geistesk/dtn7


Currently a very basic service discovery, STCP (receive only) and a rest command interface are implemented.
**Beware, the API is not very idiomatic rust and lacks documentation and tests.**
Since I consider this code to be very unpolished and far from finished it is also not yet published on crates.io.