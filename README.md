# 分帳房 SplitRoom

手機用的分帳小工具，單一 `index.html`，資料存在瀏覽器 localStorage。

## 功能
- 新增分帳成員，每筆記錄金額、誰先付、分給哪些人
- 自動結算：每人先付 / 應分攤 / 差額，以及「誰要給誰多少錢」（最少轉帳筆數）
- 開房間：6 碼房號或邀請連結，多支手機同步記帳（PeerJS / WebRTC 點對點）
- 房主離線會自動換人當房主；離線記的帳連上後自動合併
- 匯出 / 匯入備份

## 部署
Settings → Pages → Deploy from a branch → `main` / `(root)`。
