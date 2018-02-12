Elixir on Alpine Linux
=====

Elixir is a dynamic, functional language designed for building scalable and maintainable applications.

Elixir version: **1.6.1**
Image size: **25.3 MB**

See [Erlang/Elixir on Alpine Linux](https://github.com/msaraiva/alpine-erlang) to learn more about creating **minimal Erlang/Elixir docker images with Alpine Linux**.

> **Notice:** This image does not contain git, wget, rebar or hex. If you need to download dependencies, see [aeons/elixir-dev](https://registry.hub.docker.com/u/aeons/elixir-dev/)

The following packages are pre-installed:

- erlang + dependencies
- elixir

> **Notice:** In order to keep images as compact as possible, Erlang libraries for Alpine Linux are split into many different packages. The full list of Erlang packages available can be found [here](https://pkgs.alpinelinux.org/packages?name=erlang*&branch=v3.5).

## Usage

```
$ docker run --rm -it aeons/elixir iex
Erlang/OTP 20 [erts-9.1.5] [source] [64-bit] [smp:4:4] [ds:4:4:10] [async-threads:10] [hipe] [kernel-poll:false]

Interactive Elixir (1.6.1) - press Ctrl+C to exit (type h() ENTER for help)
iex(1)> IO.puts "Hello, world!"
Hello, world!
:ok
iex(2)>
```
