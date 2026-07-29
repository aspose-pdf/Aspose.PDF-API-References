---
title: "AnnotationActionCollection"
linktitle: "AnnotationActionCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "アノテーションアクションのコレクションを表します。"
type: docs
weight: 70
url: /ja/java/com.aspose.pdf/annotationactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseActionCollection com.aspose.pdf.AnnotationActionCollection, com.aspose.pdf.BaseActionCollection, com.aspose.pdf.AnnotationActionCollection

```
public final class AnnotationActionCollection extends BaseActionCollection
```

アノテーションアクションのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOnCalculate](#getOnCalculate--) | フィールド値を計算するアクションを取得します。 |
| [getOnClosePage](#getOnClosePage--) | アノテーションを含むページが閉じられたときに実行されるアクションを取得します。 |
| [getOnEnter](#getOnEnter--) | カーソルがアノテーションのアクティブ領域に入ったときに実行されるアクションを取得します。 |
| [getOnExit](#getOnExit--) | カーソルがアノテーションのアクティブ領域から出たときに実行されるアクションを取得します。 |
| [getOnFormat](#getOnFormat--) | フィールド値をフォーマットするために実行されるアクションを取得します。 |
| [getOnHidePage](#getOnHidePage--) | アノテーションを含むページがビューアアプリケーションのユーザーインターフェイスで表示されなくなったときに実行されるアクションを取得します。 |
| [getOnLostFocus](#getOnLostFocus--) | アノテーションが入力フォーカスを失ったときに実行されるアクションを取得します。 |
| [getOnModifyCharacter](#getOnModifyCharacter--) | ユーザーがフィールドの文字を変更したときに実行されるアクションを取得します。 |
| [getOnOpenPage](#getOnOpenPage--) | アノテーションを含むページが開かれたときに実行されるアクションを取得します。 |
| [getOnPressMouseBtn](#getOnPressMouseBtn--) | マウスボタンがアノテーションのアクティブ領域内で押されたときに実行されるアクションを取得します。 |
| [getOnReceiveFocus](#getOnReceiveFocus--) | アノテーションが入力フォーカスを受け取ったときに実行されるアクションを取得します。 |
| [getOnReleaseMouseBtn](#getOnReleaseMouseBtn--) | マウスボタンがアノテーションのアクティブ領域内で離されたときに実行されるアクションを取得します。 |
| [getOnShowPage](#getOnShowPage--) | アノテーションを含むページがビューアアプリケーションのユーザーインターフェイスで表示されるようになったときに実行されるアクションを取得します。 |
| [getOnValidate](#getOnValidate--) | ユーザーがフィールドの内容を変更したときに実行されるアクションを取得します。 |
| [setOnCalculate](#setOnCalculate-com.aspose.pdf.PdfAction-) | フィールド値を計算するアクションを設定します。 |
| [setOnClosePage](#setOnClosePage-com.aspose.pdf.PdfAction-) | 注釈が含まれるページが閉じられたときに実行されるアクションを設定します。 |
| [setOnEnter](#setOnEnter-com.aspose.pdf.PdfAction-) | カーソルが注釈のアクティブ領域に入ったときに実行されるアクションを設定します。 |
| [setOnExit](#setOnExit-com.aspose.pdf.PdfAction-) | カーソルが注釈のアクティブ領域から出たときに実行されるアクションを設定します。 |
| [setOnFormat](#setOnFormat-com.aspose.pdf.PdfAction-) | フィールド値をフォーマットするアクションを設定します。 |
| [setOnHidePage](#setOnHidePage-com.aspose.pdf.PdfAction-) | 注釈が含まれるページがビューアアプリケーションのユーザーインターフェイスで表示されなくなったときに実行されるアクションを設定します。 |
| [setOnLostFocus](#setOnLostFocus-com.aspose.pdf.PdfAction-) | 注釈が入力フォーカスを失ったときに実行されるアクションを設定します。 |
| [setOnModifyCharacter](#setOnModifyCharacter-com.aspose.pdf.PdfAction-) | ユーザーがフィールドの文字を変更したときに実行されるアクションを設定します。 |
| [setOnOpenPage](#setOnOpenPage-com.aspose.pdf.PdfAction-) | 注釈が含まれるページが開かれたときに実行されるアクションを設定します。 |
| [setOnPressMouseBtn](#setOnPressMouseBtn-com.aspose.pdf.PdfAction-) | マウスボタンが注釈のアクティブ領域内で押されたときに実行されるアクションを設定します。 |
| [setOnReceiveFocus](#setOnReceiveFocus-com.aspose.pdf.PdfAction-) | 注釈が入力フォーカスを受け取ったときに実行されるアクションを設定します。 |
| [setOnReleaseMouseBtn](#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-) | マウスボタンが注釈のアクティブ領域内で離されたときに実行されるアクションを設定します。 |
| [setOnShowPage](#setOnShowPage-com.aspose.pdf.PdfAction-) | 注釈が含まれるページがビューアアプリケーションのユーザーインターフェイスで表示されたときに実行されるアクションを設定します。 |
| [setOnValidate](#setOnValidate-com.aspose.pdf.PdfAction-) | ユーザーがフィールドの内容を変更したときに実行されるアクションを設定します。 |

### getOnCalculate {#getOnCalculate--}
```
public PdfAction getOnCalculate()
```

フィールド値を計算するアクションを取得します。

**Returns:**
フィールド値を計算するアクション。

### getOnClosePage {#getOnClosePage--}
```
public PdfAction getOnClosePage()
```

アノテーションを含むページが閉じられたときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnEnter {#getOnEnter--}
```
public PdfAction getOnEnter()
```

カーソルがアノテーションのアクティブ領域に入ったときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnExit {#getOnExit--}
```
public PdfAction getOnExit()
```

カーソルがアノテーションのアクティブ領域から出たときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnFormat {#getOnFormat--}
```
public PdfAction getOnFormat()
```

フィールド値をフォーマットするために実行されるアクションを取得します。

**Returns:**
フィールド値をフォーマットするために実行されるアクション。

### getOnHidePage {#getOnHidePage--}
```
public PdfAction getOnHidePage()
```

アノテーションを含むページがビューアアプリケーションのユーザーインターフェイスで表示されなくなったときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnLostFocus {#getOnLostFocus--}
```
public PdfAction getOnLostFocus()
```

アノテーションが入力フォーカスを失ったときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnModifyCharacter {#getOnModifyCharacter--}
```
public PdfAction getOnModifyCharacter()
```

ユーザーがフィールドの文字を変更したときに実行されるアクションを取得します。

**Returns:**
ユーザーがフィールドの文字を変更したときに実行されるアクション。

### getOnOpenPage {#getOnOpenPage--}
```
public PdfAction getOnOpenPage()
```

アノテーションを含むページが開かれたときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnPressMouseBtn {#getOnPressMouseBtn--}
```
public PdfAction getOnPressMouseBtn()
```

マウスボタンがアノテーションのアクティブ領域内で押されたときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnReceiveFocus {#getOnReceiveFocus--}
```
public PdfAction getOnReceiveFocus()
```

アノテーションが入力フォーカスを受け取ったときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnReleaseMouseBtn {#getOnReleaseMouseBtn--}
```
public PdfAction getOnReleaseMouseBtn()
```

マウスボタンがアノテーションのアクティブ領域内で離されたときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnShowPage {#getOnShowPage--}
```
public PdfAction getOnShowPage()
```

アノテーションを含むページがビューアアプリケーションのユーザーインターフェイスで表示されるようになったときに実行されるアクションを取得します。

**Returns:**
PdfAction オブジェクト

### getOnValidate {#getOnValidate--}
```
public PdfAction getOnValidate()
```

ユーザーがフィールドの内容を変更したときに実行されるアクションを取得します。

**Returns:**
ユーザーがフィールドの内容を変更したときに実行されるアクション。

### setOnCalculate {#setOnCalculate-com.aspose.pdf.PdfAction-}
フィールド値を計算するアクションを設定します。

### setOnClosePage {#setOnClosePage-com.aspose.pdf.PdfAction-}
注釈が含まれるページが閉じられたときに実行されるアクションを設定します。

### setOnEnter {#setOnEnter-com.aspose.pdf.PdfAction-}
カーソルが注釈のアクティブ領域に入ったときに実行されるアクションを設定します。

### setOnExit {#setOnExit-com.aspose.pdf.PdfAction-}
カーソルが注釈のアクティブ領域から出たときに実行されるアクションを設定します。

### setOnFormat {#setOnFormat-com.aspose.pdf.PdfAction-}
フィールド値をフォーマットするアクションを設定します。

### setOnHidePage {#setOnHidePage-com.aspose.pdf.PdfAction-}
注釈が含まれるページがビューアアプリケーションのユーザーインターフェイスで表示されなくなったときに実行されるアクションを設定します。

### setOnLostFocus {#setOnLostFocus-com.aspose.pdf.PdfAction-}
注釈が入力フォーカスを失ったときに実行されるアクションを設定します。

### setOnModifyCharacter {#setOnModifyCharacter-com.aspose.pdf.PdfAction-}
ユーザーがフィールドの文字を変更したときに実行されるアクションを設定します。

### setOnOpenPage {#setOnOpenPage-com.aspose.pdf.PdfAction-}
注釈が含まれるページが開かれたときに実行されるアクションを設定します。

### setOnPressMouseBtn {#setOnPressMouseBtn-com.aspose.pdf.PdfAction-}
マウスボタンが注釈のアクティブ領域内で押されたときに実行されるアクションを設定します。

### setOnReceiveFocus {#setOnReceiveFocus-com.aspose.pdf.PdfAction-}
注釈が入力フォーカスを受け取ったときに実行されるアクションを設定します。

### setOnReleaseMouseBtn {#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-}
マウスボタンが注釈のアクティブ領域内で離されたときに実行されるアクションを設定します。

### setOnShowPage {#setOnShowPage-com.aspose.pdf.PdfAction-}
注釈が含まれるページがビューアアプリケーションのユーザーインターフェイスで表示されたときに実行されるアクションを設定します。

### setOnValidate {#setOnValidate-com.aspose.pdf.PdfAction-}
ユーザーがフィールドの内容を変更したときに実行されるアクションを設定します。
