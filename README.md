# learn-rust-with-rustlings

Small exercises to get you used to reading and writing Rust code by 
[*rustlings*](https://github.com/rust-lang/rustlings)

## License

All source code in the [RustLings Repo](https://github.com/rust-lang/rustlings)

## README (EN)

Small exercises to get you used to reading and writing Rust code. Includes practice reading and responding to compiler messages! 

This repo is my rustlings' solution collection. Hope it can help you more or less. :)

**🎉 Successfully compiled all rustlings exercises! All the answers can be found in corresponding folders.** For example, you can check file `exercises/strings/strings1.rs` to read my solution about `strings` chapter.

* ✅ if
* ✅ functions
* ❎  variables
* ❎  primitive_types
* ❎  strings
* ❎  modules
* ❎  macros
* ❎  move_semantics
* ❎  error_handling
* ❎  threads
* ❎  standard_library_types

## Manually Installation

Basically: Clone the repository, checkout to the latest tag, run `cargo install`.

```bash
git clone https://github.com/rust-lang/rustlings
cd rustlings
git checkout tags/4.3.0 # or whatever the latest version is (find out at https://github.com/rust-lang/rustlings/releases/latest)
cargo install --force --path .
```

If there are installation errors, ensure that your toolchain is up to date. For the latest, run:
```bash
rustup update
```

Then, same as above, run `rustlings` to get started.

## Doing exercises

The exercises are sorted by topic and can be found in the subdirectory `rustlings/exercises/<topic>`. For every topic there is an additional README file with some resources to get you started on the topic. We really recommend that you have a look at them before you start.

The task is simple. Most exercises contain an error that keep it from compiling, and it's up to you to fix it! Some exercises are also run as tests, but rustlings handles them all the same. To run the exercises in the recommended order, execute:

```bash
rustlings watch
```

This will try to verify the completion of every exercise in a predetermined order (what we think is best for newcomers). It will also rerun automatically every time you change a file in the `exercises/` directory. If you want to only run it once, you can use:

```bash
rustlings verify
```

This will do the same as watch, but it'll quit after running.

In case you want to go by your own order, or want to only verify a single exercise, you can run:

```bash
rustlings run exercises/path/to/exercise.rs
```

In case you get stuck, there is usually a hint at the bottom of each exercise.

## Testing yourself

After every couple of sections, there will be a test that'll test your knowledge on a bunch of sections at once. These tests are found in `exercises/testN.rs`.
