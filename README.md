# trustIT2023/.github

trustIT2023 の組織共通 Issue テンプレートの正本である。

## 📋 概要

`.github/ISSUE_TEMPLATE/` に置いたテンプレートが、trustIT2023 配下の全リポジトリの Issue 作成画面に表示される。
Public / Private を問わず適用される。

| テンプレート | Type の既定値 | ファイル |
| --- | --- | --- |
| タスク | `Task` | [01_Doc_02_Rule_4_MdnGit_3_tmpl_issue.md](.github/ISSUE_TEMPLATE/01_Doc_02_Rule_4_MdnGit_3_tmpl_issue.md) |
| bug | `Bug` | [01_Doc_02_Rule_4_MdnGit_3_tmpl_bug_report.md](.github/ISSUE_TEMPLATE/01_Doc_02_Rule_4_MdnGit_3_tmpl_bug_report.md) |
| リファクタリング | `Feature` | [01_Doc_02_Rule_4_MdnGit_5_tmpl_feature_report.md](.github/ISSUE_TEMPLATE/01_Doc_02_Rule_4_MdnGit_5_tmpl_feature_report.md) |

## 運用ルール

- テンプレートの追加・変更は、このリポジトリで行う。
- 変更は作業ブランチで行い、Pull Request を通して `main` に取り込む。`main` へ直接 push しない。
  このリポジトリは Public のため、push する前にローカルで内容のレビューを受ける。
- 各リポジトリには、独自の `.github/ISSUE_TEMPLATE/` を原則置かない。
  1つでも置くと、そのリポジトリでは共通テンプレートがすべて表示されなくなる。
- テンプレートでは Type だけを指定し、ラベルは指定しない。
  ラベルを指定すると、同じラベルをこのリポジトリと全リポジトリに作っておく必要がある。
- このリポジトリは Public である（組織共通テンプレートは Public のリポジトリでないと反映されない）。
  社内のリンク・人名・パスなど、公開できない情報をテンプレートに書かない。

## 🌐 関連リンク

- [Creating a default community health file - GitHub Docs](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
- [Configuring issue templates for your repository - GitHub Docs](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/configuring-issue-templates-for-your-repository)
