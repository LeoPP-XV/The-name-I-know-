# 🌿 Ordo Studiorum Philosophiae et Theologiae

哲學與神學自主研修學則暨課程規劃（第三版）的個人網站與研修檔案。
個人自主研修，非正式學制，不授予官方學分或資格。

## 內容
- `index.html`：單頁網站（學則、四年課程與學分追蹤、每週制度、論證方法、逐週課綱）
- `notes/_template.md`：每週研究札記模板
- `.github/workflows/pages.yml`：推送到 `main` 後自動部署 GitHub Pages

## 上線步驟
1. 在 GitHub 建立新 repo（例如 `ordo-studiorum`），把這些檔案推上去
2. Settings → Pages → Source 選 **GitHub Actions**
3. 稍等一分鐘，網址是 `https://<你的帳號>.github.io/ordo-studiorum/`

## 每週使用
1. 複製 `notes/_template.md` 為 `notes/2026-W43-PH101.md`，填寫後 commit
2. 完成課程後，在網站勾選該課，學分自動累計（存在瀏覽器本機）

## 維護
課程資料在 `index.html` 內的 `STAGES` 陣列。修訂學則時，同步更新版本與日期。
