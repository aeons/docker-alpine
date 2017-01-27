FROM aeons/elixir:1.4.1
MAINTAINER Bjørn Madsen <bm@aeons.dk>

RUN apk --no-cache add erlang-crypto erlang-syntax-tools erlang-parsetools erlang-inets erlang-ssl \
    erlang-public-key erlang-eunit erlang-asn1 erlang-sasl erlang-erl-interface erlang-dev wget git

RUN mix local.hex --force && \
    mix local.rebar --force

CMD ["/bin/sh"]
