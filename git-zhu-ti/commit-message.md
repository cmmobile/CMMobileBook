---
description: 一個好的Commit Message，可以幫助審核和增加程式碼的可維護性。
---

# Commit Message 規則

## 什麼是Commit Message?

Commit Message為推送紀錄的訊息，請務必確實填寫每次程式的更動項目。

## Conventional Commits\(常規Commit守則\)\([Link](https://www.conventionalcommits.org/en/v1.0.0/)\) <a id="conventional-commits-100"></a>

## Commit Message Style\(Angular風格\)\([Link](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines)\)

```text
type(scope): subject
```

* type:
  * build\(改變建置系統或依賴\)
  * ci\(改變CI的設定\)
  * docs\(文件修改\)
  * feat\(新功能\)
  * fix\(修復Bug\)
  * perf\(優化性能\)
  * refactor\(重構\)
  * style\(CodingStyle修正\)
  * test\(新增測試\)
* scope: \(可以為空\)
  * 影響的範圍
* subject
  * 提交敘述

```text
feat: 新建立專案
feat: 新增登入頁UI
feat: 新增登入按鈕功能
fix: 修復登入邏輯參數錯誤

feat : 新增登入頁UI  <----錯誤
feat:新增登入頁UI  <----錯誤
```

