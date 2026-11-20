# 総合問題 訂正情報サイト

一橋祭 SDS模擬店「三度の飯よりホットサンド」で配布した総合問題（全5回）の訂正情報ページです。

| 回 | 公開URL | 編集するファイル |
|---|---|---|
| 一覧 | https://sds-mogiten.github.io/errata/ | （編集不要） |
| 第1回 | https://sds-mogiten.github.io/errata/1 | `1.md` |
| 第2回 | https://sds-mogiten.github.io/errata/2 | `2.md` |
| 第3回 | https://sds-mogiten.github.io/errata/3 | `3.md` |
| 第4回 | https://sds-mogiten.github.io/errata/4 | `4.md` |
| 第5回 | https://sds-mogiten.github.io/errata/5 | `5.md` |

## 訂正を追加・修正する方法（スマホ・PCどちらでも可）

1. このリポジトリで、該当する回の `1.md`〜`5.md` を開く
2. 右上の鉛筆アイコン（Edit this file）を押す
3. `## 訂正一覧` のすぐ下に訂正を書き足す（「現在、訂正はありません。」の行は消す）
4. 「Commit changes...」→「Commit changes」を押す
5. 1分ほどでサイトに反映される

## 書き方

```markdown
### 問3 (2)
- **誤**：$\displaystyle \int_0^1 x^2\,dx = \frac{1}{2}$
- **正**：$\displaystyle \int_0^1 x^2\,dx = \frac{1}{3}$
- 掲載日：11月22日
```

- 数式は LaTeX と同じく `$...$`（インライン）と `$$...$$`（別行立て）で書けます（MathJax で表示）。
- `\(...\)` と `\[...\]` も使えます。ドル記号そのものは `\$` と書きます。
- 編集するのは `1.md`〜`5.md` だけで大丈夫です。`.html`・`style.css`・`app.js` は表示用の仕組みなので触らなくてOKです。
