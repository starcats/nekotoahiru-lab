# nekotoahiru-lab

「うちのAI」シリーズの実験室。AIを使った小さなツール群を公開しています。

すべてブラウザで動く単体HTML。サーバ不要・ビルド不要。

## Tools

| ツール | 説明 |
|---|---|
| [うちのAI studio](./studio/) | 「こんなAIはいやだ」動画を簡易DSLで作れるブラウザツール |

## Live Demo

GitHub Pages公開後：
`https://nekotoahiru2026.github.io/nekotoahiru-lab/`

## ローカルで使う

```bash
# どれか開くだけ
open index.html          # ツール一覧
open studio/index.html   # うちのAI studio
```

ブラウザで直接ファイルを開くだけで動きます。

## ツールの追加方法

1. `<ツール名>/` ディレクトリを作成
2. `<ツール名>/index.html` を配置（単体で完結する形が望ましい）
3. ルートの `index.html` の tools-grid に新カードを追加

## Author

[@nekotoahiru2026](https://x.com/nekotoahiru2026)

## License

MIT
