# rustack
This is a rust-devstack

## useful commands:

Rust's package manager
- **cargo**:
  - Create a new cargo package `cargo new`
  - Compile the current package `cargo build`
  - Run a binary or example of the local package `cargo run`
  - help `cargo --help`

    ```
    Commands:
    build, b    Compile the current package
    check, c    Analyze the current package and report errors, but don't build object files
    clean       Remove the target directory
    doc, d      Build this package's and its dependencies' documentation
    new         Create a new cargo package
    init        Create a new cargo package in an existing directory
    add         Add dependencies to a manifest file
    remove      Remove dependencies from a manifest file
    run, r      Run a binary or example of the local package
    test, t     Run the tests
    bench       Run the benchmarks
    update      Update dependencies listed in Cargo.lock
    search      Search registry for crates
    publish     Package and upload this package to the registry
    install     Install a Rust binary
    uninstall   Uninstall a Rust binary
    ...         See all commands with --list
    ``` 

The Rust toolchain installer
- **rustup**:
  ```
  Commands:
  show         Show the active and installed toolchains or profiles
  update       Update Rust toolchains and rustup
  check        Check for updates to Rust toolchains and rustup
  default      Set the default toolchain
  toolchain    Modify or query the installed toolchains
  target       Modify a toolchain's supported targets
  component    Modify a toolchain's installed components
  override     Modify toolchain overrides for directories
  run          Run a command with an environment configured for a given toolchain
  which        Display which binary will be run for a given command
  doc          Open the documentation for the current toolchain
  self         Modify the rustup installation
  set          Alter rustup settings
  completions  Generate tab-completion scripts for your shell
  help         Print this message or the help of the given subcommand(s)
  ```

## useful websites:

- [rust-lang.org](https://www.rust-lang.org/)
- [crates.io](https://crates.io/)
- [github.com/rust-lang](https://github.com/rust-lang)

**Learn**
- [rust-lang/learn](https://www.rust-lang.org/learn)
- [rust-lang/book](https://doc.rust-lang.org/book/)
- [doc-rust-lang](https://doc.rust-lang.org/stable/)
- [rustlings](https://github.com/rust-lang/rustlings/)
- [rust-by-example](https://doc.rust-lang.org/rust-by-example/)