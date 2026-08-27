---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "{@link GraphicElement} コレクションを表します。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

{@link GraphicElement} コレクションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | 新しいコレクションを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | 新しい {@link GraphicElement} をコレクションに追加します。コレクション内のすべての項目は同じ {@code GraphicElement.Parent}({@link GraphicElement#getParent}) を持つ必要があります。 |
| [clear](#clear--) | コレクションをクリアします。 |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | 要素がコレクションに含まれているかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | 対象配列の指定インデックスから開始して、互換性のある一次元配列にコレクション全体をコピーします。 |
| [get_Item](#get_Item-int-) | 指定されたインデックスの {@link GraphicElement} 要素を取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。常に false を返します。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | コレクション全体の列挙子を返します。 |
| [iterator](#iterator--) | コレクション全体の列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) |  {@link GraphicElement} 要素を削除します。 |
| [size](#size--) | コレクションに実際に含まれる {@link GraphicElement} オブジェクト要素の数を取得します。 |
| [toList](#toList--) | 制限のない列挙のために内部コレクションを返します。 |
| [toString](#toString--) | このコレクションの文字列表現を取得します。 |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

新しいコレクションを初期化します。

### add {#add-com.aspose.pdf.vector.GraphicElement-}
新しい {@link GraphicElement} をコレクションに追加します。コレクション内のすべての項目は同じ {@code GraphicElement.Parent}({@link GraphicElement#getParent}) を持つ必要があります。

### clear {#clear--}
```
public final void clear()
```

コレクションをクリアします。

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
要素がコレクションに含まれているかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
対象配列の指定インデックスから開始して、互換性のある一次元配列にコレクション全体をコピーします。

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

指定されたインデックスの {@link GraphicElement} 要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | コレクション内のインデックス。 |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。常に false を返します。

**Returns:**
ブール値

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

コレクション全体の列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

コレクション全体の列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
 {@link GraphicElement} 要素を削除します。

### size {#size--}
```
public final int size()
```

コレクションに実際に含まれる {@link GraphicElement} オブジェクト要素の数を取得します。

**Returns:**
int 値です。

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

制限のない列挙のために内部コレクションを返します。

**Returns:**
内部リスト

### toString {#toString--}
```
public String toString()
```

このコレクションの文字列表現を取得します。

**Returns:**
文字列です。
