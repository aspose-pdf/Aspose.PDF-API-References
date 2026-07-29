---
title: "TextFragmentCollection"
linktitle: "TextFragmentCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "テキストフラグメントのコレクションを表します"
type: docs
weight: 5130
url: /ja/java/com.aspose.pdf/textfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextFragmentCollection

**All Implemented Interfaces:**
Iterable < TextFragment >

```
public final class TextFragmentCollection extends Object implements Iterable < TextFragment >
```

テキストフラグメントのコレクションを表します

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.TextFragment-) | 指定されたインデックスにテキストフラグメント要素を追加します。 |
| [clear](#clear--) | コレクションからすべての項目をクリアします。 |
| [contains](#contains-com.aspose.pdf.TextFragment-) | コレクションが特定の値を含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.TextFragment:A-int-) | / * / * コレクション全体の列挙子を返します。 / * / * |
| [get_Item](#get_Item-int-) | 指定されたインデックスのテキストフラグメント要素を取得します。インデックスは [1..n] の範囲である必要があり、n はテキストフラグメントの数に等しいです。 |
| [getSyncRoot](#getSyncRoot--) | コレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します |
| [isSynchronized](#isSynchronized--) | コレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator](#iterator--) | コレクション全体の列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.TextFragment-) | コレクションから指定された項目を削除します。 |
| [size](#size--) | コレクションに実際に含まれる {@code TextFragment} オブジェクト要素の数を取得します。 |

### add {#add-com.aspose.pdf.TextFragment-}
指定されたインデックスにテキストフラグメント要素を追加します。

### clear {#clear--}
```
public void clear()
```

コレクションからすべての項目をクリアします。

### contains {#contains-com.aspose.pdf.TextFragment-}
コレクションが特定の値を含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.TextFragment:A-int-}
/ * / * コレクション全体の列挙子を返します。 / * / *

### get_Item {#get_Item-int-}
```
public TextFragment get_Item(int index)
```

指定されたインデックスのテキストフラグメント要素を取得します。インデックスは [1..n] の範囲である必要があり、n はテキストフラグメントの数に等しいです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | コレクション内のインデックス。 |

**Returns:**
TextFragment オブジェクト。

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
public Iterator < TextFragment > iterator()
```

コレクション全体の列挙子を返します。

**Returns:**
Enumerator オブジェクト。

### remove {#remove-com.aspose.pdf.TextFragment-}
コレクションから指定された項目を削除します。

### size {#size--}
```
public int size()
```

コレクションに実際に含まれる {@code TextFragment} オブジェクト要素の数を取得します。

**Returns:**
int 値です。
