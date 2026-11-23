# vs-wobbly-deps

A Python metapackage
for installing [Wobbly](https://github.com/Jaded-Encoding-Thaumaturgy/Wobbly)'s dependencies.

## Installation

`vs-wobbly-deps` is distributed via PyPi.
You can install it with the following command:

```shell
pip install vs-wobbly-deps
```

You can also add this package to an existing `uv` project
by using the following command:

```shell
uv add vs-wobbly-deps --group wobbly
```

Remember to configure and legacy register
your project's Vapoursynth module
so Wobbly will actually use this venv!

```shell
uv run vapoursynth config
uv run vapoursynth register-legacy-install
```
