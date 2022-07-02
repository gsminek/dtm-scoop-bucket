# DTM scoop bucket

DTM や音声合成ソフトウェアの [Scoop](https://scoop.sh) バケツです。Scoop は Windows 用のコマンドラインインストーラです。

## 使い方

1. Scoop をインストールする

    PowerShell で Scoop をインストールしてください。

    ```powershell
    > Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
    > irm get.scoop.sh | iex
    ```

1. このバケツを追加する

    scoop にこのバケツを追加してください。

    ```powershell
    > scoop bucket add dtm https://github.com/gsminek/dtm-scoop-bucket.git
    ```
