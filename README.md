# 牧者照片畫廊

教會開堂禮拜出席牧者貴賓的照片展示網站。

## 專案資訊

- **Repository**: https://github.com/welovetwn/pastor-gallery.git
- **用途**: 展示教會開堂禮拜出席的牧者貴賓資訊
- **技術**: 純 HTML/CSS/JavaScript，無需框架

## 檔案結構

```
pastor-gallery/
├── index.html          # 主頁面
└── photos/             # 牧者照片目錄
    ├── pastor-01.png
    ├── pastor-02.png
    └── ... (共19張照片)
```

## 功能特色

- 響應式設計，支援各種裝置尺寸
- Metro 風格的色彩配置
- 點選照片可查看牧者詳細資料（姓名、教會、職位）
- 無障礙設計（ARIA labels）

## 修改記錄

### 2025-10-24
- 初始化牧者照片畫廊網站
- 新增 index.html 和 19 張牧者照片
- 更新按鈕文字為「簡介」（將 aria-label 和提示文字從「查看詳細資料」和「查看教會資訊」改為「簡介」）

## 使用方式

直接在瀏覽器中開啟 `index.html` 即可查看。
