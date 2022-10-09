Two options for development:

a) Using web-based Gitpod environment - ready to code straight away
    links below: 
    1) JS code: https://gitpod.io/#https://github.com/near-examples/donation-js
    2) Rust code: https://gitpod.io/#https://github.com/near-examples/donation-rust
    3) AssemblyScript: https://gitpod.io/#https://github.com/near-examples/docs-examples/blob/main/donation-as 

b) Work locally requires setup of pre-requisites:

Pre-requisites:

1) Rust : check you have rust using cmd line input "rustc --version"
    - if not: install using this link: https://doc.rust-lang.org/book/ch01-01-installation.html

2) wasm32-unknown-unknown (enables compiling Rust to Web Assembly - wasm)
    Web Assembly is the low-level language used by the Near Platform
    - check using cmd line input "rustup target list" returns cross-compile support 

   

