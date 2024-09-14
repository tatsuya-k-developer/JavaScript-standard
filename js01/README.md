# JavaScriptの基礎

## 変数と定数

変っ数と定数の使い分け

基本的には定数を使う
理由
コードを読みやすくするためや予期せぬエラーを防ぐため


命名規則
```js
// 定義可能な例
let CorporateName = '株式会社〇〇';
let corporateName1 = '株式会社〇〇';
let corporateName$ = '株式会社〇〇';
let $corporateName = '株式会社〇〇';
let corporate_Name = '株式会社〇〇';
let _corporateName = '株式会社〇〇';
let 法人名 = '株式会社〇〇';

// 定義不可の例
let 1corporateName = '株式会社〇〇';
let const = '株式会社〇〇';
let corporate Name = '株式会社〇〇';


// 良い例
// キャメルケース（JavaScriptで一番使われている命名規則）
let corporateName = '株式会社〇〇';
```
