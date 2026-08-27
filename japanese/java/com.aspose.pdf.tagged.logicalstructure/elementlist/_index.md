---
title: "ElementList"
linktitle: "ElementList"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "要素の順序付きコレクションを表す。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

要素の順序付きコレクションを表す。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | 要素をリストに追加します。 |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | ElementList の要素数を取得します。 |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | 要素をリストに挿入します。 |
| [item](#item-int-) | 指定されたインデックスの要素を取得します。 |
| [iterator](#iterator--) | 要素コレクションを反復処理する列挙子を取得します。 |
| [removeAt](#removeAt-int-) | リストから要素を削除します。 |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | リストから要素を削除します。 |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
要素をリストに追加します。

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

ElementList の要素数を取得します。

**Returns:**
int 値です。

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
要素をリストに挿入します。

### item {#item-int-}
```
public abstract Element item(int index)
```

指定されたインデックスの要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 要素リストへのインデックスです。 |

**Returns:**
コレクション内で指定されたインデックスを持つ {@code /Aspose.Pdf.LogicalStructure.Element}。{@code index} がリスト内の要素数以上の場合、null を返します。

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

要素コレクションを反復処理する列挙子を取得します。

**Returns:**
要素コレクションを反復処理するために使用される列挙子。

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

リストから要素を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除するインデックス。 |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
リストから要素を削除します。
