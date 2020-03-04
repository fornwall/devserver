# devserver
An extremely tiny tool to serve a static folder locally.

This tool is only for local development and makes no effort to be secure for other purposes.

## Installation
```
cargo install devserver
```

## Usage
Open a command line and navigate to the directory you'd like to host then run:
```
devserver
```

Visit http://localhost:8000 to see your hosted content.

## Options
`--https`   Enables https with an insecure self-signed certificate.
`--address` Pass an address like "127.0.0.1:8080" or "localhost:8000" to change the address the server will host on.
`--help`    Explains available options.

