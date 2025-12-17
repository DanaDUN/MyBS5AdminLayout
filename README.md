# MyBS5AdminLayout
## 模板使用說明

### 一、核心主題與 CSS 變數
```
  所有主題設定都集中在 wwwroot/css/site.css 檔案最上方的 :root 區塊。
  --sidebar-bg：主色，用於側邊藍背景、主要按鈕、Active 邊條。
  --sidebar-hover-bg：懸停色，用於按鈕和選單懸停效果。
  --brand-red：強調色(LOGO色)，用於警告、刪除、Active 狀態的邊條。
  --corp-secondary：次要色，沉穩灰藍色，用於表格邊框、輪廓按鈕。
  --body-bg：內容被景色，用於內容區和 Active 選單底色。
  --corp-text-dark：文字色，確保高對比閱讀體驗。
```

### 二、客製化 CSS 類別
```
    .content-card：內容卡片基礎樣式，包含圓角和微妙陰影。
    .table-corp：數據表格樣式，包含統一標題被景色和斑馬紋。
    .btn-corp 系列：自定義按鈕樣式。
    .fixed-action-footer：固定操作欄，確保 儲存/取消 按鈕在捲動時可見。
    .nav-pills-corp：自定義 Pills，確保 Tab/垂直導航 顯示主色系填充。
    .submenu-link：處理側邊欄子選單的縮排和 Hover 效果。
```

### 三、維護和擴展提示
1. 修改顏色：只需要修改 site.css 中的 :root 區塊顏色變數，即可統一更新全站色調。
2. 調整尺寸：若要修改側邊欄寬度，請統一調整 :root 中的 --sidebar-width-。
