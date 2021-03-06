# How to include files in Rust.

One of the things that people struggle the most when starting to learn Rust is how to include modules, especially when they are deeply nested throughout the application.

The problem is that Rust considers every file to be a module, and the directories (folders) as sub-modules. You need to expose each individual sub-module to the parent so they can be accessed. This is a repo shows how can that be done. It will show you how to include files, modules, structs, enums, and more to any file.

Navigate to the [/src](/src) folder and inspect the files (starting from main.rs) to learn how files are included.

I strongly recommend watching Rust 2018 - Modules, External Crates, Submodules, Paths and Visibility Modifiers video from TensorProgramming - https://www.youtube.com/watch?v=U8uhW9bFm-8 to get a complete grasp of the module system.

## References:

- Rust 2018 - Modules, External Crates, Submodules, Paths and Visibility Modifiers video from TensorProgramming - https://www.youtube.com/watch?v=U8uhW9bFm-8
- https://doc.rust-lang.org/reference/visibility-and-privacy.html
- https://github.com/rust-lang/book/issues/1709
- https://stackoverflow.com/questions/57535061/how-to-use-another-file-in-rust-module-with-hyphens-in-it
- https://users.rust-lang.org/t/how-to-call-a-function-in-another-file-but-the-same-crate/15214
- https://stackoverflow.com/a/26390046/1057052
- https://stackoverflow.com/questions/45519176/how-do-i-use-or-import-a-local-rust-file
- https://stackoverflow.com/questions/26224947/how-do-i-do-a-basic-import-include-of-a-function-from-one-module-to-another-in-r
