# デプロイ運用メモ — AI企業研修LP

- 正本は GitHub リモート。ローカルは作業コピー（消えても再 clone で復旧）。
- Vercel プロジェクトは 1 リポにつき 1 つ。**再作成しない**。
- 更新は「clone → 編集 → main に push」→ Vercel が自動再デプロイ。
- 本番URLは production alias（`<project>.vercel.app`）を正本にする。
- Cowork からは「AI企業研修LPを更新して」で再デプロイできる。

## 構成
- 静的HTML1枚（`index.html`）。ビルド不要・DB/課金なし。
