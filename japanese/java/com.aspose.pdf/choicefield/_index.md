---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "選択フィールドの基底クラスを表します。"
type: docs
weight: 590
url: /ja/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

選択フィールドの基底クラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | 選択フィールドを作成します（Generator 用） |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | ChoiceField のコンストラクタです。 |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ChoiceField のコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | 指定された名前で新しいオプションを追加します。 |
| [addOption](#addOption-java.lang.String-java.lang.String-) | 指定されたエクスポート値と名前で新しいオプションを追加します。 |
| [deleteOption](#deleteOption-java.lang.String-) | 名前でオプションを削除します。 |
| [getCommitImmediately](#getCommitImmediately--) | 選択変更時にコミットするフラグを取得します。 |
| [getMultiSelect](#getMultiSelect--) | マルチ選択フラグを取得します。 |
| [getOptions](#getOptions--) | 選択肢のコレクションを取得します。 |
| [getSelected](#getSelected--) | 選択されたオプションのインデックスを取得します。このプロパティは選択を変更できます。 |
| [getSelectedItems](#getSelectedItems--) | 選択された項目の配列を設定します。マルチ選択リストの場合、配列には複数の項目が含まれます。単一選択リストの場合、単一の項目が含まれます。 |
| [getValue](#getValue--) | フィールドの値を取得します。 |
| [setCommitImmediately](#setCommitImmediately-boolean-) | 選択変更時にコミットするフラグを設定します。 |
| [setMultiSelect](#setMultiSelect-boolean-) | マルチ選択フラグを設定します。 |
| [setOptions](#setOptions-java.util.List-) | 利用可能なオプションを、options パラメータで指定された名前のオプションに置き換えます。 |
| [setSelected](#setSelected-int-) | 選択されたオプションのインデックスを設定します。このプロパティは選択を変更できます。 |
| [setSelectedItems](#setSelectedItems-int:A-) | 選択された項目の配列を設定します。マルチ選択リストの場合、配列には複数の項目が含まれます。単一選択リストの場合、単一の項目が含まれます。 |
| [setValue](#setValue-java.lang.String-) | フィールドの値を設定します。 |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
選択フィールドを作成します（Generator 用）

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
ChoiceField のコンストラクタです。

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ChoiceField のコンストラクタです。

### addOption {#addOption-java.lang.String-}
指定された名前で新しいオプションを追加します。

### addOption {#addOption-java.lang.String-java.lang.String-}
指定されたエクスポート値と名前で新しいオプションを追加します。

### deleteOption {#deleteOption-java.lang.String-}
名前でオプションを削除します。

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

選択変更時にコミットするフラグを取得します。

**Returns:**
ブール値

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

マルチ選択フラグを取得します。

**Returns:**
ブール値

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

選択肢のコレクションを取得します。

**Returns:**
OptionCollection オブジェクト

### getSelected {#getSelected--}
```
public int getSelected()
```

選択されたオプションのインデックスを取得します。このプロパティは選択を変更できます。

**Returns:**
int 値です。

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

選択された項目の配列を設定します。マルチ選択リストの場合、配列には複数の項目が含まれます。単一選択リストの場合、単一の項目が含まれます。

**Returns:**
int 値の配列

### getValue {#getValue--}
```
public String getValue()
```

フィールドの値を取得します。

**Returns:**
文字列値

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

選択変更時にコミットするフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

マルチ選択フラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setOptions {#setOptions-java.util.List-}
利用可能なオプションを、options パラメータで指定された名前のオプションに置き換えます。

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

選択されたオプションのインデックスを設定します。このプロパティは選択を変更できます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

選択された項目の配列を設定します。マルチ選択リストの場合、配列には複数の項目が含まれます。単一選択リストの場合、単一の項目が含まれます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値の配列 |

### setValue {#setValue-java.lang.String-}
フィールドの値を設定します。
