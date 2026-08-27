---
title: "TextParagraphCollection"
linktitle: "TextParagraphCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキスト段落コレクションを表します"
type: docs
weight: 5230
url: /ja/java/com.aspose.pdf/textparagraphcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraphCollection

**All Implemented Interfaces:**
Iterable < TextParagraph >

```
public final class TextParagraphCollection extends Object implements Iterable < TextParagraph >
```

テキスト段落コレクションを表します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.TextParagraph-) | 指定されたインデックスにテキスト段落要素を追加します。 |
| [clear](#clear--) | コレクションからすべての項目をクリアします。 |
| [contains](#contains-com.aspose.pdf.TextParagraph-) | コレクションが特定の値を含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.TextParagraph:A-int-) | コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。 |
| [get_Item](#get_Item-int-) | 指定されたインデックスのテキスト段落要素を取得します。 |
| [getSyncRoot](#getSyncRoot--) | コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します |
| [isSynchronized](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator](#iterator--) | コレクション全体の列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.TextParagraph-) | コレクションから指定された項目を削除します。 |
| [size](#size--) | コレクションに実際に含まれる {@code TextParagraph} オブジェクト要素の数を取得します。 |

### add {#add-com.aspose.pdf.TextParagraph-}
指定されたインデックスにテキスト段落要素を追加します。

### clear {#clear--}
```
public void clear()
```

コレクションからすべての項目をクリアします。

### contains {#contains-com.aspose.pdf.TextParagraph-}
コレクションが特定の値を含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.TextParagraph:A-int-}
コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。

### get_Item {#get_Item-int-}
```
public TextParagraph get_Item(int index)
```

指定されたインデックスのテキスト段落要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | int 値です。 |

**Returns:**
TextParagraph オブジェクト

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。

**Returns:**
オブジェクト要素

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< TextParagraph > iterator()
```

コレクション全体の列挙子を返します。

**Returns:**
IEnumerator オブジェクト

### remove {#remove-com.aspose.pdf.TextParagraph-}
コレクションから指定された項目を削除します。

### size {#size--}
```
public int size()
```

コレクションに実際に含まれる {@code TextParagraph} オブジェクト要素の数を取得します。

**Returns:**
int 値です。
