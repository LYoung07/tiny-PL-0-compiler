# tiny-PL/0 compiler

Compiling:
----------

Compile compiler: `make`

Compile vm: `gcc -o vm vm.c`

Executing:
----------

run compiler: `./compile (arguments) (input) (output)`

run vm: `./vm (input)`

arguments:

* `--source` Display input PL/0 code
* `--clean` Display input PL/0 Code without comments
* `--tokens` Display tokens found from lexer
* `--pm0` Display PM/0 code generated from parser

Examples:
---------

Example: `./compile input.pl0 output.pm0`

Example: `./vm output.pm0`
