---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "チェックボックスフィールドを表すクラス"
type: docs
weight: 580
url: /ja/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

チェックボックスフィールドを表すクラス

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CheckboxField](#CheckboxField--) | CheckboxField のインスタンスを作成します。 @deprecated 完全なフィールド機能のためには、ドキュメントへのバインディングが必要です - CheckboxField(Document doc) を使用してください |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | CheckboxField のインスタンスを作成します。 @deprecated 完全なフィールド機能のためには、ドキュメントへのバインディングが必要です - CheckboxField(Document doc) を使用してください |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | CheckboxField のインスタンスを作成します。 @deprecated 完全なフィールド機能のためには、ドキュメントへのバインディングが必要です - CheckboxField(Document doc) を使用してください |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | CheckboxField のインスタンスを作成します。 @deprecated 完全なフィールド機能のためには、ドキュメントへのバインディングが必要です - CheckboxField(Document doc) を使用してください |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | チェックボックスグループに新しいチェックボックスを追加します。このグループでは、同時にチェックできるチェックボックスは最大で1つです。新しいチェックボックスはグループの下部に追加されます。 |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | チェックボックスグループに新しいチェックボックスを追加します。このグループでは、同時にチェックできるチェックボックスは最大で1つです。 |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | チェックボックスグループに新しいチェックボックスを追加します。このグループでは、同時にチェックできるチェックボックスは最大で1つです。 |
| [deepClone](#deepClone--) | チェックボックスをクローンします。 |
| [getActiveState](#getActiveState--) | 現在の注釈外観状態を取得します。 |
| [getAllowedStates](#getAllowedStates--) | 許可された状態のリストを返します。 |
| [getChecked](#getChecked--) | チェックボックスの状態を取得します。 |
| [getExportValue](#getExportValue--) | CheckBox フィールドのエクスポート値を取得または設定します。 |
| [getNormalCaption](#getNormalCaption--) | フィールドの通常キャプションを取得します。 |
| [getOnState](#getOnState--) | チェックボックスの「Checked」状態の名前を返します。これは「Yes」で、存在する場合や「Off」以外の任意の値の場合、そして「No」です; |
| [getStyle](#getStyle--) | チェックボックスのスタイルを取得します。 |
| [getValue](#getValue--) | チェックボックスフィールドの値を取得します。 |
| [setActiveState](#setActiveState-java.lang.String-) | 現在の注釈の外観状態を設定します。 |
| [setChecked](#setChecked-boolean-) | チェックボックスの状態を設定します。 |
| [setExportValue](#setExportValue-java.lang.String-) | CheckBox フィールドのエクスポート値を取得または設定します。 |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | チェックボックスのスタイルを設定します。 |
| [setValue](#setValue-java.lang.String-) | チェックボックスフィールドの値を設定します。 |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

CheckboxField のインスタンスを作成します。 @deprecated 完全なフィールド機能のためには、ドキュメントへのバインディングが必要です - CheckboxField(Document doc) を使用してください

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
CheckboxField のインスタンスを作成します。 @deprecated 完全なフィールド機能のためには、ドキュメントへのバインディングが必要です - CheckboxField(Document doc) を使用してください

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
CheckboxField のインスタンスを作成します。 @deprecated 完全なフィールド機能のためには、ドキュメントへのバインディングが必要です - CheckboxField(Document doc) を使用してください

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
CheckboxField のインスタンスを作成します。 @deprecated 完全なフィールド機能のためには、ドキュメントへのバインディングが必要です - CheckboxField(Document doc) を使用してください

### addOption {#addOption-java.lang.String-}
チェックボックスグループに新しいチェックボックスを追加します。このグループでは、同時にチェックできるチェックボックスは最大で1つです。新しいチェックボックスはグループの下部に追加されます。

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
チェックボックスグループに新しいチェックボックスを追加します。このグループでは、同時にチェックできるチェックボックスは最大で1つです。

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
チェックボックスグループに新しいチェックボックスを追加します。このグループでは、同時にチェックできるチェックボックスは最大で1つです。

### deepClone {#deepClone--}
```
public Object deepClone()
```

チェックボックスをクローンします。

**Returns:**
クローンされたオブジェクト

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

現在の注釈外観状態を取得します。

**Returns:**
文字列値

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

許可された状態のリストを返します。

**Returns:**
文字列値のリスト

### getChecked {#getChecked--}
```
public boolean getChecked()
```

チェックボックスの状態を取得します。

**Returns:**
ブール値

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

CheckBox フィールドのエクスポート値を取得または設定します。

**Returns:**
文字列値

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

フィールドの通常キャプションを取得します。

**Returns:**
文字列値

### getOnState {#getOnState--}
```
public String getOnState()
```

チェックボックスの「Checked」状態の名前を返します。これは「Yes」で、存在する場合や「Off」以外の任意の値の場合、そして「No」です;

**Returns:**
文字列値

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

チェックボックスのスタイルを取得します。

**Returns:**
チェックボックスのスタイル。 @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

チェックボックスフィールドの値を取得します。

**Returns:**
文字列値

### setActiveState {#setActiveState-java.lang.String-}
現在の注釈の外観状態を設定します。

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

チェックボックスの状態を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setExportValue {#setExportValue-java.lang.String-}
CheckBox フィールドのエクスポート値を取得または設定します。

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
チェックボックスのスタイルを設定します。

### setValue {#setValue-java.lang.String-}
チェックボックスフィールドの値を設定します。
