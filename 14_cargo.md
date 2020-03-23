# Caogo

## Profiles
* [profile.*]
    * for each profiles
* [profile.dev]
    * for develop
    * `cargo build` apply
* [profile.release]
    * for release
    * `cargo build —release` apply
* opt-level
    * optimise code
    * 0-3, more bigger => more compile time, run faster
* configuration wiki
    * https://doc.rust-lang.org/cargo/reference/manifest.html#the-profile-sections
## Document
* generate html
* //!
    * crate document
* ///
    * function document
* `cargo doc`
    * generate html in target/doc
* `cargo doc —open`
    * open the crate document html in browser
* sections
    * Examples : demo code
    * Panics : how to panic for others to avoid
    * Errors : all kinds of Result error
    * Safety : why unsafe
* test
    * `cargo test` will run demo code in Examples document
* re-export
    * `pub use self::xx:xxx;`
* crate.io
    * login : `cargo login xxxxxx`
    * publish : `cargo publish`
* Rust license : MIT OR Apache-2.0
* new version :  version in Cargo.toml
* yanking
    * prevent new project depend on that version
    * `cargo yank —vers 1.0.1`
    * `cargo yank —vers 1.0.1 —undo` to cancel a yank
## Workspaces
* a set of packages
* `cargo run -p x` : run a particular package
* `cargo test -p x` : test a particular package
## Install binaries
* `cargo install ripgrep`
* can only install packages that have binary targets( has src/main.rs file )
* default directory : ~/.cargo/bin
## Cargo Extend
* ~/cargo-something , can run `cargo something`
* `cargo —list` show all options