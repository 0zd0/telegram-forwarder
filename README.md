# Telegram Forwarder

Forwarding or copying messages/posts from chats/channels (including those with forwarding restrictions). Supports a pool of accounts with separate configurations. Independent of the implementation of a specific client library ([Hydrogram](https://github.com/hydrogram/hydrogram), [Telethon](https://github.com/LonamiWebs/Telethon)), as a basic adapter is implemented, but asynchrony is required.

## Development

1. Install dependencies (including dev):
```shell
uv install --group dev
```
(add `--group hydro` if you need a hydrogram)

2. Install git hooks
```shell
uv run pre-commit install --install-hooks
```

3. Run the tests
```shell
uv run pytest
```