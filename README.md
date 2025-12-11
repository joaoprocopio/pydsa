# pydsa

material de referência do [curso](https://hub.la/g/L8wi9vio7WPnWbmF8ZIO).  
esse material serve pra ir desenvolvendo entendimento no assunto.

## setup no [zed](https://zed.dev/)

### pre-requisitos
- ter o `uv` instalado: https://zed.dev/docs/installation
- ter o `cargo` instalado (vem junto com o rust): https://rust-lang.org/tools/install/

### desenvolver

```sh
uv sync
uv run jupyter lab
```

### rodar o livro localmente

```sh
cargo install --version '0.4.52' mdbook && \
    cargo install --version '0.1.1' mdbook-jupyter
mdbook serve --open
```
