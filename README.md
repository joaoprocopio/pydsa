# pydsa

## desenvolver

```sh
uv sync
uv run jupyter lab
```

## rodar o livro

```sh
cargo install --version '0.4.52' mdbook && \
    cargo install --version '0.1.1' mdbook-jupyter
mdbook serve --open
```
