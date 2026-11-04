# skill-receipt（自己投資レシート）

自己投資の「お金・時間・指標の変化・振り返り」をレシートにして貯め、月・半期・年・冊子（A5）にまとめるClaude用のSkillです。

## かんたんスタート（登録なし）
新しいチャットに、次の文をそのまま貼ります。Claudeの設定には何も登録しません。

```
次のリンクの SKILL.md を読み、このチャットの間はその手順に従って「自己投資レシート」を作ってください。
https://raw.githubusercontent.com/s4qr-tech/skill-receipt/main/SKILL.md
・SKILL.md の中の references/ templates/ site/ は、https://raw.githubusercontent.com/s4qr-tech/skill-receipt/main/ の配下にあるので、必要になったときに読み込むこと
・最初に、レシートの保存先（Googleドライブ または 手元のフォルダ）を私に聞くこと
・私のデータを、このリポジトリに保存しないこと
・このチャットが続く間は、この手順を守り続けること
```

- うまく動かなくなったら:「SKILL.md をもう一度読み直して」と伝えます。
- 見本の画面: https://s4qr-tech.github.io/skill-receipt/index.html
- Claudeがリンクを読めない環境では、下の「つかい方」のとおりZIPを添付します。

## つかい方
1. このリポジトリを ZIP でダウンロードして解凍します。
2. Claudeに「skill-receipt フォルダをSkillとして追加して」と頼みます（ZIPを添付してもOK）。
3. 初回に、レシートの保存先（Googleドライブ または ローカル）を聞かれるので選びます。
4. あとは話しかけるだけです。
   - 「このリンクをレシートにして」＋リンク・金額・日付
   - 「TOEICのスコアは500から710になった」＋スコア票の写真
   - 「10月をまとめて」
   - 「冊子にして」→ 開いて「PDFで保存」

## 見本の画面
`site/index.html` をブラウザで開くと、ダミーデータの画面を見られます。

## 守られること
- 「ひとこと振り返り」の原文は書き換えません。校正は出力時だけです。
- 確認できていない数字は【実績】にしません（【試算】【計画】と区別します）。
- あなたのデータはこのフォルダに入りません。保存先は自分のドライブ／PCです。

## フォルダ
- `SKILL.md` Claudeへの手順書
- `references/` 書式・校正・見た目の決まり
- `templates/` TOEIC・簿記・英検・汎用のひな形
- `site/` 画面の見本（HTML+CSS）
- `sample-receipts/` ダミーのレシート

使用者の名前は、出力されるHTMLの `<body data-user="…">` で変わります。
