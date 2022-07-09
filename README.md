## Monkey

```
            __,__
   .--.  .-"     "-.  .--.
  / .. \/  .-. .-.  \/ .. \
 | |  '|  /   Y   \  |'  | |
 | \   \  \ 0 | 0 /  /   / |
  \ '- ,\.-"""""""-./, -' /
   ''-' /_   ^ ^   _\ '-''
       |  \._   _./  |
       \   \ '~' /   /
        '._ '-=-' _.'
           '-----'
```

- [x] mathematical expressions
- [x] variable bindings
- [x] functions
- [x] application of those functions
- [x] conditionals
- [x] return statements
- [x] higher-order functions
- [x] closures
- [x] data types
  - [x] integers
  - [x] booleans
  - [x] strings
  - [x] arrays
  - [x] hashes
- [x] bytecode compiler
- [x] virtual machine

### Eval

```sh
go run main.go
```

### VM

```sh
go build -o monkey . && ./monkey
```

### Benchmark

```sh
go build -o fibonacci ./benchmark
./fibonacci -engine=eval
./fibonacci -engine=vm
```

## Writing An Interpreter In Go

Go there and buy this now: https://interpreterbook.com/
