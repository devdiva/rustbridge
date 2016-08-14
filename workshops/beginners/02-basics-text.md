# Basics  _Rename_

We'll start going over some Rust language basics.  

_Note: This is using the Guessing Game example from Rust book._

## Goals

_TODO_

## Steps

### Step 1. Setup


Change to your working directory.  For example, `cd ~/projects`.

Create the Rust project using Cargo's `new` command.

```bash
cargo new guessing_game --bin
```

```bash
cd guessing_game
```

If you have `tree` installed, you can quickly check the contents in your ocmmand line.  
Otherwise, use `ls`.

```bash
tree .
```

```bash
ls -la
```

```bash
ls -la src
```

Cargo has generated the basic structure we need for a Rust project.

`src`
`main.rs`
`Cargo.toml`

For good measure, the project has also been initialized with git and a `gitignore` file.

_TODO add instruction_

```bash
cargo build
```

```bash
cargo run
```

Observe, what happened?  

_TODO add note about compile/run output in terminal._

The build process created new folder `target` with a debug version of the guessing_game.

Just for kicks, try running it again directly.

```bash
./target/debug/guessing_game
```


	
## Next Steps

_Next: [Let's make something art!][1]_

_Self Guideded: [Finish the Guessing Game][2]_

### References

[1]: # "RustBridge Tutorial: Make Art"
[2]: https://doc.rust-lang.org/book/guessing-game.html "The Rust Book, Tutorial: Guessing Game"
[3]: http://doc.crates.io/ "Cargo"
[4]: https://doc.rust-lang.org/book/getting-started.html "The Rust Book, Getting Started"