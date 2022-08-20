 An example project building a Rust crate targetting wasm32-unknown-unknown with Nix

 Companion blog post: https://www.tomhoule.com/building-rust-wasm-with-nix-flakes/

 ```
 $ nix build
 $ python -mSimpleHTTPServer 8080
 # localhost:8080/hello.html
 ```
