---
title: "メタデータ"
linktitle: "メタデータ"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XMP メタデータストリームへのアクセスを提供します。"
type: docs
weight: 3050
url: /ja/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

XMP メタデータストリームへのアクセスを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | キーと値のペアをディクショナリに追加します。 |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | メタデータに値を追加します。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | メタデータに PDF 拡張機能を追加します。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | メタデータに値を追加します。 |
| [clear](#clear--) | メタデータをクリアします。 |
| [contains](#contains-java.lang.String-) | キーがメタデータに含まれているか確認します。 |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 指定されたキーと値のペアがディクショナリに含まれているか確認します。 |
| [containsKey](#containsKey-java.lang.String-) | このディクショナリが指定されたキーを含むかどうかを判断します。 |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | コレクションの要素を配列にコピーします。 |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | コレクションの要素を配列にコピーします。 |
| [get_Item](#get_Item-java.lang.String-) | メタデータからデータを取得します。 |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | 内部使用のみです。拡張フィールドのディクショナリを取得します。 |
| [getExtensionFields](#getExtensionFields--) | <p> 拡張フィールドのディクショナリを取得します。 </p> |
| [getItem](#getItem-java.lang.String-) | メタデータからデータを取得します。 |
| [getKeys](#getKeys--) | メタデータキーのコレクションを取得します。 |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | プレフィックスから名前空間 URI を返します。 |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | 名前空間 URI からプレフィックスを返します。 |
| [getSyncRoot](#getSyncRoot--) | コレクションの同期オブジェクトを取得します。 |
| [getValues](#getValues--) | メタデータ内の値を取得します。 |
| [isFixedSize](#isFixedSize--) | コレクションが固定サイズかどうかをチェックします。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用かどうかをチェックします。 |
| [isSynchronized](#isSynchronized--) | コレクションが同期化されているかどうかをチェックします。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | 辞書の列挙子を返します。 |
| [iteratorIE](#iteratorIE--) | コレクションの列挙子を取得します。 |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | 名前空間 URI を登録します。 |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | 名前空間 URI を登録します。 |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | コレクションからキー/値のペアを削除します。 |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | メタデータからエントリを削除します。 |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | メタデータからデータを設定します。 |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | メタデータからデータを設定します。 |
| [size](#size--) | コレクション内の要素数を取得します。 |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
キーと値のペアをディクショナリに追加します。

### addItem {#addItem-java.lang.String-java.lang.Object-}
メタデータに値を追加します。

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
メタデータに PDF 拡張機能を追加します。

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
メタデータに値を追加します。

### clear {#clear--}
```
public void clear()
```

メタデータをクリアします。

### contains {#contains-java.lang.String-}
キーがメタデータに含まれているか確認します。

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
指定されたキーと値のペアがディクショナリに含まれているか確認します。

### containsKey {#containsKey-java.lang.String-}
このディクショナリが指定されたキーを含むかどうかを判断します。

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
コレクションの要素を配列にコピーします。

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
コレクションの要素を配列にコピーします。

### get_Item {#get_Item-java.lang.String-}
メタデータからデータを取得します。

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

内部使用のみです。拡張フィールドのディクショナリを取得します。

**Returns:**
内部オブジェクト

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> 拡張フィールドのディクショナリを取得します。 </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} オブジェクト

### getItem {#getItem-java.lang.String-}
メタデータからデータを取得します。

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

メタデータキーのコレクションを取得します。

**Returns:**
ICollection オブジェクト

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
プレフィックスから名前空間 URI を返します。

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
名前空間 URI からプレフィックスを返します。

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

コレクションの同期オブジェクトを取得します。

**Returns:**
同期用オブジェクト

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

メタデータ内の値を取得します。

**Returns:**
ICollection オブジェクト

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

コレクションが固定サイズかどうかをチェックします。

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用かどうかをチェックします。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

コレクションが同期化されているかどうかをチェックします。

**Returns:**
ブール値

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

辞書の列挙子を返します。

**Returns:**
列挙子。

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

コレクションの列挙子を取得します。

**Returns:**
IEnumerator オブジェクト @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
名前空間 URI を登録します。

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
名前空間 URI を登録します。

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
コレクションからキー/値のペアを削除します。

### removeItemByKey {#removeItemByKey-java.lang.String-}
メタデータからエントリを削除します。

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
メタデータからデータを設定します。

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
メタデータからデータを設定します。

### size {#size--}
```
public int size()
```

コレクション内の要素数を取得します。

**Returns:**
int 値です。

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
辞書内でキーを検索し、見つかった場合は値を取得します。

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
辞書内でキーを検索し、見つかった場合は値を取得します。
