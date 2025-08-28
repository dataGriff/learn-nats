# Nats Getting Started

- [Video](https://www.youtube.com/watch?v=hjXIUPZ7ArM&list=PLgqCaaYodvKY22TpvwlsalIArTmc56W9h&index=1)

## Fan In

In a fan-in scenario, multiple publishers send messages to a single subscriber. This pattern is useful for aggregating data from multiple sources.

## Fan Out

In a fan-out scenario, a single publisher sends messages to multiple subscribers. This pattern is useful for broadcasting messages to multiple consumers.

## Wildcards

NATS supports wildcards in subject names, allowing subscribers to listen to multiple subjects with a single subscription. The two types of wildcards are:

1. **Single-level wildcard (`*`)**: Matches any single token in the subject. For example, `hello.*` matches `hello.world` but not `hello.world.test`.

2. **Multi-level wildcard (`>`)**: Matches any number of tokens in the subject. For example, `hello.>` matches `hello.world` and `hello.world.test`.
