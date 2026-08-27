---
title: "TextSegmentCollection"
linktitle: "TextSegmentCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストセグメントコレクションを表します"
type: docs
weight: 5310
url: /ja/java/com.aspose.pdf/textsegmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegmentCollection

**All Implemented Interfaces:**
Iterable < TextSegment >

```
public final class TextSegmentCollection extends Object implements Iterable < TextSegment >
```

テキストセグメントコレクションを表します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.TextSegment-) | 指定されたインデックスにテキストセグメント要素を追加します。 |
| [clear](#clear--) | コレクションからすべての項目をクリアします。 |
| [contains](#contains-com.aspose.pdf.TextSegment-) | コレクションが特定の値を含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.TextSegment:A-int-) | コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。 |
| [delete](#delete-int-) | 指定されたインデックスのテキストセグメント要素を削除します。 |
| [get_Item](#get_Item-int-) | 指定されたインデックスのテキストセグメント要素を取得します。 |
| [getSyncRoot](#getSyncRoot--) | コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します |
| [isSynchronized](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator](#iterator--) | コレクション全体の列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.TextSegment-) | コレクションから指定された項目を削除します。 |
| [size](#size--) | コレクションに実際に含まれている {@code TextSegment} オブジェクト要素の数を取得します。 |

### add {#add-com.aspose.pdf.TextSegment-}
指定されたインデックスにテキストセグメント要素を追加します。

### clear {#clear--}
```
public void clear()
```

コレクションからすべての項目をクリアします。

### contains {#contains-com.aspose.pdf.TextSegment-}
コレクションが特定の値を含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.TextSegment:A-int-}
コレクション全体を互換性のある一次元配列にコピーし、対象配列の指定されたインデックスから開始します。

### delete {#delete-int-}
```
public void delete(int index)
```

指定されたインデックスのテキストセグメント要素を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | int 値です。 |

### get_Item {#get_Item-int-}
```
public TextSegment get_Item(int index)
```

指定されたインデックスのテキストセグメント要素を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | コレクション内のインデックス。 |

**Returns:**
TextSegment オブジェクト。

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
public Iterator < TextSegment > iterator()
```

コレクション全体の列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### remove {#remove-com.aspose.pdf.TextSegment-}
コレクションから指定された項目を削除します。

### size {#size--}
```
public int size()
```

コレクションに実際に含まれている {@code TextSegment} オブジェクト要素の数を取得します。

**Returns:**
int 値です。
