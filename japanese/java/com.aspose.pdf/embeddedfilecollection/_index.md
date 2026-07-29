---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "埋め込みファイルコレクションを表すクラス。"
type: docs
weight: 1200
url: /ja/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

埋め込みファイルコレクションを表すクラス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | コレクションに埋め込みファイルの仕様を追加します。 |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | 指定されたキーで埋め込みファイルにファイルを追加します。 |
| [clear](#clear--) | ドキュメントからすべての埋め込みファイルを削除します。 |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | コレクションが指定された FileSpecification を含むかどうかを判定します。サポートされていません。 |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | FileSpecification オブジェクトの配列をコレクションにコピーします。 |
| [delete](#delete--) | ドキュメントからすべての埋め込みファイルを削除します。 |
| [delete](#delete-java.lang.String-) | ドキュメントからすべての埋め込みファイルを削除します。 |
| [deleteByKey](#deleteByKey-java.lang.String-) | コレクション内のキーでファイルを削除します。 |
| [findByName](#findByName-java.lang.String-) | 名前で埋め込みファイルを返します。 |
| [get_Item](#get_Item-int-) | インデックスで埋め込みファイルを取得します。 |
| [get_Item](#get_Item-java.lang.String-) | 名前で埋め込みファイルを取得します。 |
| [getKeys](#getKeys--) | ファイル添付キーのリストを返します。 |
| [getSyncRoot](#getSyncRoot--) | このコレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。 |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | 埋め込みファイル構造が存在するか確認します。構造が存在すれば TRUE、存在しなければ FALSE を返します。ドキュメントがこれまでに埋め込みファイルを含んでいなかった場合、この構造は作成されず存在しません。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを判定します。常に false を返します。 |
| [isSynchronized](#isSynchronized--) | このコレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | コレクションの列挙子を返します。 |
| [iterator](#iterator--) | コレクションの列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | 指定された FileSpecification をコレクションから削除します。サポートされていません。 |
| [size](#size--) | コレクション内の埋め込みファイル数を取得します。 |

### add {#add-com.aspose.pdf.FileSpecification-}
コレクションに埋め込みファイルの仕様を追加します。

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
指定されたキーで埋め込みファイルにファイルを追加します。

### clear {#clear--}
```
public void clear()
```

ドキュメントからすべての埋め込みファイルを削除します。

### contains {#contains-com.aspose.pdf.FileSpecification-}
コレクションが指定された FileSpecification を含むかどうかを判定します。サポートされていません。

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
FileSpecification オブジェクトの配列をコレクションにコピーします。

### delete {#delete--}
```
public void delete()
```

ドキュメントからすべての埋め込みファイルを削除します。

### delete {#delete-java.lang.String-}
ドキュメントからすべての埋め込みファイルを削除します。

### deleteByKey {#deleteByKey-java.lang.String-}
コレクション内のキーでファイルを削除します。

### findByName {#findByName-java.lang.String-}
名前で埋め込みファイルを返します。

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

インデックスで埋め込みファイルを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | 埋め込みファイルのインデックス。番号は 1 から始まります。 |

**Returns:**
取得した埋め込みファイルの仕様

### get_Item {#get_Item-java.lang.String-}
名前で埋め込みファイルを取得します。

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

ファイル添付キーのリストを返します。

**Returns:**
文字列値のリスト

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

このコレクションへのアクセスを同期させるために使用できるオブジェクトを取得します。

**Returns:**
同期用オブジェクト

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

埋め込みファイル構造が存在するか確認します。構造が存在すれば TRUE、存在しなければ FALSE を返します。ドキュメントがこれまでに埋め込みファイルを含んでいなかった場合、この構造は作成されず存在しません。

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかを判定します。常に false を返します。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

このコレクションへのアクセスが同期化されているか（スレッドセーフか）を示す値を取得します。

**Returns:**
ブール値

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

コレクションの列挙子を返します。

**Returns:**
コレクションの列挙子。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

コレクションの列挙子を返します。

**Returns:**
コレクションの列挙子。

### remove {#remove-com.aspose.pdf.FileSpecification-}
指定された FileSpecification をコレクションから削除します。サポートされていません。

### size {#size--}
```
public int size()
```

コレクション内の埋め込みファイル数を取得します。

**Returns:**
int 値です。
