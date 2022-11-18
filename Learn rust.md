# Learn Rust on windows

WSL
Ubuntu
apt update/upgrade

shell? might need proxy if cloning from github

```
export http_proxy="http://localhost:1080"
export https_proxy="http://localhost:1080"
```

or set -x http_proxy "http://localhost:1080" for fish shell

# Rust Start

- apt install gcc
- Rustup: install rust tool chain including Rust, Cargo
- Cargo: package management like maven for Rust
- Rustling: a repo of tutorial

Following tutorial at Rust offical website

While this does work (https://sacul.github.io/rust/cargo_proxy), it's better to use mirror source for Cargo https://runrust.miraheze.org/wiki/Rust_installation_special_notes_in_China/zh

Cargo's `carge update` will clone the git repo into ~/.cargo/index, which is about 200MB. If it takes too long and without response, you could go to the folder, find the git local repo, and clone and rename the folder following the obvious rule.

# Terminology



# Rust syntax

## Datatypes

## Control flow

## Ownership 

- Pass a parameter as value will pass the ownership and invalidate in the caller scope
- Pass a reference &var most of time
- Only one mutable ref at a time, &mut var; Unless it's never used after the second one is declared (lexical scope)
- 

## Class 

## Functional paradiams

## Debug

-  Add `#[derive[Debug]]` to struct, and placeholding with `{:?}` or `{:#}`; dbg! macro is useful as well 
# Rust ecosystem

## IO

## Math

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

# Thoughts

Difference with Closure:
- Make mutability explicit, instead of by default build on immutability
- Still be safe and clear
- Stronger typing, while keeps the symplicity of expressiveness with the help of type inferring


