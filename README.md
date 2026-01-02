# uv2nix-add-package-sample

[uv2nix/templates/hello-world at master · pyproject-nix/uv2nix](https://github.com/pyproject-nix/uv2nix/tree/master/templates/hello-world)にPythonパッケージを追加するサンプルです。ここでは`pandas`を追加しています。

## 実行手順

```bash
$ nix develop
```

1. 

```bash
$ uv run hello
Hello from hello-world!
Pandas version: 2.3.3
```

## 新たなパッケージを追加する場合の手順

例えば、`plotly`パッケージを追加する場合、

```
$ uv add plotly
$ nix develop
```
