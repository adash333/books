# このリポジトリでの作業ルール

- **チャットの返事は、いつも日本語で書く**。
- このリポジトリは公開の「本の読者用ページ」（GitHub Pages、 https://adash333.github.io/books/ ）。本の付録の印刷用シート（空欄と記入例の PDF）と、巻ごとのページだけを置く。章の文章・解説・練習問題・模範作品の全文は置かない（KDPセレクトの電子書籍の独占のため。方針の正本は非公開の `writing-presentation-lab` の `docs/repository-policy.md` 第6節の2。このリポジトリからはリンクしない）。
- シートのもとは、非公開の `kindle-publishing` の各巻の `sheets/sheets.json` にある。PDF は `node scripts/reader-sheets/make_sheets.cjs books/<巻のフォルダ>` で作り、できた PDF をこのリポジトリの巻のフォルダにコピーする。このリポジトリで PDF を直接直さない。
- 作業記録（プロンプトと結果）は、このリポジトリに置かず、`kindle-publishing` の `docs/prompt/` に書く。
- 子どもの作文、子どもの名前や学校に関する情報、個人情報は置かない。
- 否定形の文は極力使わない。Markdown の表の前には空行を入れる。リンクは相対リンクで張る。
- 巻のフォルダの名前：`narrative/`（第1巻）、`opinion/`（第2巻）、`essay/`（第3巻）、`essay-advanced/`（第4巻）。
