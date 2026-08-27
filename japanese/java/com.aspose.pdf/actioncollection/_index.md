---
title: "ActionCollection"
linktitle: "ActionCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "アクションのコレクション"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf/actioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public final class ActionCollection extends Object implements Iterable < PdfAction >
```

アクションのコレクション

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | コレクションに新しいアクションを追加します。 |
| [clear](#clear--) | コレクションをクリアします。 |
| [contains](#contains-com.aspose.pdf.PdfAction-) | まだサポートされていません。コレクションに指定された項目が存在する場合は true を返します。 |
| [copyTo](#copyTo-com.aspose.pdf.PdfAction:A-int-) | アクション配列をコレクションにコピーします。 |
| [delete](#delete--) | すべてのアクションを削除します。 |
| [delete](#delete-int-) | インデックスでコレクションからアクションを削除します。 |
| [get_Item](#get_Item-int-) | インデックスでアクションを取得します。 |
| [getSyncRoot](#getSyncRoot--) | 同期オブジェクトを取得します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用の場合、true を返します。 |
| [isSynchronized](#isSynchronized--) | オブジェクトが同期されている場合、true を返します。 |
| [iterator](#iterator--) | / * / * コレクションの列挙子を返します。 / * / * / * |
| [remove](#remove-com.aspose.pdf.PdfAction-) | * まだサポートされていません。コレクションから項目を削除します。 |
| [size](#size--) | コレクション上のアクションの数。 |

### add {#add-com.aspose.pdf.PdfAction-}
コレクションに新しいアクションを追加します。

### clear {#clear--}
```
public void clear()
```

コレクションをクリアします。

### contains {#contains-com.aspose.pdf.PdfAction-}
まだサポートされていません。コレクションに指定された項目が存在する場合は true を返します。

### copyTo {#copyTo-com.aspose.pdf.PdfAction:A-int-}
アクション配列をコレクションにコピーします。

### delete {#delete--}
```
public void delete()
```

すべてのアクションを削除します。

### delete {#delete-int-}
```
public void delete(int index)
```

インデックスでコレクションからアクションを削除します。

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
| インデックス |  | アクションのインデックス。 |

**Returns:**
取得されたアクション。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

同期オブジェクトを取得します。

**Returns:**
Object の値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用の場合、true を返します。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

オブジェクトが同期されている場合、true を返します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator()
```

/ * / * コレクションの列挙子を返します。 / * / * / *

**Returns:**
コレクションの列挙子。 /

### remove {#remove-com.aspose.pdf.PdfAction-}
* Not supported yet. Removes item from collection.

### size {#size--}
```
public int size()
```

コレクション上のアクションの数。

**Returns:**
int 値です。
