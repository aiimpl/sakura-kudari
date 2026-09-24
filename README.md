# 桜川くだり

three.js で作った、苫舟で日本の川を下る 3D シーン。HTML 1 ファイルで、画像・3D モデル・音声ファイルは使わず、地形・草・木・水・人物・天気・効果音まですべてコードで生成しています。

**ブラウザで遊ぶ：https://aiimpl.github.io/sakura-kudari/**

外部サービスへの接続はありません（three.js とフォントは同梱）。手元で動かす場合は、ES モジュールを読み込むためローカルサーバー経由で開いてください（例：`python3 -m http.server` → http://localhost:8000）。

## 操作
| キー | 内容 |
|---|---|
| W / S | 漕ぐ速さ |
| A / D | 舵 |
| ドラッグ | 視点（ホイールで距離） |
| 1〜6 | 朝・陽光・霧・雨・夕焼け・夜 |
| T | 天気が自動で移り変わる |
| V | 映画カメラ |
| H | UI を隠す |

## 同梱しているもの（サードパーティ）
| 内容 | 場所 | ライセンス |
|---|---|---|
| three.js r160 | `vendor/three/` | MIT（`vendor/three/LICENSE`） |
| Shippori Mincho B1 | `fonts/shippori-mincho-b1/` | SIL Open Font License 1.1（同フォルダの `LICENSE`） |
| Zen Kaku Gothic New | `fonts/zen-kaku-gothic-new/` | SIL Open Font License 1.1（同フォルダの `LICENSE`） |

フォントは @fontsource 配布のファイルを改変せずに使い、画面に表示する文字を含む分割ファイルだけを同梱しています。

Built with Claude Opus 5.5.
