rust-watch
====

> A watch script for on-save crate compilation of rust-empty-like projects

## Getting started

```bash
cp watch /usr/local/bin                   # Copy watch to your bin folder
# ln -s /abs/path/to/watch /usr/local/bin # Alternatively, create an alias
cd ../rust-empty                          # Change to your project directory
watch                                     # Watch for changes
```

##Usage

`watch` will recompile using `make` any time a file in your `src` directory changes.

The command and directory are configurable, in case you don't use rust-empty:
```bash
# $1: Directory to watch
#     src by default
# $2: Command to execute
#     `make` by default
```

---

I've (@zzmp) been frequenting `#rust` on the mozilla irc. Come say hi.
