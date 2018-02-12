Erlang/OTP on Alpine Linux
=====

Erlang/OTP minimal environment.

Latest version: **20.1.7-r2**
Image size: **16.7 MB**

See [Erlang/Elixir on Alpine Linux](https://github.com/msaraiva/alpine-erlang) to learn more about creating **minimal Erlang/Elixir docker images with Alpine Linux**.

The following packages are pre-installed:

- ncurses-libs
- erlang-kernel
- erlang-stdlib
- erlang-compiler
- erlang

> **Notice:** In order to keep images as compact as possible, Erlang libraries for Alpine Linux are split into many different packages. The full list of Erlang packages available can be found [here](https://pkgs.alpinelinux.org/packages?name=erlang*&branch=v3.5).

## Usage

```
$ docker run --rm -it aeons/erlang erl
Erlang/OTP 20 [erts-9.1.5] [source] [64-bit] [smp:4:4] [ds:4:4:10] [async-threads:10] [hipe] [kernel-poll:false]

Eshell V9.1.5  (abort with ^G)
1> io:fwrite("Hello, world!\n").
Hello, world!
ok
2>
```
