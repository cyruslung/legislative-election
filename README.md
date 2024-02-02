# 2023 THE F2E 前端修練精神時光屋 - 立委競選官網

![](https://images.thef2e.com//works/217_2023-11-07T08:29:32.597Z.png)

## 🔗 Link

- [2023 THE F2E](https://2023.thef2e.com/)
- [Design - Mock Up](<https://www.figma.com/proto/GDvhrmKAtFgcHe5aVjBci0/2023TheF2E-%E7%AC%AC%E4%B8%80%E9%9A%8E%E6%AE%B5-%E7%AB%8B%E5%A7%94%E7%AB%B6%E9%81%B8%E5%AE%98%E7%B6%B2(UNA)?page-id=80%3A569&type=design&node-id=80-570&viewport=521%2C203%2C0.25&t=V9f9YjM3wHfkRUeV-1&scaling=scale-down>) (by Una)
- [Design - Figma](<https://www.figma.com/file/GDvhrmKAtFgcHe5aVjBci0/2023TheF2E-%E7%AC%AC%E4%B8%80%E9%9A%8E%E6%AE%B5-%E7%AB%8B%E5%A7%94%E7%AB%B6%E9%81%B8%E5%AE%98%E7%B6%B2(UNA)?type=design&node-id=0-1&mode=design>) (by Una)
- [Demo](https://legislator-campaign-official-website-iqko.vercel.app/) (by Cyrus)

## 🚀 Getting Started

Install the project

```bash
$ npm install
```

Run the project

```bash
$ npm run dev
```

## 🔧 Built With

- [Next.js](https://nextjs.org/)
- [Vercel](https://vercel.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Swiper](https://swiperjs.com/)
- [Aos](https://michalsnik.github.io/aos/)
- [Animate.css](https://animate.style/)
- [React-modal](https://www.npmjs.com/package/react-modal)
- [Dayjs](https://day.js.org/)

## 作品說明

針對一位即將競選立法委員的AI候選人所設計的官方網站，致力於為候選人塑造出良好的形象，同時提供重要的政見主張資訊以及捐款指引。

## 系統說明

**版本**

本專案在 Node.js `v20.10.0` 環境下進行開發。

**專案運行**

您可以按照以下步驟運行專案：

```shell
npm install
npm run dev
```

這些命令將安裝所有必要的相依套件，並啟動開發伺服器，讓您能夠開始開發和預覽您的專案。

如果您需要更多詳細資訊，請參考專案的 `package.json`。

## 資料夾說明

```shell
├── public
│   └── images/       # 包含公共的圖像資源，這些圖像可以在網站上使用。
├── src               # 專案的主要原始碼資料夾，包含了應用程式的原始程式碼。
│   ├── assets/       # 包含應用程式的靜態資源，如圖像、字體等。
│   ├── components/   # 包含應用程式中的可重複使用元件。
│   ├── config/       # 包含應用程式的設定檔或設定。
│   ├── pages/        # 包含應用程式的頁面元件，用於建立不同的頁面。
│   ├── theme/        # 包含應用程式的樣式或主題相關的檔案。
│   ├── utils/        # 包含各種輔助工具或功能的實用工具函數。
│   ├── App.tsx       # 應用程式的主應用程式元件。
│   ├── main.tsx      # 應用程式的主入口檔案。
├── index.html        # 應用程式的主HTML文件，用於載入JavaScript檔案和渲染應用程式。
├── tsconfig.json     # TypeScript的設定文件，用於指定專案的編譯選項。
├── package.json      # 專案的npm套件設定文件，包含了專案依賴和腳本。
├── DESIGN.md         # 設計稿、設計規範等相關說明
└── README.md         # 包含項目的簡要描述和使用說明的自述文件。
```

## 使用技術

**前端框架與函式庫**

- React.js：前端開發框架，用於建立使用者介面和應用程式的元件。
- styled-components：用於建立和管理應用程式的樣式的 CSS-in-JS 函式庫。
- Material UI：提供現代UI元件的函式庫，用於建立漂亮的使用者介面。

**建置工具**

- Next.js：用於快速創建高效React，輕鬆實現靜態生成和伺服器端渲染，提供更好的使用者體驗和 SEO。

**類型系統**

- Typescript：提供靜態型別檢查，提高程式碼品質和開發效率。

**動畫效果**

- AOS（Animation of Scroll）：用於實現頁面滾動時的動畫效果的函式庫。

**部署和託管**

- gh-pages：用於將應用程式部署到 GitHub Pages，以便在線上示範和分享專案。