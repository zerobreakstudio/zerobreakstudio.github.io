# Zero Break Studio のサイト

GitHub Pages で公開する、スタジオのページとアプリのプライバシーポリシー。

| ページ | ファイル | 使い道 |
| --- | --- | --- |
| スタジオのトップ | `index.html` | Play Console の「組織のウェブサイト」 |
| 数独のプライバシーポリシー | `sudoku/privacy/index.html` | Play Console のストア掲載情報と、アプリの設定画面（ServiceConfig の privacyPolicyUrl） |

- 中身の元は Sudoku2 の `Store/privacy-policy.md`。ポリシーを変えたら両方を直し、ページの制定日（変更日）も書き換える。
- `.nojekyll` は、GitHub Pages にファイルをそのまま公開させるためのもの。
- `app-ads.txt` は AdMob（パブリッシャー ID pub-9106565573997532）の売り手の証明。サイトのいちばん上に置いたままにする。Play のストア掲載情報の「ウェブサイト」にこのサイトの URL を入れると、AdMob がこれを読みに来る。
- Google Search Console の所有権確認で渡される `google〜.html` は、このフォルダのいちばん上に置いて公開する（消さない）。
