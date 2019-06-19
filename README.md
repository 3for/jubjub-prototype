# jubjub-prototype

This is a research project being built for [Zcash](https://z.cash/).

## Running

Using Rust's nightly compiler:

```
cargo run --release --bin bench_50
```

Using ARM or can't use Rust's nightly compiler? Pass `--no-default-features`.

```
cargo run --release --no-default-features --bin bench_50
```

## Performance
Running in virtual machine:

```
Creating random generators for the Pedersen hash...
Done!
Creating the parameters and saving them to `./params`
Just wrote the parameters to disk! We don't need to do it next time.
Creating 50 proofs and averaging the time spent creating them.
average proving time: 56.937373766s
```

## License

Licensed under either of

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in the work by you, as defined in the Apache-2.0
license, shall be dual licensed as above, without any additional terms or
conditions.
