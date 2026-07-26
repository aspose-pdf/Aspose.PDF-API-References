---
title: "ListBoxField"
linktitle: "ListBoxField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスは ListBox フィールドを表します。"
type: docs
weight: 2770
url: /ja/java/com.aspose.pdf/listboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField com.aspose.pdf.ListBoxField, com.aspose.pdf.ChoiceField, com.aspose.pdf.ListBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class ListBoxField extends ChoiceField
```

クラスは ListBox フィールドを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ListBoxField](#ListBoxField--) | Generatorで使用されるListBoxFieldのコンストラクタです。 |
| [ListBoxField](#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Generatorで使用されるListBoxFieldのコンストラクタです。 |
| [ListBoxField](#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Generatorで使用されるListBoxFieldのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTopIndex](#getTopIndex--) | リストの最上部に表示されている要素のインデックスを取得します。 |
| [setSelected](#setSelected-int-) | 選択された項目のインデックスを取得します。項目は1から番号付けされます。 |
| [setSelectedItems](#setSelectedItems-int:A-) | マルチセレクトリストで選択された項目の配列を設定します。シングルセレクトリストの場合は、単一項目の配列を返します。 |
| [setTopIndex](#setTopIndex-int-) | リストの最上部に表示されている要素のインデックスを設定します。 |

### ListBoxField {#ListBoxField--}
```
public ListBoxField()
```

Generatorで使用されるListBoxFieldのコンストラクタです。

### ListBoxField {#ListBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Generatorで使用されるListBoxFieldのコンストラクタです。

### ListBoxField {#ListBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Generatorで使用されるListBoxFieldのコンストラクタです。

### getTopIndex {#getTopIndex--}
```
public int getTopIndex()
```

リストの最上部に表示されている要素のインデックスを取得します。

**Returns:**
int 値です。

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

選択された項目のインデックスを取得します。項目は1から番号付けされます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

マルチセレクトリストで選択された項目の配列を設定します。シングルセレクトリストの場合は、単一項目の配列を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値の配列 |

### setTopIndex {#setTopIndex-int-}
```
public void setTopIndex(int value)
```

リストの最上部に表示されている要素のインデックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
