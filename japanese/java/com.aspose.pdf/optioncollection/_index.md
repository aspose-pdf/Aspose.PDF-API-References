---
title: "OptionCollection"
linktitle: "OptionCollection"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "選択フィールドのオプションのコレクションを表すクラス。"
type: docs
weight: 3250
url: /ja/java/com.aspose.pdf/optioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OptionCollection

**All Implemented Interfaces:**
Iterable < Option >

```
public final class OptionCollection extends Object implements Iterable < Option >
```

選択フィールドのオプションのコレクションを表すクラス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.Option-) | コレクションに項目を追加します。例外をスローします。まだ実装されていません。 |
| [clear](#clear--) | コレクションからすべての項目を削除します。 |
| [contains](#contains-com.aspose.pdf.Option-) | コレクションに項目が存在するか確認します。例外をスローします。まだ実装されていません。 |
| [deleteOption](#deleteOption-java.lang.String-) | 名前でオプションを削除します。 |
| [get_Item](#get_Item-int-) | インデックスでオプションを取得します。 |
| [get_Item](#get_Item-java.lang.String-) | 名前でオプションを取得します。 |
| [get](#get-int-) | インデックスでオプションを取得します。 |
| [get](#get-java.lang.String-) | コレクションからオプション名でオプションを取得します。 |
| [getSyncRoot](#getSyncRoot--) | コレクションの同期オブジェクト。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかを示す値を取得します。 |
| [isSynchronized](#isSynchronized--) | オブジェクトが同期されている場合に true を返します。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | コレクション内のオプションの列挙子を返します。 |
| [iterator](#iterator--) | コレクション内のオプションの列挙子を返します。 |
| [remove](#remove-com.aspose.pdf.Option-) | コレクションから項目を削除します。例外をスローします。まだ実装されていません。 |
| [size](#size--) | オプションの数を取得します。 |

### add {#add-com.aspose.pdf.Option-}
コレクションに項目を追加します。例外をスローします。まだ実装されていません。

### clear {#clear--}
```
public void clear()
```

コレクションからすべての項目を削除します。

### contains {#contains-com.aspose.pdf.Option-}
コレクションに項目が存在するか確認します。例外をスローします。まだ実装されていません。

### deleteOption {#deleteOption-java.lang.String-}
名前でオプションを削除します。

### get_Item {#get_Item-int-}
```
public Option get_Item(int index)
```

インデックスでオプションを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | オプションのインデックス。 |

**Returns:**
指定されたインデックスのオプション。

### get_Item {#get_Item-java.lang.String-}
名前でオプションを取得します。

### get {#get-int-}
```
public Option get(int index)
```

インデックスでオプションを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | オプションインデックス。インデックスは [1..n] の範囲である必要があります（n はオプション数）。 |

**Returns:**
取得したオプション。

### get {#get-java.lang.String-}
コレクションからオプション名でオプションを取得します。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

コレクションの同期オブジェクト。

**Returns:**
オブジェクト要素

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

オブジェクトが同期されている場合に true を返します。

**Returns:**
ブール値

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

コレクション内のオプションの列挙子を返します。

**Returns:**
オプションの列挙子。

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Option > iterator()
```

コレクション内のオプションの列挙子を返します。

**Returns:**
オプションの列挙子。

### remove {#remove-com.aspose.pdf.Option-}
コレクションから項目を削除します。例外をスローします。まだ実装されていません。

### size {#size--}
```
public int size()
```

オプションの数を取得します。

**Returns:**
int 値です。
