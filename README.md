rbenv role sample
==================

# 概要

以下の手順を実行します
指定するユーザが存在しない場合はエラーになります

1. 指定したユーザの権限でrbenvをインストール
2. rbenvにruby-buildプラグインをインストール
3. 指定したrubyをインストール
4. rbenv globalでデフォルトのrubyバージョンを設定
5. gem bundlerをインストール

# 動作確認済み環境

- ubuntu12.04
- ubuntu14.04

# 設定

    rbenv_user # rbenvをインストールするユーザ
    rbenv_install_ruby_version # インストールするrubyバージョン
    rbenv_default_ruby_version # rbenv globalで指定するバージョン


# 依存関係

依存するroleはありません

