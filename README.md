# 📚 Cursor Training - フロントエンド学習プロジェクト

このリポジトリは、HTML、CSS、JavaScriptの基礎から応用までを段階的に学習するための実践的なサンプルコレクションです。

## 📁 プロジェクト構造

```
cursor-training/
├── README.md                    # このファイル
├── .cursor/                     # Cursor設定ファイル
│   └── rules/                   # Cursor Rules設定
│       ├── update-readme.mdc    # README自動更新ルール
│       └── ec-commerce.mdc      # ECサイト開発ルール
├── case1/                       # 基本的なHTML+CSS
│   ├── index.html              # メインページ
│   ├── about.html              # アバウトページ
│   └── hogehoge.html           # サンプルページ
├── case2/                       # ToDoアプリケーション
│   ├── index.html              # メインHTML
│   ├── app.js                  # アプリケーションロジック
│   └── style.css               # スタイルシート
├── case3/                       # インタラクティブカード（GSAP）
│   ├── index.html              # メインHTML
│   ├── script.js               # アニメーションスクリプト
│   └── styles.css              # スタイルシート
├── case4/                       # ループ処理の練習
│   └── loop.js                 # 配列操作関数
├── case5/                       # 定数管理とユーティリティ
│   └── config.js               # 設定ファイル
├── case6/                       # ボタンコンポーネント
│   └── button.html             # ボタンデザインシステム
└── case7/                       # ECサイト（ShopEasy）
    ├── index.html              # メインHTML
    ├── app.js                  # 商品・カート管理
    └── style.css               # スタイルシート
```

## 🎯 学習ケース詳細

### Case 1: 基本的なHTML+CSS

- **目的**: HTML5とCSS3の基本構造を理解する
- **技術**: HTML5, CSS3, Flexbox
- **機能/内容**:
  - セマンティックHTML（`<nav>`, `<main>`タグの使用）
  - ナビゲーションバーの実装
  - CSS変数とホバーエフェクト
  - レスポンシブデザインの基礎（box-sizing、viewport設定）

### Case 2: ToDoアプリケーション 📝

- **目的**: JavaScriptのクラス構文とCRUD操作を学ぶ
- **技術**: HTML5, CSS3, ES6+ JavaScript（クラス、アロー関数）
- **機能/内容**:
  - クラスベースのアプリケーション設計
  - CRUD操作（作成・読み込み・更新・削除）
  - LocalStorageによるデータ永続化
  - フィルター機能（全て・未完了・完了済み）
  - イベント委譲パターンの実装
  - インライン編集機能（ダブルクリック、Enter/Escapeキー）
  - XSS対策（HTMLエスケープ）

### Case 3: インタラクティブカード 🎨

- **目的**: アニメーションライブラリ（GSAP）の使い方を習得する
- **技術**: HTML5, CSS3, JavaScript, GSAP 3.12.5
- **機能/内容**:
  - GSAPによる高度なアニメーション
  - 順次表示アニメーション（stagger効果）
  - ホバーアニメーション（浮き上がり効果）
  - クリックアニメーション（色変更、回転）
  - イージング関数の活用（elastic, back, power）
  - ランダムカラー生成

### Case 4: ループ処理の練習 🔄

- **目的**: 基本的なループ構文と配列操作を理解する
- **技術**: JavaScript（while, for, Array methods）
- **機能/内容**:
  - `while`ループを使った配列操作（doubleArray）
  - `for`ループを使った合計計算（sumArray）
  - `indexOf`を使った重複削除（uniqueArray）
  - 関数の基本構造とreturn文

### Case 5: 定数管理とユーティリティ 🛠️

- **目的**: マジックナンバーの排除と保守性の高いコード設計を学ぶ
- **技術**: ES6+ JavaScript（const, 関数、オブジェクト）
- **機能/内容**:
  - 定数の適切な命名規則（UPPER_SNAKE_CASE）
  - 税率・割引率計算ロジック
  - API設定の一元管理
  - ユーティリティ関数の設計
  - 関数の責務分離（単一責任の原則）

