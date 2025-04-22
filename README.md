## エッジAIコンピューティング

### Mac用データセットのダウンロード

※ windowsユーザでも場合によって使用することがあります

`id_train.zip` と `id_test.zip` をダウンロードしてください。
こちらのデータは、以下のリポジトリのデータセットから拝借し、Mac用にTAがパスに変更を加えたものです。

https://github.com/TE-YoshinoriOota/Spresense-Tech-Seminar-Basic


### オプション

`robust`データセットはTAが独自で作成したデータセットです。

Spresenseで撮影した，環境光の映り込み（白飛び）があったり，斜めから撮影したりした，推論の難しいデータセットです．難しいデータセットで検討を行いたい場合はこちらをテストデータとして使用してください．


### データセットの配置場所

上記のzipを展開した `id_train` と `id_test` フォルダを、`/Users/{user_name}/nncd_bucket/datasets` 直下に配置してください。

```bash
/Users/{user_name}/nncd_bucket/datasets
├── id_train
│   ├── data
│   └── index.csv
├── id_valid
│   ├── data
│   └── index.csv
└── robust # option
    ├── data
    └── index.csv
```
