---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスはアクションのリストを記述します。"
type: docs
weight: 3680
url: /ja/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

クラスはアクションのリストを記述します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | アクションリストにアクションを追加します。 |
| [delete](#delete-int-) | インデックスでアクションを削除します。 |
| [get_Item](#get_Item-int-) | インデックスでアクションを取得します。 |
| [getCount](#getCount--) | アクションの数を取得します。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | 内部メソッド |
| [iterator](#iterator--) | 列挙子を取得します。 |

### add {#add-com.aspose.pdf.PdfAction-}
アクションリストにアクションを追加します。

### delete {#delete-int-}
```
public void delete(int index)
```

インデックスでアクションを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除するアクションのインデックス。 |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

インデックスでアクションを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | アクションのインデックス値。 |

**Returns:**
PdfAction のインデックスが見つかった場合はそのインデックスを返します。見つからない場合は @throws IndexOutOfRangeException IndexOutOfRangeException をスローします。

### getCount {#getCount--}
```
public int getCount()
```

アクションの数を取得します。

**Returns:**
int 値です。

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

内部メソッド

**Returns:**
内部オブジェクト。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

列挙子を取得します。

**Returns:**
PDfAction 列挙子。
