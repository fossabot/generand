# generand
[![Rust](https://github.com/batmac/generand/actions/workflows/rust.yml/badge.svg)](https://github.com/batmac/generand/actions/workflows/rust.yml)
![Crates.io](https://img.shields.io/crates/v/generand)
![GitHub](https://img.shields.io/github/license/batmac/generand)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fbatmac%2Fgenerand.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fbatmac%2Fgenerand?ref=badge_shield)

crate to generate random sequences from your string/vec/iterator symbols.


- `cargo install generand --features=bin` to install the cli tool `generand`:

```
USAGE:
    generand [OPTIONS] [DICTIONARY]

ARGS:
    <DICTIONARY>

OPTIONS:
    -c, --cats
    -d, --digits
    -f, --full
    -h, --hex
        --help               Print help information
    -n, --number <NUMBER>    [default: 1]
    -s, --size <SIZE>        [default: 12]
    -V, --version            Print version information
   ```

# EXAMPLE
```
$ generand -n 15                       
LE8Nd1gemH5g Pe17VgBKe74U 4bbNdQ16mWIp hxNMwlqoHD8W 3Wd2EEBKdhxw aVuXwSvUP4im 
Yhmx6KP2bdyI iincIf6FUdqp GrA5l5VlJJKT ldZBH2AlhDsf nTTYWvlXW5Ss e3FHFVNQ5PrO 
Wo97SaSIewBG O6OCdQVblgsH h1ypG5vMv65a 
```

( or add `generand` in dependencies in your Cargo.toml to use the crate.)


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fbatmac%2Fgenerand.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fbatmac%2Fgenerand?ref=badge_large)