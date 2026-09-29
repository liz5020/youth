# youth

## 如何上傳資料

### 方法一：GitHub 網頁（最簡單）
1. 進入 https://github.com/liz5020/youth
2. 點選 **Add file → Upload files**
3. 把檔案拖曳進去（可一次多個，或整個資料夾）
4. 填寫說明後按 **Commit changes**

> 單一檔案上限 25MB（網頁）；超過請用方法二或 Git LFS。

### 方法二：Git 指令
```bash
git clone https://github.com/liz5020/youth.git
cd youth
cp /你的檔案路徑/檔名.xlsx data/
git add data/
git commit -m "新增資料"
git push
```

### 方法三：請 Claude 代為上傳
在 Claude Code 對話中附上檔案或貼上內容，請 Claude 放進 `data/` 並 commit、push。

## 資料夾
- `data/`：資料檔（`data/sample.csv` 為上傳測試用範例）