### Case 6: ボタンコンポーネント 🎨

- **目的**: CSS変数とコンポーネントベースのデザインシステムを構築する
- **技術**: HTML5, CSS3（CSS変数、BEM命名規則）, JavaScript
- **機能/内容**:
  - CSS変数（カスタムプロパティ）の活用
  - BEM命名規則（Block, Element, Modifier）
  - 多様なボタンバリエーション（primary, secondary, success, danger, outline, ghost）
  - サイズバリエーション（small, medium, large）
  - ボタン状態管理（loading, disabled）
  - アクセシビリティ対応（aria-label, focus-visible, キーボード操作）
  - リップルエフェクト（:before疑似要素）
  - レスポンシブデザイン（モバイルファースト）

### Case 7: ECサイト - ShopEasy 🛒

- **目的**: 実践的なECサイトの商品一覧とカート機能を実装する
- **技術**: HTML5, CSS3, ES6+ JavaScript（async/await, アロー関数）
- **機能/内容**:
  - 商品データ管理（SAMPLE_PRODUCTS配列）
  - 商品カードの動的生成
  - 税込み価格計算ロジック
  - 在庫状態管理（在庫あり、残りわずか、在庫切れ）
  - カート機能（追加、数量管理、LocalStorage永続化）
  - 非同期処理（async/await）
  - エラーハンドリング
  - ローディング表示
  - アクセシビリティ対応（aria-live, role属性）
  - 画像の遅延読み込み（loading="lazy"）
  - レスポンシブ商品グリッド

## 🛠️ 技術スタック

### 共通技術

- **HTML5**: セマンティックHTML、アクセシビリティ対応
- **CSS3**: Flexbox, Grid, CSS変数, アニメーション, レスポンシブデザイン
- **JavaScript (ES6+)**: クラス, アロー関数, const/let, テンプレートリテラル, 分割代入, async/await

### 専用技術・ライブラリ

- **GSAP 3.12.5**: 高度なアニメーションライブラリ（case3）
- **LocalStorage API**: ブラウザストレージ（case2, case7）
- **Google Fonts**: Noto Sans JP（case7）

## 📝 コーディング規約

### JavaScript

- **命名規則**:
  - 定数: `UPPER_SNAKE_CASE`（例: `TAX_RATE`, `BASE_URL`）
  - 関数・変数: `camelCase`（例: `calculatePrice`, `userName`）
  - クラス: `PascalCase`（例: `TodoApp`）
  - プライベートメソッド: `_privateMethod`（アンダースコアプレフィックス）

- **関数スタイル**:
  - アロー関数を優先（`const func = () => {}`）
  - 純粋関数を心がける（副作用を最小限に）
  - 適切なJSDocコメントを追加

- **モダンな構文**:
  - `const`/`let`を使用（`var`は使用しない）
  - テンプレートリテラルを活用
  - 分割代入を積極的に使用
  - オプショナルチェーン（`?.`）の活用

### CSS

- **命名規則**:
  - BEM規則を推奨（Block__Element--Modifier）
  - 例: `.button`, `.button__icon`, `.button--primary`

- **スタイルガイド**:
  - CSS変数で色・サイズ・スペーシングを管理
  - モバイルファースト設計
  - セマンティックなクラス名
  - 適切なコメント区切り

### HTML

- **ベストプラクティス**:
  - セマンティックHTMLタグを使用
  - アクセシビリティ属性（aria-*, role）を適切に配置
  - 画像にはalt属性を必ず記載
  - フォーム要素にはlabelを関連付け

## 🎨 デザインシステム（case6参照）

### カラーパレット

```css
--color-primary: #3b82f6;        /* プライマリカラー */
--color-secondary: #6b7280;      /* セカンダリカラー */
--color-success: #10b981;        /* 成功状態 */
--color-danger: #ef4444;         /* 危険状態 */
--color-white: #ffffff;          /* 白 */
--color-text-dark: #1f2937;      /* テキスト色 */
```

