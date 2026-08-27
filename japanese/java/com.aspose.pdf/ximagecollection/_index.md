---
title: "XImageCollection"
linktitle: "XImageCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XImage コレクションを表すクラスです。"
type: docs
weight: 5630
url: /ja/java/com.aspose.pdf/ximagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImageCollection

**All Implemented Interfaces:**
Iterable < XImage >

```
public final class XImageCollection extends Object implements Iterable < XImage >
```

XImage コレクションを表すクラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.BitmapInfo-) | エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。 |
| [add](#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-) | エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。 |
| [add](#add-java.awt.image.BufferedImage-) | エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。 |
| [add](#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-) | エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。 |
| [add](#add-java.io.InputStream-) | エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。 |
| [add](#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。 |
| [add](#add-java.io.InputStream-int-) | エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。 |
| [add](#add-com.aspose.pdf.XImage-) | 画像リストに新しい画像を追加します。このメソッドは画像を同じ PdfObject への参照として追加し（ファイルサイズの削減が可能です）。 |
| [add](#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-) |  |
| [addWithImageFilterType](#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。 |
| [clear](#clear--) | コレクションからすべての項目をクリアします。 |
| [contains](#contains-com.aspose.pdf.XImage-) | コレクションが特定の値を含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.pdf.XImage:A-int-) | 画像の配列をコレクションにコピーします。 |
| [delete](#delete--) | コレクションから画像を削除します。 |
| [delete](#delete-int-) | インデックスでコレクションからインデックスを削除します。 |
| [delete](#delete-int-int-) | インデックスでコレクションからインデックスを削除し、action パラメーターで指定されたアクションを実行します。 |
| [delete](#delete-java.lang.String-) | コレクションから画像を削除します。 |
| [delete](#delete-java.lang.String-int-) | コレクションから画像を削除します。 |
| [get_Item](#get_Item-int-) | インデックスでコレクションから画像を取得します。 |
| [get_Item](#get_Item-java.lang.String-) | 名前でコレクションから画像を取得します。 |
| [getImageName](#getImageName-com.aspose.pdf.XImage-) | 指定された画像のキーである画像リスト内の名前を返します。 |
| [getNames](#getNames--) | 画像名の配列を取得します。 |
| [getSyncRoot](#getSyncRoot--) | 同期オブジェクトを返します。 |
| [hasImage](#hasImage-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [isSynchronized](#isSynchronized--) | オブジェクトが同期されている場合、true を返します。 |
| [iterator](#iterator--) | コレクションの列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.XImage-) | まだサポートされておらず、例外をスローします。常に NotImplementedException をスローします。 |
| [replace](#replace-int-java.io.InputStream-) | コレクション内の画像を別の画像に置き換えます。 |
| [replace](#replace-int-java.io.InputStream-int-) | コレクション内の画像を別の画像に置き換えます。 |
| [replace](#replace-int-java.io.InputStream-int-boolean-) | コレクション内の画像を別の画像に置き換えます。 |
| [saveJpxWithQuality](#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-) |  |
| [size](#size--) | コレクション内の画像数。 |

### add {#add-com.aspose.pdf.BitmapInfo-}
エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。

### add {#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-}
エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。

### add {#add-java.awt.image.BufferedImage-}
エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。

### add {#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-}
エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。

### add {#add-java.io.InputStream-}
エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。

### add {#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。

### add {#add-java.io.InputStream-int-}
エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。

### add {#add-com.aspose.pdf.XImage-}
画像リストに新しい画像を追加します。このメソッドは画像を同じ PdfObject への参照として追加し（ファイルサイズの削減が可能です）。

### add {#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-}


### addWithImageFilterType {#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
エンティティをコレクションの末尾に追加し、最後のインデックスでエンティティにアクセスできるようにします。

### clear {#clear--}
```
public void clear()
```

コレクションからすべての項目をクリアします。

### contains {#contains-com.aspose.pdf.XImage-}
コレクションが特定の値を含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.pdf.XImage:A-int-}
画像の配列をコレクションにコピーします。

### delete {#delete--}
```
public void delete()
```

コレクションから画像を削除します。

### delete {#delete-int-}
```
public void delete(int index)
```

インデックスでコレクションからインデックスを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 画像インデックス。 |

### delete {#delete-int-int-}
```
public final void delete(int index, int action)
```

インデックスでコレクションからインデックスを削除し、action パラメーターで指定されたアクションを実行します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 削除される画像のインデックス。 |
| action |  | ImageDeleteAction 要素。画像削除後に実行されるアクション。 |

### delete {#delete-java.lang.String-}
コレクションから画像を削除します。

### delete {#delete-java.lang.String-int-}
コレクションから画像を削除します。

### get_Item {#get_Item-int-}
```
public XImage get_Item(int index)
```

インデックスでコレクションから画像を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 画像インデックス |

**Returns:**
取得した画像。

### get_Item {#get_Item-java.lang.String-}
名前でコレクションから画像を取得します。

### getImageName {#getImageName-com.aspose.pdf.XImage-}
指定された画像のキーである画像リスト内の名前を返します。

### getNames {#getNames--}
```
public String [] getNames()
```

画像名の配列を取得します。

**Returns:**
String[] 配列

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

同期オブジェクトを返します。

**Returns:**
オブジェクト要素

### hasImage {#hasImage-java.lang.String-}


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
ブール値

### iterator {#iterator--}
```
public Iterator < XImage > iterator()
```

コレクションの列挙子を返します。

**Returns:**
コレクションの列挙子

### remove {#remove-com.aspose.pdf.XImage-}
まだサポートされておらず、例外をスローします。常に NotImplementedException をスローします。

### replace {#replace-int-java.io.InputStream-}
コレクション内の画像を別の画像に置き換えます。

### replace {#replace-int-java.io.InputStream-int-}
コレクション内の画像を別の画像に置き換えます。

### replace {#replace-int-java.io.InputStream-int-boolean-}
コレクション内の画像を別の画像に置き換えます。

### saveJpxWithQuality {#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-}


### size {#size--}
```
public int size()
```

コレクション内の画像数。

**Returns:**
int 値です。
