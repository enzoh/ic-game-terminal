# IC Game Terminal

Graphics output and keyboard input terminal for the Internet Computer.

For playing games, viewing graphics and more.


## Building and testing


### Use `dfx` and `vessel` to build and run the test canister

In one terminal:

```
dfx start
```

In another terminal:

```
dfx build
dfx canister install --all
```

Use the canister ID printed back on the terminal to connect `icgt`


### Use `cargo` to build and run the `icgt` tool

```
cargo run -- connect ic:06AB8F2EB9EB6699D6
```


