# act-scrum-docs-template

スクラム開発でのプロジェクト(プロダクト)管理に使う、ドキュメントテンプレート集です。プロダクトゴールの明確化、スプリントの計画とレビュー、インセプションデッキによる関係者の認識合わせを支援します。

プロダクトオーナー、スクラムマスター、開発者、ステークホルダーが、目的や成果について共通認識を持ち、継続的に検査・適応するために利用します。

## 収録内容

### スクラムイベント関連ドキュメント

- スクラムイベントを手助けするドキュメントを格納しています。
- [01_sprint_documents](./01_sprint_documents)に、以下のテンプレートを収録しています。

| ドキュメント | 内容 |
| --- | --- |
| [product_goal.md](./01_sprint_documents/product_goal.md) | プロダクトが目指す成果と、その達成を判断する指標を整理します。 |
| [sprint_planning.md](./01_sprint_documents/sprint_planning.md) | 今回のスプリントのゴール、バックログ項目、作業計画を記録します。 |
| [sprint_review.md](./01_sprint_documents/sprint_review.md) | 今回のスプリントの成果、フィードバック、ゴールの達成可否を記録します。 |
| [pre_sprint_planning.md](./01_sprint_documents/pre_sprint_planning.md) | 前回のスプリントのゴールと計画を記載しておきます。 |
| [pre_sprint_review.md](./01_sprint_documents/pre_sprint_review.md) | 前回のスプリントの成果とレビュー結果を記載しておきます。 |

> 収録していないスクラムイベント(リファイメントやレトロスペクティブなど)は、各自フォーマットを用意の上、実施してください。

### ワークショップ関連ドキュメント

- インセプションデッキを活用して、立ち上げ時に関係者の目的・方向性を揃えるための課題と進め方を紹介しています。
- [README.md](./02_workshop_documents/README.md)を参照し、必要な課題に取り組んでください。
- インセプションデッキの各課題は、[images](./02_workshop_documents/images)と[Googleドライブ](https://docs.google.com/presentation/d/1ulJPxMsdpA8VcqLOjUcSb4G1WyX3Vfiy/edit?usp=drive_link&ouid=103908980228298744161&rtpof=true&sd=true)にテンプレートを用意しています(どちらも同様の課題)。

## 使い方

- [act-scrum-docs-template](https://github.com/ap-communications/act-scrum-docs-template)にアクセスし、`Use this template`を押下する
- 下記内容を記入して、`Create repository`を押下しリポジトリを作成する
  - Start with a template: ap-communications/act-scrum-docs-template
  - General
    - Owner: ap-communications
    - Repository name: act-{{ 案件名 }}-{{ scrum }}-docs
    - Description: {{ 案件名 }}のスクラム開発用ドキュメント ※記載内容は任意

## 利用上の注意

- 本リポジトリはスクラム開発を支援するドキュメント集です。バックログの管理などは案件ごと(例：Backlogのプロジェクト)に別途管理してください。
- スクラムのすべてのイベントや作成物を網羅しているわけではありません。たとえば、デイリースクラム、レトロスペクティブ、リファイメントは含まれていません。
- テンプレートは対話と合意形成を支援するためのものです。記入すること自体を目的にせず、状況に応じて内容を見直してください。
- スクラムの定義やルールは、[スクラムガイド 2020 日本語版](https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-Japanese.pdf)を参照してください。
