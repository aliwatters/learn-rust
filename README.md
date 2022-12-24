# Learn Rust

12/24/22 - https://doc.rust-lang.org/book/

## Chapter 01 Notes; 12/24

- `println!("string");` -- `name!()` run a macro,`name()` run a function.
- `rustc` -- compiler
- `cargo` -- is the tool chain
  -- `cargo new project_name` -- new dir and scaffolding in `project_name` -- note it's a git init'd repo
  -- `cargo build` -- makes a binary in `target` dir
  -- `cargo run` -- builds and runs
  -- `cargo check` -- doesn't run or build, just syntax check
  -- `cargo build --release` -- makes a prod version

Typical workflow;

```
$ git clone example.org/someproject
$ cd someproject
$ cargo build
```

Note: `rm -r chapter-01/hello_cargo/.git` so that I have a single repo for this.

## Chapter 02 Notes; 12/24
