# Benchz

> Zsh startup time benchmarks

## Installation & usage

```sh
git clone https://github.com/filipekiss/benchz
cd benchz
./benchz
```

The script will run two benchmarks: One **vanilla** and your **custom** setup.
You'll get an output like the one below:

```sh
The average startup time for vanilla is: 11 ms
The average startup time for custom is: 125 ms
```

## How it works

The script will startup the shell 100 times and average how long it takes to
completely start it.

## Options

### -n [integer] | default: 100

`./benchz -n 50`

Use this to change how many iterations the script will perform. Defaults to 100

## Thanks

- [@Eriner](https://github.com/Eriner), for writing [zsh-framework-benchmark](https://github.com/Eriner/zsh-framework-benchmark/) which is the base for this script

---

**benchz** © 2019+, Filipe Kiss Released under the [MIT] License.<br>
Authored and maintained by Filipe Kiss with help from contributors ([list][contributors]).

> GitHub [@filipekiss](https://github.com/filipekiss) &nbsp;&middot;&nbsp;
> Twitter [@filipekiss](https://twitter.com/filipekiss)

[mit]: http://mit-license.org/
[contributors]: http://github.com/filipekiss/benchz/contributors
