
```sh
$ cargo new guessing_game
$ cd guessing_game
```

Filename: Cargo.toml
```
[package]
name = "guessing_game"
version = "0.1.0"
edition = "2021"

# See more keys and their definitions at https://doc.rust-lang.org/cargo/reference/manifest.html

[dependencies]

```

Filename: src/main.rs
```rs
fn main() {
    println!("Hello, world!");
}
```

```
$ cargo run
   Compiling guessing_game v0.1.0 (file:///projects/guessing_game)
    Finished dev [unoptimized + debuginfo] target(s) in 1.50s
     Running `target/debug/guessing_game`
Hello, world!
```