# 泥日教育｜學生手冊

收錄泥日教育各課程的學生手冊 HTML 版本，供內部同事瀏覽、審閱與測試使用。

## 目前收錄

| 課程 | 資料夾 | 狀態 |
|------|--------|------|
| 起飛班 | [`takeoff/`](./takeoff/) | ✅ 已上線 |
| 起步班 | `kickoff/` | 🚧 規劃中 |
| 起跑班 | `running/` | 🚧 規劃中 |
| 語感練功坊 | `sensei/` | 🚧 規劃中 |

## 本機預覽方式

由於這是 private repo，GitHub 網頁上不會直接渲染 HTML。請用以下其中一種方式預覽：

### 方法 1：Clone 後直接開啟

```bash
git clone git@github.com:heyitseliii/nii-student-handbooks.git
cd nii-student-handbooks
open takeoff/index.html   # macOS
```

### 方法 2：下載單一檔案

到對應資料夾，點擊 `index.html` → 右上角 `Download raw file` → 用瀏覽器開啟下載後的檔案。

### 方法 3：本機起一個簡單的 Server

```bash
cd nii-student-handbooks
python3 -m http.server 8000
# 然後打開 http://localhost:8000/takeoff/
```

## 給予回饋

發現問題或有建議請直接開 Issue，或在 Slack 上 tag Eli。
