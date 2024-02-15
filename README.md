# 2023 THE F2E 前端修練精神時光屋 - 立委競選官網

![](https://images.thef2e.com//works/217_2023-11-07T08:29:32.597Z.png)

## Description

針對一位即將競選立法委員的AI候選人所設計的官方網站，致力於為候選人塑造出良好的形象，同時提供重要的政見主張資訊以及捐款指引。

## Getting Started

**Version**

本專案在 Node.js `v20.10.0` 環境下進行開發。

Install the project

```bash
$ npm install
```

Run the project

```bash
$ npm run dev
```

## Project structure description

```shell
├── public
│   └── assets/                  # 包含公共的圖像資源，如字體、圖像等。
├── components                   # 包含應用程式中的可重複使用元件。
│   ├── About/                   
│   ├── Campaign/                
│   ├── ContactUs/               
│   ├── Donate/                  
│   ├── Home/                    
│   ├── Layout/                  
│   ├── Policy/                  
│   └── UI/                      
├── constants/                   # 專案中用來定義常數值的一個模組或目錄。
├── hooks/                       # 用於存放自定義的React Hooks，這些Hooks是用來處理組件邏輯、狀態管理、以及與其他React功能的集成。
├── pages                        # 包含應用程式的頁面元件，用於建立不同的頁面。
│   ├── api/                     # 包含應用程式的設定檔或設定。
│   ├── _app.tsx                 # 應用程式的主應用程式元件。
│   └── index.tsx                # 應用程式的主入口檔案。
├── styles/                      # 存放與網頁或應用程式的樣式相關的資源文件。
├── utils/                       # 包含各種輔助工具或功能的實用工具函數。。
├── .eslintrc.json               # 用於配置 ESLint 的配置檔案，它控制著 JavaScript 代碼風格和品質的檢查工具。
├── .gitignore                   # 指定哪些檔案或目錄不應該被Git版本控制系統追蹤或提交到版本儲存庫中。
├── next-env.d.ts                # 用於定義全域的 TypeScript 類型，讓 TypeScript 編譯器能夠正確地理解 Next.js 的特定 API 和模組。
├── next.config.js               # 是 Next.js 項目中的一個配置文件，用於定制和設定 Next.js 應用程式的各種行為和功能。
├── package-lock.json            # 鎖定安裝的 npm package 版本的檔案。
├── package.json                 # 專案的npm套件設定文件，包含了專案依賴和腳本。
├── postcss.config.js            # 配置 PostCSS 的設定檔案，用於處理 CSS 的工具。
├── tailwind-default.config.js   # 自定義 Tailwind CSS 框架的各種設定，例如顏色、字體、間距、陰影等。
├── tailwind.config.js           # 自定義顏色、字型、間距、邊框等各種設定，以及啟用或禁用特定的功能和模組。
├── tsconfig.json                # TypeScript的設定文件，用於指定專案的編譯選項。
└── README.md                    # 包含項目的簡要描述和使用說明的自述文件。
```

## Built With

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Swiper](https://swiperjs.com/)
- [Aos](https://michalsnik.github.io/aos/)
- [Animate.css](https://animate.style/)
- [React-modal](https://www.npmjs.com/package/react-modal)
- [React-countup]()
- [React-scroll-parallax]()
- [Dayjs](https://day.js.org/)
- [Postcss]()
- [Zod]()

## 🔗 Link

- [2023 THE F2E](https://2023.thef2e.com/)
- [Design - Mock Up](<https://www.figma.com/proto/GDvhrmKAtFgcHe5aVjBci0/2023TheF2E-%E7%AC%AC%E4%B8%80%E9%9A%8E%E6%AE%B5-%E7%AB%8B%E5%A7%94%E7%AB%B6%E9%81%B8%E5%AE%98%E7%B6%B2(UNA)?page-id=80%3A569&type=design&node-id=80-570&viewport=521%2C203%2C0.25&t=V9f9YjM3wHfkRUeV-1&scaling=scale-down>) (by Una)
- [Design - Figma](<https://www.figma.com/file/GDvhrmKAtFgcHe5aVjBci0/2023TheF2E-%E7%AC%AC%E4%B8%80%E9%9A%8E%E6%AE%B5-%E7%AB%8B%E5%A7%94%E7%AB%B6%E9%81%B8%E5%AE%98%E7%B6%B2(UNA)?type=design&node-id=0-1&mode=design>) (by Una)
- [Demo](https://legislative-election-cyruslung.vercel.app/) (by Cyrus)