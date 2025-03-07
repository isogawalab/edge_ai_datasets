## エッジAIコンピューティング

### Mac用データセットのダウンロード

`id_train.zip` と `id_test.zip` をダウンロードしてください。
こちらのデータは、以下のリポジトリのデータセットから拝借し、Mac用にTAがパスに変更を加えたものです。

https://github.com/TE-YoshinoriOota/Spresense-Tech-Seminar-Basic


### データセットの配置場所

上記のzipを展開した `id_train` と `id_test` フォルダを、`/Users/{user_name}/nncd_bucket/datasets` 直下に配置してください。

```bash
/Users/{user_name}/nncd_bucket/datasets
├── id_train
│   ├── data
│   └── index.csv
└── id_valid
    ├── data
    └── index.csv
```
