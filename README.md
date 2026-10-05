# RPSTR9 skill library

A public library of reusable marketing instructions.

## Brand Name Generator / ブランド名を戦略からつくる

ブランドホロタイプまたは同等の8要素戦略から、名称の方向、候補、読み、比較、推奨、未確認事項を作ります。表示名・アカウントID・ドメインを区別します。候補は由来やロゴを見せる前に語感・品位を審査し、信頼感を損なう無理な語呂合わせや可愛すぎる説明名は、短さや取得しやすさで救済しません。日本語名や自然な造語も、各ブリーフに照らして比較します。

- [Brand Name Generator — 指示と必須参照の全文](https://raw.githubusercontent.com/rpstr9/rpstr9-marketing-library/main/BRAND_NAME_GENERATOR.md)
- [GitHubで全文を読む](BRAND_NAME_GENERATOR.md)
- [インストール用スキルフォルダを取得](brand-name-generator.zip)

AIにはこの開始ガイド、命名の依頼、戦略の本文、市場・言語・使用媒体・変更できない条件を渡してください。AIは命名を依頼されたら上の完全版を全文読み、既存戦略を再作成せずに実行します。戦略がないときだけ、下記の完全なMarketerメソッドからBrand Holotype能力と必須全文資料を読み、必要な戦略を先に作ります。命名のみの依頼にPerception Flowやロゴ制作を追加しません。

リンクを読めない環境では完全版をダウンロードし、ファイルとして添付できます。インストールは任意です。ZIPを使う場合は、展開した `brand-name-generator` フォルダを利用するAI環境のスキルディレクトリへ置き、全文の読み込みを確認してください。名称の生成・比較と、使用権の確認・登録・公開は別の行為です。

版1.1.1-public-candidate。Mike CoulbournのMITライセンスの命名パッケージを適応。出典とライセンスは完全版・ZIPに収録。無料で利用できます。実行はAI環境の読込・調査能力に依存し、特定モデルは指定しません。

## Use the strategy skill

Open [Marketer — complete instructions](https://raw.githubusercontent.com/rpstr9/rpstr9-marketing-library/main/MARKETER.md) and provide your brand, product or task to an AI assistant that can read the full document. All required method sources are included in that single file; its internal links point to sections of the same document.

Use the full-text link above for AI reading. The [GitHub file page](MARKETER.md) is also available for human browsing.

No installation or named model is required. Execution depends on the assistant's available tools and its ability to read the required source text completely.

## Concept Review

The complete instructions include a shared Concept Review skill. It researches relevant expert perspectives, challenges candidate concepts, sends revisions back to the originating skill, and rechecks them before concrete idea development. Direct strategy, identity and planning calls use the same review. Unchanged concepts reuse a valid review; no fixed expert panel or additional approval pause is required. Simulated critique remains distinct from actual expert participation and audience evidence.

## Brand identity drafts

Brand Identity Director develops three candidate identities in three independent generation calls and delivers three standalone board images. Each call receives its own concept brief and references plus the approved shared brand context. The separate results are inspected, compared and presented with a recommendation before the user chooses a direction.

## Source

The 30 complete method sections retain the maintained source depth. Scoped identity input/process wording distinguishes preserve/adapt from create; this candidate adds three complete identity references and their activation routes. Baseline: link edition 1.4.9, method version 1.3.8. The baseline contains 30 complete source sections; this candidate contains those 30 plus three complete identity references (33 sections total).

- Original file: `MARKETER.md`
- Size: 420,557 bytes
- SHA-256: `e8d79f95736a7507fa309a6bfd358deb233f59256af53426efd90d92e61c8589`

This repository is testing the simplest public delivery route. Public availability and successful retrieval by an AI browsing tool are checked separately. The pre-existing Marketer document has no repository-wide reuse license specified. The naming package carries its own included upstream MIT notice; that notice does not relicense unrelated library material.
