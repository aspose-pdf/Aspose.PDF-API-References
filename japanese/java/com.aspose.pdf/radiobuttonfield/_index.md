---
title: "RadioButtonField"
linktitle: "RadioButtonField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ラジオボタン フィールドを表すクラスです。"
type: docs
weight: 4080
url: /ja/java/com.aspose.pdf/radiobuttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.RadioButtonField, com.aspose.pdf.ChoiceField, com.aspose.pdf.RadioButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class RadioButtonField extends ChoiceField
```

ラジオボタン フィールドを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.IDocument-) | RadioButtonField のコンストラクタ。 |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-) | RadiouttonField のコンストラクタ。 |
| [RadioButtonField](#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ラジオボタンフィールドを設定します |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.RadioButtonOptionField-) | RadioButton フィールドに新しいオプションフィールドを追加します |
| [addOption](#addOption-java.lang.String-) | radion ボタンにオプションを追加します。 |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | 指定された矩形でラジオボタンのオプションを追加します。 |
| [getNoToggleToOff](#getNoToggleToOff--) | <p> ラジオボタンが選択されていない状態を許可するフラグを取得または設定します。{@code } の場合、常に正確に1つのラジオボタンが選択されている必要があり、現在選択されているボタンを選択しても効果がありません。{@code } の場合、選択されたボタンをクリックすると選択が解除され、ボタンが選択されていない状態になります。 </p> <hr> 一部の PDF リーダー（Adobe Acrobat を含む）はこのフラグの状態を無視する可能性があります。 |
| [getOptions](#getOptions--) | ラジオボタンのオプションのコレクションを取得します。 |
| [getPageIndex](#getPageIndex--) | この RadioButton フィールドを含むページのインデックスを取得します。 |
| [getSelected](#getSelected--) | 選択された項目のインデックスを取得します。項目の番号付けは 1 から開始されます。 |
| [getStyle](#getStyle--) | フィールドボックスのスタイル。 |
| [getValue](#getValue--) | フィールドの値を取得します。 |
| [setNoToggleToOff](#setNoToggleToOff-boolean-) | <p> ラジオボタンが選択されていない状態を許可するフラグを取得または設定します。{@code } の場合、常に正確に1つのラジオボタンが選択されている必要があり、現在選択されているボタンを選択しても効果がありません。{@code } の場合、選択されたボタンをクリックすると選択が解除され、ボタンが選択されていない状態になります。 </p> <hr> 一部の PDF リーダー（Adobe Acrobat を含む）はこのフラグの状態を無視する可能性があります。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | ラジオボタンのすべてのサブアイテムをページ上の指定された位置に移動します。 |
| [setSelected](#setSelected-int-) | 選択された項目のインデックスを設定します。項目の番号付けは 1 から開始されます。 |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | フィールドボックスのスタイル。 |
| [setValue](#setValue-java.lang.String-) | フィールドの値を設定します。 |
| [updateAppearances](#updateAppearances--) | 外観の値を更新します。 |

### RadioButtonField {#RadioButtonField-com.aspose.pdf.IDocument-}
RadioButtonField のコンストラクタ。

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-}
RadiouttonField のコンストラクタ。

### RadioButtonField {#RadioButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ラジオボタンフィールドを設定します

### add {#add-com.aspose.pdf.RadioButtonOptionField-}
RadioButton フィールドに新しいオプションフィールドを追加します

### addOption {#addOption-java.lang.String-}
radion ボタンにオプションを追加します。

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
指定された矩形でラジオボタンのオプションを追加します。

### getNoToggleToOff {#getNoToggleToOff--}
```
public final boolean getNoToggleToOff()
```

<p> ラジオボタンが選択されていない状態を許可するフラグを取得または設定します。{@code } の場合、常に正確に1つのラジオボタンが選択されている必要があり、現在選択されているボタンを選択しても効果がありません。{@code } の場合、選択されたボタンをクリックすると選択が解除され、ボタンが選択されていない状態になります。 </p> <hr> 一部の PDF リーダー（Adobe Acrobat を含む）はこのフラグの状態を無視する可能性があります。

**Returns:**
ブール値

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

ラジオボタンのオプションのコレクションを取得します。

**Returns:**
OptionCollection オブジェクト

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

この RadioButton フィールドを含むページのインデックスを取得します。

**Returns:**
int 値です。

### getSelected {#getSelected--}
```
public int getSelected()
```

選択された項目のインデックスを取得します。項目の番号付けは 1 から開始されます。

**Returns:**
int 値です。

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

フィールドボックスのスタイル。

**Returns:**
BoxStyle の値 @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

フィールドの値を取得します。

**Returns:**
文字列値

### setNoToggleToOff {#setNoToggleToOff-boolean-}
```
public final void setNoToggleToOff(boolean value)
```

<p> ラジオボタンが選択されていない状態を許可するフラグを取得または設定します。{@code } の場合、常に正確に1つのラジオボタンが選択されている必要があり、現在選択されているボタンを選択しても効果がありません。{@code } の場合、選択されたボタンをクリックすると選択が解除され、ボタンが選択されていない状態になります。 </p> <hr> 一部の PDF リーダー（Adobe Acrobat を含む）はこのフラグの状態を無視する可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPosition {#setPosition-com.aspose.pdf.Point-}
ラジオボタンのすべてのサブアイテムをページ上の指定された位置に移動します。

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

選択された項目のインデックスを設定します。項目の番号付けは 1 から開始されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
フィールドボックスのスタイル。

### setValue {#setValue-java.lang.String-}
フィールドの値を設定します。

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

外観の値を更新します。
