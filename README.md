# website

Personal static website generated using [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) and [Jinja](https://jinja.palletsprojects.com/en/stable/).

The modification of the standard `materials` theme is inspired by [pawamoy](https://pawamoy.github.io/)'s beautiful website.

The generated website is graciously hosted by [GitHub](https://pages.github.com/) at [ka-sarthak.github.io](https://ka-sarthak.github.io).

## Development

- Setup environment with `pip` and run website locally.

    Clone the package, create a Python virtual environment, and install the dependencies:
    ```sh
    python -m venv .venv
    source .venv/bin/activate
    pip install .
    ```

    Run the website locally using:
    ```sh
    mkdocs serve
    ```

- Alternatively, use [uv](https://docs.astral.sh/uv/) to setup the environment and run the website locally:
    ```sh
    uv sync
    uv run mkdocs serve
    ```