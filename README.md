# learn-rust

## First installation note

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
info: downloading installer

Welcome to Rust!

This will download and install the official compiler for the Rust
programming language, and its package manager, Cargo.

Rustup metadata and toolchains will be installed into the Rustup
home directory, located at:

  /home/rizki/.rustup

This can be modified with the RUSTUP_HOME environment variable.

The Cargo home directory is located at:

  /home/rizki/.cargo

This can be modified with the CARGO_HOME environment variable.

The cargo, rustc, rustup and other commands will be added to
Cargo's bin directory, located at:

  /home/rizki/.cargo/bin

This path will then be added to your PATH environment variable by
modifying the profile files located at:

  /home/rizki/.profile
  /home/rizki/.bashrc

You can uninstall at any time with rustup self uninstall and
these changes will be reverted.

Current installation options:


   default host triple: x86_64-unknown-linux-gnu
     default toolchain: stable (default)
               profile: default
  modify PATH variable: yes

1) Proceed with installation (default)
2) Customize installation
3) Cancel installation
>1

info: profile set to 'default'
info: default host triple is x86_64-unknown-linux-gnu
info: syncing channel updates for 'stable-x86_64-unknown-linux-gnu'
781.5 KiB / 781.5 KiB (100 %) 494.9 KiB/s in  1s ETA:  0s
info: latest update on 2023-08-03, rust version 1.71.1 (eb26296b5 2023-08-03)
info: downloading component 'cargo'
  7.0 MiB /   7.0 MiB (100 %) 745.6 KiB/s in 11s ETA:  0s
info: downloading component 'clippy'
  2.3 MiB /   2.3 MiB (100 %)   1.1 MiB/s in  2s ETA:  0s
info: downloading component 'rust-docs'
 13.6 MiB /  13.6 MiB (100 %)   1.6 MiB/s in 11s ETA:  0s
info: downloading component 'rust-std'
 26.1 MiB /  26.1 MiB (100 %)   1.0 MiB/s in 28s ETA:  0s
info: downloading component 'rustc'
 55.0 MiB /  63.5 MiB ( 87 %)   1.2 MiB/s in  1m 27s ETA:  7s
info: retrying download for 'https://static.rust-lang.org/dist/2023-08-03/rustc-1.71.1-x86_64-unknown-linux-gnu.tar.xz'
 63.5 MiB /  63.5 MiB (100 %) 159.0 KiB/s in  3m 48s ETA:  0s
info: downloading component 'rustfmt'
  2.3 MiB /   2.3 MiB (100 %) 716.3 KiB/s in  3s ETA:  0s
info: installing component 'cargo'
info: installing component 'clippy'
info: installing component 'rust-docs'
 13.6 MiB /  13.6 MiB (100 %)   2.7 MiB/s in  5s ETA:  0s
info: installing component 'rust-std'
 26.1 MiB /  26.1 MiB (100 %)  10.1 MiB/s in  3s ETA:  0s
info: installing component 'rustc'
 63.5 MiB /  63.5 MiB (100 %)  11.0 MiB/s in  7s ETA:  0s
info: installing component 'rustfmt'
info: default toolchain set to 'stable-x86_64-unknown-linux-gnu'

  stable-x86_64-unknown-linux-gnu installed - rustc 1.71.1 (eb26296b5 2023-08-03)


Rust is installed now. Great!

To get started you may need to restart your current shell.
This would reload your PATH environment variable to include
Cargo's bin directory ($HOME/.cargo/bin).

To configure your current shell, run:
source "$HOME/.cargo/env"
```
