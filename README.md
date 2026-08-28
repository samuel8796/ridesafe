# RideSafe

匿名化乘車安全回報平台 prototype。

## 產品原則
- 不公開司機姓名、平台頭像、電話、住址或完整車牌。
- 不建立針對私人個人的「最糟司機排行榜」或跨來源負面人物檔案。
- 只公開達到驗證門檻的匿名化事件與聚合風險訊號。
- 正式版應加入人工審核、申訴/更正、證據遮罩、資料保存期限與濫用防護。

## GitHub Pages
Repository 建立後：
1. 將本專案內容 push 到 `main`。
2. GitHub → Settings → Pages → Source 選 `GitHub Actions`。
3. `Deploy static site to Pages` workflow 會部署網站。

## 本地預覽
直接開啟 `index.html`。

## Submitted incident handling
Public pages show only redacted evidence previews. Original screenshots must not be committed to the public repository.
Names, faces, license plates / vehicle identifiers, phone numbers, exact pickup points and other directly identifying details are excluded from the public build.