### スペーシング

```css
--spacing-sm: 0.5rem;   /* 8px */
--spacing-md: 1rem;     /* 16px */
--spacing-lg: 1.5rem;   /* 24px */
```

### フォントサイズ

```css
--font-size-sm: 0.875rem;   /* 14px */
--font-size-md: 1rem;       /* 16px */
--font-size-lg: 1.125rem;   /* 18px */
```

## 🚀 学習の進め方

### 推奨学習順序

1. **Case 1** → HTML/CSSの基礎を固める
2. **Case 4** → JavaScriptの基本的なループと配列操作を理解
3. **Case 5** → 保守性の高いコード設計を学ぶ
4. **Case 2** → クラスとCRUD操作、LocalStorageを習得
5. **Case 6** → CSS変数とコンポーネント設計を学ぶ
6. **Case 3** → アニメーションライブラリの使い方を理解
7. **Case 7** → 実践的なECサイト機能を実装

### 学習のポイント

- **各caseを実際に動かしてみる**: ブラウザで開いて動作を確認
- **コードを読み解く**: コメントを参考に処理の流れを理解
- **改造してみる**: 機能追加や仕様変更にチャレンジ
- **デバッグツールを活用**: Chrome DevToolsで変数の中身を確認
- **段階的に学習**: 簡単なcaseから始めて徐々にレベルアップ

### 発展課題

#### Case 2（ToDoアプリ）
- [ ] 優先度設定機能の追加
- [ ] 期限設定機能の追加
- [ ] カテゴリ分類機能の追加
- [ ] ドラッグ&ドロップによる並び替え

#### Case 3（アニメーション）
- [ ] スクロールトリガーアニメーションの追加
- [ ] パララックス効果の実装
- [ ] 独自のアニメーションパターンの作成

#### Case 7（ECサイト）
- [ ] 商品検索機能の実装
- [ ] カートページの作成
- [ ] 商品詳細ページの追加
- [ ] お気に入り機能の実装
- [ ] 価格でのソート・フィルター機能

## 📚 参考リソース

### 公式ドキュメント
- [MDN Web Docs](https://developer.mozilla.org/) - HTML/CSS/JavaScript完全リファレンス
- [GSAP Documentation](https://greensock.com/docs/) - GSAPアニメーションライブラリ
- [Web.dev](https://web.dev/) - Google提供のWeb開発ガイド

### CSS設計
- [BEM Methodology](https://en.bem.info/) - BEM命名規則
- [CSS-Tricks](https://css-tricks.com/) - CSSテクニック集

### JavaScript
- [JavaScript.info](https://javascript.info/) - モダンJavaScriptチュートリアル
- [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) - JavaScript深掘りシリーズ

## 📋 開発環境

### 必要なもの
- モダンブラウザ（Chrome, Firefox, Safari, Edge最新版）
- テキストエディタ（VS Code, Cursor推奨）
- ローカルサーバー（Live Server拡張機能など）

### 推奨VS Code拡張機能
- Live Server - ローカル開発サーバー
- Prettier - コードフォーマッター
- ESLint - JavaScriptリンター
- Auto Rename Tag - HTMLタグ自動リネーム

## 🎯 このプロジェクトで学べること

✅ HTML5のセマンティックな構造設計  
✅ CSS3の最新機能（Grid, Flexbox, 変数, アニメーション）  
✅ ES6+のモダンなJavaScript構文  
✅ クラスベースのアプリケーション設計  
✅ LocalStorageを使ったデータ永続化  
✅ 非同期処理（async/await）  
✅ イベントハンドリングとイベント委譲  
✅ アニメーションライブラリの活用  
✅ レスポンシブデザインの実装  
✅ アクセシビリティ対応  
✅ 保守性の高いコード設計  
✅ 実践的なECサイト機能の実装

---

**Happy Coding! 🚀**

質問や改善提案があれば、お気軽にIssueを作成してください。
