---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "クラスはすべてのデスティネーションのコレクションを表します（名前文字列をデスティネーションにマッピングする名前ツリー（12.3.2.3、\"Named Destinations\" を参照）および（7.7.4、\"Name Dictionary\" を参照））です。"
type: docs
weight: 960
url: /ja/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

PDF ドキュメント内のすべてのデスティネーション（名前文字列をデスティネーションにマッピングする名前ツリー（12.3.2.3「Named Destinations」参照）および（7.7.4「Name Dictionary」参照））のコレクションを表すクラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 指定された項目を追加します。 |
| [clear](#clear--) | コレクションは読み取り専用です。常に NotSupportedException 例外をスローします。 |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | このインスタンスがオブジェクトを含むかどうかを判定します。 |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | コレクションの要素を配列にコピーし、特定の配列インデックスから開始します。 |
| [get_Item](#get_Item-int-) | インデックスでデスティネーションオブジェクトを取得します。 |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | 名前で明示的なデスティネーションを返します。 |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | 名前でデスティネーションのページ番号を返します。 |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | コレクション内のデスティネーションのインデックスを返します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [iterator](#iterator--) | 列挙子を返します。 |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 指定された項目を削除します。 |
| [size](#size--) | コレクションに含まれる要素数を取得します。 |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
指定された項目を追加します。

### clear {#clear--}
```
public void clear()
```

コレクションは読み取り専用です。常に NotSupportedException 例外をスローします。

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
このインスタンスがオブジェクトを含むかどうかを判定します。

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
コレクションの要素を配列にコピーし、特定の配列インデックスから開始します。

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

インデックスでデスティネーションオブジェクトを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 取得するデスティネーションのインデックス。 |

**Returns:**
デスティネーション。

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
名前で明示的なデスティネーションを返します。

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
名前でデスティネーションのページ番号を返します。

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
コレクション内のデスティネーションのインデックスを返します。

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

列挙子を返します。

**Returns:**
列挙子です。

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
指定された項目を削除します。

### size {#size--}
```
public int size()
```

コレクションに含まれる要素数を取得します。

**Returns:**
int 値です。
