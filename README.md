# minigrep
This is a very basic version of grep written following the ![Building a Command Line Program](https://doc.rust-lang.org/stable/book/ch12-00-an-io-project.html) chapter of the official rust programming language book.

To run, simply use `cargo run query path/to/file.txt` where query is the string to search for. Optionally the IGNORE_CASE environment variable can be set, or the command can be run with the additional flag `-ignore_case` in order to make the search case insensitive.