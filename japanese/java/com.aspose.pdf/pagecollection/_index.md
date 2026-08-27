---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF文書ページのコレクション。"
type: docs
weight: 3340
url: /ja/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

PDF文書ページのコレクション。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | アノテーションの操作機能を提供する {@code AnnotationSelector} ビジターオブジェクトを受け入れます。 |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | 画像配置オブジェクトの操作機能を提供する {@code ImagePlacementAbsorber} ビジターオブジェクトを受け入れます。 |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | テキストオブジェクトの操作機能を提供する {@code TextAbsorber} ビジターオブジェクトを受け入れます。 |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | テキストオブジェクトの操作機能を提供する {@code TextFragmentAbsorber} ビジターオブジェクトを受け入れます。 |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | ページをコレクションに追加します。 |
| [add](#add--) | 空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。 |
| [add](#add-java.lang.Iterable-) | 空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。 |
| [add](#add-java.util.List-) | 空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。 |
| [add](#add-com.aspose.pdf.Page-) | 空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。 |
| [add](#add-com.aspose.pdf.Page:A-) | 空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。 |
| [beginUpdate](#beginUpdate--) | グループの変更が開始されたときに更新します。 |
| [clear](#clear--) | ページコレクションをクリアします。 |
| [contains](#contains-com.aspose.pdf.Page-) | このインスタンスがオブジェクトを含むかどうかを判定します。 |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | ページをドキュメントにコピーします。 |
| [delete](#delete--) | コレクションからすべてのページを削除します。 |
| [delete](#delete-int-) | 指定されたページを削除します。 |
| [delete](#delete-java.lang.Integer:A-) | コレクションからすべてのページを削除します。 |
| [endUpdate](#endUpdate--) | グループの変更が完了したときに更新します。 |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | ページ上にあるすべてのフィールドを削除し、その代わりに値を配置します。 |
| [freeMemory](#freeMemory--) | キャッシュされたデータをクリアします |
| [get_Item](#get_Item-int-) | インデックスでページを取得します。 |
| [getSyncRoot](#getSyncRoot--) | コレクションの同期オブジェクトを取得します。 |
| [getUnrestricted](#getUnrestricted-int-) | インデックスでページを返します。 {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> 指定されたページのインデックスを返します。 </p> |
| [insert](#insert-int-) | 指定された位置に空のページをコレクションに挿入します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。 |
| [insert](#insert-int-java.lang.Iterable-) | コレクションからページをドキュメントに挿入します。 |
| [insert](#insert-int-java.util.List-) | コレクションからページをドキュメントに挿入します。 |
| [insert](#insert-int-com.aspose.pdf.Page-) | 指定された位置にページをページコレクションに挿入します。 |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | 配列のページをドキュメントに挿入します。 |
| [isEmpty](#isEmpty--) | コレクションが空の場合は TRUE を返します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。常に false を返します。 |
| [isSynchronized](#isSynchronized--) | オブジェクトが同期されている場合に true を返します。 |
| [iterator](#iterator--) | ページの列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.Page-) | 指定された項目を削除し、例外をスローします。 |
| [size](#size--) | ドキュメント内のページ数を取得します。 |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
アノテーションの操作機能を提供する {@code AnnotationSelector} ビジターオブジェクトを受け入れます。

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
画像配置オブジェクトの操作機能を提供する {@code ImagePlacementAbsorber} ビジターオブジェクトを受け入れます。

### accept {#accept-com.aspose.pdf.TextAbsorber-}
テキストオブジェクトの操作機能を提供する {@code TextAbsorber} ビジターオブジェクトを受け入れます。

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
テキストオブジェクトの操作機能を提供する {@code TextFragmentAbsorber} ビジターオブジェクトを受け入れます。

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
ページをコレクションに追加します。

### add {#add--}
```
public Page add()
```

空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。

**Returns:**
ページが追加されました。

### add {#add-java.lang.Iterable-}
空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。

**Returns:**
ページが追加されました。

### add {#add-java.util.List-}
空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。

**Returns:**
ページが追加されました。

### add {#add-com.aspose.pdf.Page-}
空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。

**Returns:**
ページが追加されました。

### add {#add-com.aspose.pdf.Page:A-}
空のページを追加します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。

**Returns:**
ページが追加されました。

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

グループの変更が開始されたときに更新します。

### clear {#clear--}
```
public void clear()
```

ページコレクションをクリアします。

### contains {#contains-com.aspose.pdf.Page-}
このインスタンスがオブジェクトを含むかどうかを判定します。

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
ページをドキュメントにコピーします。

### delete {#delete--}
```
public void delete()
```

コレクションからすべてのページを削除します。

### delete {#delete-int-}
```
public void delete(int index)
```

指定されたページを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除されるページの番号。ページ番号は 1 から始まります。 |

### delete {#delete-java.lang.Integer:A-}
コレクションからすべてのページを削除します。

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

グループの変更が完了したときに更新します。

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

ページ上にあるすべてのフィールドを削除し、その代わりに値を配置します。

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

キャッシュされたデータをクリアします

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

インデックスでページを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | ページのインデックス。 |

**Returns:**
取得されたページ。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

コレクションの同期オブジェクトを取得します。

**Returns:**
同期用オブジェクト

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

インデックスでページを返します。 {@code Page}

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 要求されたページのインデックス。ページ番号は 1 から始まります。 |

**Returns:**
要求されたページ

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> 指定されたページのインデックスを返します。 </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

指定された位置に空のページをコレクションに挿入します。ドキュメントにサイズが異なるページがすでに含まれている場合、最も頻繁に出現するページのサイズが選択されます。2 つだけ異なるページがある場合は、最初のページのサイズが使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | 新しいページの位置。 |

**Returns:**
挿入されたページ。

### insert {#insert-int-java.lang.Iterable-}
コレクションからページをドキュメントに挿入します。

### insert {#insert-int-java.util.List-}
コレクションからページをドキュメントに挿入します。

### insert {#insert-int-com.aspose.pdf.Page-}
指定された位置にページをページコレクションに挿入します。

### insert {#insert-int-com.aspose.pdf.Page:A-}
配列のページをドキュメントに挿入します。

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

コレクションが空の場合は TRUE を返します。

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを示す値を取得します。常に false を返します。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

オブジェクトが同期されている場合に true を返します。

**Returns:**
ブール値

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

ページの列挙子を返します。

**Returns:**
ページの列挙子

### remove {#remove-com.aspose.pdf.Page-}
指定された項目を削除し、例外をスローします。

### size {#size--}
```
public int size()
```

ドキュメント内のページ数を取得します。

**Returns:**
int 値です。
