---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XFormCollection のコレクションを表すクラスです。"
type: docs
weight: 5600
url: /ja/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

XFormCollection のコレクションを表すクラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | 新しい XForm をコレクションに追加します。 |
| [clear](#clear--) | コレクションからすべての項目をクリアします。 |
| [contains](#contains-com.aspose.pdf.XForm-) | コレクションが特定の値を含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | XFormCollection をコレクションにコピーします。 |
| [delete](#delete--) | コレクションからすべての XForm を削除します。 |
| [delete](#delete-int-) | コレクションから XForm を削除します。 |
| [delete](#delete-java.lang.String-) | コレクションからすべての XForm を削除します。 |
| [freeMemory](#freeMemory--) | キャッシュされたデータをクリアし、メモリを解放しますなど。 |
| [get_Item](#get_Item-int-) | インデックスで XForm を返します。 |
| [get_Item](#get_Item-java.lang.String-) | 名前で XForm を返します。指定された名前の XForm が見つからない場合は例外がスローされます。 |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | このフォームコレクション内のフォームの名前を返します |
| [getSyncRoot](#getSyncRoot--) | 同期オブジェクトです。 |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [isSynchronized](#isSynchronized--) | オブジェクトが同期されている場合、true を返します。 |
| [iterator](#iterator--) | コレクションの列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.XForm-) | コレクションから指定された項目を削除します。 |
| [size](#size--) | コレクション内の XForm の数を取得します。 |

### add {#add-com.aspose.pdf.XForm-}
新しい XForm をコレクションに追加します。

### clear {#clear--}
```
public void clear()
```

コレクションからすべての項目をクリアします。

### contains {#contains-com.aspose.pdf.XForm-}
コレクションが特定の値を含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
XFormCollection をコレクションにコピーします。

### delete {#delete--}
```
public void delete()
```

コレクションからすべての XForm を削除します。

### delete {#delete-int-}
```
public void delete(int index)
```

コレクションから XForm を削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除すべき XForm のインデックス |

### delete {#delete-java.lang.String-}
コレクションからすべての XForm を削除します。

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

キャッシュされたデータをクリアし、メモリを解放しますなど。

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

インデックスで XForm を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | XFormCollection のインデックス。XForm の番号は 1 から始まります |

**Returns:**
取得した XForm

### get_Item {#get_Item-java.lang.String-}
名前で XForm を返します。指定された名前の XForm が見つからない場合は例外がスローされます。

### getFormName {#getFormName-com.aspose.pdf.XForm-}
このフォームコレクション内のフォームの名前を返します

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

同期オブジェクトです。

**Returns:**
オブジェクト

### hasForm {#hasForm-java.lang.String-}


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

オブジェクトが同期されている場合、true を返します。

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

コレクションの列挙子を返します。

**Returns:**
コレクションの列挙子

### remove {#remove-com.aspose.pdf.XForm-}
コレクションから指定された項目を削除します。

### size {#size--}
```
public int size()
```

コレクション内の XForm の数を取得します。

**Returns:**
int 値です。
