# elpis-legal

Elpis の利用規約・プライバシーポリシーの**正本**。GitHub Pages で公開している。

- 利用規約: https://homio13.github.io/elpis-legal/terms/
- プライバシーポリシー: https://homio13.github.io/elpis-legal/privacy/

アプリ本体（`homio13/elpis`）は private なので Pages を出せない。
そのためこのリポジトリを分けている。**文面のコピーを elpis 側に置かない** ——
二重管理は必ず食い違う。改定履歴はこのリポジトリの `git log` が担う。

アプリからの参照は `client/.env.*` の `TERMS_URL` / `PRIVACY_URL` / `SUPPORT_URL`。
URL 未設定のあいだアプリはリンクを出さない実装になっている。

## 改定するとき

1. `terms.md` / `privacy.md` を直す
2. 冒頭の「最終改定日」を更新する
3. 実質的な変更なら、アプリ内でユーザーに通知する（規約 第13条 / ポリシー 第10条）
