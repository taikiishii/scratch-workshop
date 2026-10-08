# Scratch 体験ワークショップ

共通ルール（すべての教材で同じ）はこちら:

@../workshop-kit/CLAUDE.md

上の読み込みが効かない環境のために、要点だけ再掲します。

- **編集してよいのは `content/` と `site.toml` だけ。** `docs/` は `python build.py` の生成物。
- `docs/assets/` の共通部品と `.gitignore` `.vscode/settings.json` は **workshop-kit が配る**。
  直すときは `../workshop-kit/wskit/` を直す（＝すべての教材に効く）。
- **表（`| … | … |`）はスライドで使えない。** 箇条書きにする。
- コミットメッセージは日本語。`docs/` もコミットに含める。

---

## この教材のきまり

書き方の詳細は [AUTHORING.md](AUTHORING.md)。とくに：

- 章フォルダ名の頭 … **i=導入編 / b=基本編 / c=制御編 / g=ゲーム編 / e=拡張機能編 / p=作品編 / x=付録**
- カードの枠色は `c1`〜`c5`
- **プログラムはブロックの画面キャプチャで見せる。** 文字のコードブロックは使わない
- ブロック名・カテゴリー名は、言語設定「**日本語**」の Scratch の画面に出る文字と**一字一句**同じにして「**…**」でかこむ
- **ゲーム編は1章＝1パターン、プログラムはシンプルに**（AUTHORING.md「ゲーム編の作り方」）

## 事実の裏取り

- ブロックの名前・メニューの場所は [Scratch のエディター](https://scratch.mit.edu/projects/editor/) の実画面で確認する
- オフライン版・アカウント・共有のきまりは [Scratch の FAQ](https://scratch.mit.edu/faq) で確認する
- マイクロビット連携は [scratch.mit.edu/microbit](https://scratch.mit.edu/microbit) で確認する
- 画面キャプチャは Scratch の最新UIに合わせて撮る（古いUIのままにしない）

## 公開しないもの

- `archive/` … 元資料や .sb3 の下書き（`.gitignore` で除外済み）
