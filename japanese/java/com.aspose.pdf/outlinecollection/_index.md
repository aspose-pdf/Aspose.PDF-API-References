---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ドキュメントアウトライン階層を表します。"
type: docs
weight: 3260
url: /ja/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

ドキュメントアウトライン階層を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | アウトライン項目をコレクションに追加します。 |
| [clear](#clear--) | コレクションからすべての項目をクリアします。 |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | まだサポートされていません。コレクションが指定された項目を含むかどうかをチェックします。 |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | アウトライン項目を System.Array にコピーします。特定の System.Array インデックスから開始します。 |
| [delete](#delete--) | ドキュメントのアウトラインからすべての項目を削除します。 |
| [delete](#delete-java.lang.String-) | ドキュメントのアウトラインからすべての項目を削除します。 |
| [get_Item](#get_Item-int-) | インデックスでコレクションからアウトライン項目を取得します。 |
| [getFirst](#getFirst--) | アウトラインの最上位項目の最初の項目を表すアウトライン項目を取得します。 |
| [getLast](#getLast--) | アウトラインの最上位項目の最後の項目を表すアウトライン項目を取得します。 |
| [getSyncRoot](#getSyncRoot--) | このコレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [getVisibleCount](#getVisibleCount--) | Count は、すべてのレベルで表示される子孫アウトライン項目の数の合計です。注意: コレクション内の項目数を表す Count と混同しないでください。 |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [isSynchronized](#isSynchronized--) | このコレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [next](#next--) |  |
| [remove](#remove-int-) | インデックスで項目を削除します。 |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | まだサポートされていません。常に例外がスローされます。 |
| [size](#size--) | ドキュメントアウトラインのすべてのレベルにおけるアウトライン項目（ブックマーク）の総数を取得します。 |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
アウトライン項目をコレクションに追加します。

### clear {#clear--}
```
public void clear()
```

コレクションからすべての項目をクリアします。

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
まだサポートされていません。コレクションが指定された項目を含むかどうかをチェックします。

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
アウトライン項目を System.Array にコピーします。特定の System.Array インデックスから開始します。

### delete {#delete--}
```
public void delete()
```

ドキュメントのアウトラインからすべての項目を削除します。

### delete {#delete-java.lang.String-}
ドキュメントのアウトラインからすべての項目を削除します。

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

インデックスでコレクションからアウトライン項目を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 要求された項目のインデックスです。 |

**Returns:**
OutlineItemCollection オブジェクト

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

アウトラインの最上位項目の最初の項目を表すアウトライン項目を取得します。

**Returns:**
OutlineItemCollection オブジェクト

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

アウトラインの最上位項目の最後の項目を表すアウトライン項目を取得します。

**Returns:**
OutlineItemCollection オブジェクト

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

このコレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。

**Returns:**
同期用オブジェクト

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count は、すべてのレベルで表示される子孫アウトライン項目の数の合計です。注意: コレクション内の項目数を表す Count と混同しないでください。

**Returns:**
int 値です。

### hasNext {#hasNext--}
```
public boolean hasNext()
```



### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

このコレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

コレクションを反復処理する列挙子を返します。

**Returns:**
コレクションを反復処理できる System.Collections.IEnumerator オブジェクトです。

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

インデックスで項目を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除される項目のインデックスです。 |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
まだサポートされていません。常に例外がスローされます。

### size {#size--}
```
public int size()
```

ドキュメントアウトラインのすべてのレベルにおけるアウトライン項目（ブックマーク）の総数を取得します。

**Returns:**
int 値です。
