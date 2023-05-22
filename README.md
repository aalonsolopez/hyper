# [hyper](https://hyper.rs) for WebAssembly: hyper_wasi

A **fast** and **correct** HTTP implementation for Rust. 
This is a fork from the original [hyper](https://github.com/hyperium/hyper) with support for WebAssembly compilation target.
That allows hyper client and server apps to run inside the [WasmEdge Runtime](https://github.com/WasmEdge/WasmEdge#readme) as a lightweight and secure alternative to natively compiled apps in Linux container.

For more details and usage examples, please see the upstream [hyper](https://github.com/hyperium/hyper) source and [these examples](https://github.com/WasmEdge/wasmedge_hyper_demo).

Note: We do not yet support SSL / TLS connections in hyper_wasi yet.


- HTTP/1 and HTTP/2
- Asynchronous design
- Leading in performance
- Tested and **correct**
- Extensive production use
- Client and Server APIs

**Get started** by looking over the [guides](https://hyper.rs/guides/1/).

## "Low-level"

hyper is a relatively low-level library, meant to be a building block for
libraries and applications.

If you are looking for a convenient HTTP client, then you may wish to consider
[reqwest](https://github.com/seanmonstar/reqwest).
If you are not sure what HTTP server to choose, then you may want to consider [axum](https://github.com/tokio-rs/axum) or [warp](https://github.com/seanmonstar/warp), the latter taking a more functional approach.
Both are built on top of this library.

## Contributing

To get involved, take a look at [CONTRIBUTING](CONTRIBUTING.md).

## License

hyper is provided under the MIT license. See [LICENSE](LICENSE).

