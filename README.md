# python

## Pythonのインストール


## Pythonのライブラリ
Pythonには最初からよくつかうライブラリが同封されており、標準ライブラリと呼ばれている。
しかし、Pythonには標準ライブラリに含まれないライブラリが大量にある。そして、多くの場合、そのサードパーティのライブラリを使いたくなるであろう。
そのようなライブラリを一箇所で管理するリポジトリがある。それがPython Package Index（PyPI）である。

PyPIから欲しいライブラリを探し、ダウン路どしてインストールすることが可能である。
しかし、例えば「AというライブラリはBというライブラリに依存している」といった状況があり、全部自力で解決するのは困難である。
そこで、パッケージのダウンロードや依存関係を解決するpipコマンドが用意されている。
コマンドラインから
```sh
pip install hoge
```
と入力すると、自動でPyPIから`hoge'を探してきて、依存関係も解決しつつインストールしてくれるようになる。
