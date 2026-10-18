# Zero Break Studio のサイト

GitHub Pages で公開する、スタジオのページとアプリのプライバシーポリシー。

| ページ | ファイル | 使い道 |
| --- | --- | --- |
| スタジオのトップ | `index.html` | Play Console の「組織のウェブサイト」 |
| 数独のプライバシーポリシー | `sudoku/privacy/index.html` | Play Console のストア掲載情報と、アプリの設定画面（ServiceConfig の privacyPolicyUrl） |

- 中身の元は Sudoku2 の `Store/privacy-policy.md`。ポリシーを変えたら両方を直し、ページの制定日（変更日）も書き換える。
- `.nojekyll` は、GitHub Pages にファイルをそのまま公開させるためのもの。
- Google Search Console の所有権確認で渡される `google〜.html` は、このフォルダのいちばん上に置いて公開する（消さない）。
