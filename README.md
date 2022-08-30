# 06-readable-async-iterator

This program shows how to consume a readable stream using the async iterator interface.

## Run

To run the example, use 

> npm start

Write in the standard input (console) and use `ctrl+d`(unix) or `ctrl+z`(windows) to end the input stream.

Alternatively:

> cat <path/to/file> | node read-stdin.js

to consume an arbitrary file
