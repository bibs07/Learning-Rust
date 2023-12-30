# Learning Rust

This is me learning rust using RUST book. \

Available at [Rust WebSite](https://doc.rust-lang.org/stable/book/) or offline by running `rustup docs --book`
To compile `.rs` file. Run `rustc {fileName}.rs;`

## Cargo

Cargo is Rust's build system and package manager. \
Run ` cargo new {project_name}` to create new project. \

- Note for myself: After running `cargo new` command. Run

  [Comment]: <> (To store everything in same repo. `cargo run` initialises git repo for every project. This is to remove all the git repo reference.)

```
rm -rf .git
rm -rf .gitignore
```

Run following to build and run the project.

```
cargo build
./target/debug/{project_name}
```

Or, simply run `cargo run` to build and run the project using single command.

- Run `cargo check` to check if your code'll copile.

For production ready application, run `cargo build --release`. This'll save the executable file in `target/release` instead of `target/debug`
