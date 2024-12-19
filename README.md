# review-badge

レビュー時に利用できるバッジを管理します。

レビューコメントに以下のように書いておきましょう。
> [!NOTE]
> コメントのバッジについては[こちら](https://github.com/guncys/review-badge)をご参照ください。

## バッジ一覧

| badge | 期待するリアクション | 意味 | リンク |
| --- | --- | --- | --- |
| ![ask-badge](https://img.shields.io/badge/review-ask-blue.svg) | 回答必須 | 確認 | `![ask-badge](https://img.shields.io/badge/review-ask-blue.svg)` |
| ![must-badge](https://img.shields.io/badge/review-must-red.svg) | 修正必須 | この対応がされていないと Approve できない | `![must-badge](https://img.shields.io/badge/review-must-red.svg)` |
| ![imo-badge](https://img.shields.io/badge/review-imo-orange.svg) | 修正任意 | こういう表現もあります | `![imo-badge](https://img.shields.io/badge/review-imo-orange.svg)` |
| ![nits-badge](https://img.shields.io/badge/review-nits-green.svg) | 修正任意 | 細かい指摘 | `![nits-badge](https://img.shields.io/badge/review-nits-green.svg)` |
| ![next-badge](https://img.shields.io/badge/review-next-blueviolet) | 修正不要 | 今後の改善点 | `![next-badge](https://img.shields.io/badge/review-next-blueviolet)` |
| ![memo-badge](https://img.shields.io/badge/review-memo-lightgrey) | - | コード理解・解説のためのメモ書き | `![memo-badge](https://img.shields.io/badge/review-memo-lightgrey)` |
| ![good-badge](https://img.shields.io/badge/review-good-blightgreen.svg) | - | 良い点 | `![good-badge](https://img.shields.io/badge/review-good-blightgreen.svg)` |

## 使い方

- PullRequestのレビュー時などに使う。
- レビューコメントの冒頭などにリンクの文字列をコピぺする。
  - ![image](https://github.com/user-attachments/assets/6ac5ccfe-44d2-410a-afb5-0473b46328e3)

### Saved Replies

- GitHubの[Saved Replies](https://docs.github.com/ja/get-started/writing-on-github/working-with-saved-replies/creating-a-saved-reply)に登録しておくと便利。
  - 毎回コピペする必要がなくなります。
  - ![image](https://github.com/user-attachments/assets/62026718-b05e-4ecb-9584-94e2cb8cf834)

## 参考にした記事

- [レビューコメントにメタ情報を持たせよう](https://zenn.dev/yumemi_inc/articles/review-badge)
- [コードレビューにラベルを付けるだけでチームの心理的安全性を高めた話](https://zenn.dev/hacobell_dev/articles/code-review-comment-prefix)
