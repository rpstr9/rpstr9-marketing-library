# RPSTR9 skill library

A public library of reusable marketing instructions.

## Strategic Decision Check / 手段を選ぶ前に、目的から確かめる

判断や計画の相談に重ねて、得たい結果、必要な手段、実行する時期、既存資源、代替経路を確認します。最安・最小の案を常に勧めるものではありません。決定済みの条件を尊重し、必要な不足だけを尋ねます。

- [Strategic Decision Check — 指示の全文](https://raw.githubusercontent.com/rpstr9/rpstr9-marketing-library/main/STRATEGIC_DECISION_CHECK.md)
- [GitHubで全文を読む](STRATEGIC_DECISION_CHECK.md)
- [インストール用スキルフォルダを取得](strategic-decision-check.zip)

全文を相談中のチャットに添付し、「このスキルで、いまの相談を確認してください」と頼めます。既存の文脈を使うので、長い入力フォームは不要です。リンクを読めない環境では完全版をダウンロードして添付してください。全文の読み込みを確認します。

版1.0.0-candidate。無料で利用できます。インストールは任意です。ZIPを展開した `strategic-decision-check` フォルダを対応環境のスキルディレクトリに置き、明示的に `$strategic-decision-check` を指定できます。自動適用は環境に依存し、一度添付しただけで恒久的な自動適用が設定されるものではありません。特定モデルや実行スクリプトは不要です。比較に必要な事実は別途調べ、調査できない条件は未確認として扱います。購入・契約・公開などの権限は与えません。

## Brand Name Generator / ブランド名を戦略からつくる

ブランドホロタイプまたは同等の8要素戦略から、名称の方向、候補、読み、比較、推奨、未確認事項を作ります。表示名・アカウントID・ドメインを区別します。候補は由来やロゴを見せる前に語感・品位を審査し、信頼感を損なう無理な語呂合わせや可愛すぎる説明名は、短さや取得しやすさで救済しません。日本語名や自然な造語も、各ブリーフに照らして比較します。

- [Brand Name Generator — 指示と必須参照の全文](https://raw.githubusercontent.com/rpstr9/rpstr9-marketing-library/main/BRAND_NAME_GENERATOR.md)
- [GitHubで全文を読む](BRAND_NAME_GENERATOR.md)
- [インストール用スキルフォルダを取得](brand-name-generator.zip)

AIにはこの開始ガイド、命名の依頼、戦略の本文、市場・言語・使用媒体・変更できない条件を渡してください。AIは命名を依頼されたら上の完全版を全文読み、既存戦略を再作成せずに実行します。戦略がないときだけ、下記の完全なMarketerメソッドからBrand Holotype能力と必須全文資料を読み、必要な戦略を先に作ります。命名のみの依頼にPerception Flowやロゴ制作を追加しません。

リンクを読めない環境では完全版をダウンロードし、ファイルとして添付できます。インストールは任意です。ZIPを使う場合は、展開した `brand-name-generator` フォルダを利用するAI環境のスキルディレクトリへ置き、全文の読み込みを確認してください。名称の生成・比較と、使用権の確認・登録・公開は別の行為です。

版1.1.2-public-candidate。Mike CoulbournのMITライセンスの命名パッケージを適応。出典とライセンスは完全版・ZIPに収録。無料で利用できます。実行はAI環境の読込・調査能力に依存し、特定モデルは指定しません。

## Use the strategy skill

Open [Marketer — complete instructions](https://raw.githubusercontent.com/rpstr9/rpstr9-marketing-library/main/MARKETER.md) and provide your brand, product or task to an AI assistant that can read the full document. All required method sources are included in that single file; its internal links point to sections of the same document.

Use the full-text link above for AI reading. The [GitHub file page](MARKETER.md) is also available for human browsing.

No installation or named model is required. Execution depends on the assistant's available tools and its ability to read the required source text completely.

## Choose the task and check dependencies

| Requested task | Entry and required input |
|---|---|
| Choose a course of action from the desired outcome | [Complete Strategic Decision Check](STRATEGIC_DECISION_CHECK.md), with the current conversation or decision context. No strategy/naming/identity workflow is required. |
| Generate, compare or revise names | [Complete naming method and references](BRAND_NAME_GENERATOR.md#method), plus the existing eight-element strategy and naming brief. Read screening and language policy before generation; use the editorial reference when its stated conditions apply. |
| Build or revise strategy | Marketer's [complete source map](MARKETER.md#rpstr9-full-method) and [workflow](MARKETER.md#rpstr9-workflow), then the complete sources assigned to the requested capability. |
| Develop identity, creative briefs, plans or measures | The same source map, [dependency protocol](MARKETER.md#rpstr9-protocol) and [input/output contracts](MARKETER.md#rpstr9-contracts). Reuse valid upstream work and follow the relevant branch. |

The assistant must be able to retrieve the complete required text; a preview or contents list is not a substitute. Attach the downloaded document if link retrieval is unavailable. Current-name, handle, domain or preliminary trademark checks need browsing or the relevant search tool. Without that access, keep those checks visibly unperformed. Actual identity board images need an available image-generation tool; text briefs alone do not establish that images were produced. See the complete method for its fallback and review steps.

These are instruction packages, with no required executable script, runtime library, named model or external agent. Local skill installation is optional. Registration, purchases, account changes and publication require their own user-authorized scope. After revising an output, repeat the affected checks; preserve valid inputs and unrelated work. Model review is separate from audience evidence and legal clearance.

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
