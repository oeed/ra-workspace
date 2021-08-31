VS Code Rust Analyzer issue [#9093](https://github.com/rust-analyzer/rust-analyzer/issues/9093) reproduction.

Try running the take 'in .code-workspace'; it'll fail with `There is no task provider registered for tasks of type "cargo".`

Running the same task defined in `tasks.json` will succeed, however.
