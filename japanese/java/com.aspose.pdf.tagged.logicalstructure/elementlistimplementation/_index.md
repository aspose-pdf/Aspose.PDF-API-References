---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description:
type: docs
weight: 50
url: /ja/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | 要素をリストに追加します。 |
| [getCount](#getCount--) | ElementList の要素数を取得します。 |
| [item](#item-int-) | 指定されたインデックスの要素を取得します。 |
| [iterator](#iterator--) | 要素コレクションを反復処理する列挙子を取得します。 |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
要素をリストに追加します。

### getCount {#getCount--}
```
public int getCount()
```

ElementList の要素数を取得します。

**Returns:**
int 値です。

### item {#item-int-}
```
public Element item(int index)
```

指定されたインデックスの要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  |  |

**Returns:**
コレクション内で指定されたインデックスを持つ /Aspose.Pdf.LogicalStructure.Element。インデックスがリストの要素数以上の場合、null を返します。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

要素コレクションを反復処理する列挙子を取得します。

**Returns:**
要素コレクションを反復処理するために使用される列挙子。
