---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XMP メタデータを操作するクラスです。"
type: docs
weight: 620
url: /ja/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

XMP メタデータを操作するクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> PdfXmpMetadata のコンストラクタ。 </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> PdfXmpMetadata のコンストラクタ。 </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | メタデータに拡張フィールドを追加します。 |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> XMP メタデータに値を追加します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | キーと値のペアをディクショナリに追加します。 |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | 辞書オブジェクトに新しい要素を追加します。 |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> 辞書オブジェクトに新しい要素を追加します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> オブジェクトからすべての要素を削除します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | 辞書が指定されたプロパティを含むか確認します。 |
| [contains](#contains-java.lang.String-) | <p> 辞書が指定されたキーを含むか確認します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | 指定されたキーと値のペアがディクショナリに含まれているか確認します。 |
| [containsKey](#containsKey-java.lang.String-) | このディクショナリが指定されたキーを含むかどうかを判断します。 |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | メタデータを配列にコピーします。 |
| [get_Item](#get_Item-java.lang.String-) | <p> キーで値を取得します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> キーで XMP メタデータの値を取得します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> 拡張フィールドのディクショナリを取得します。 </p> |
| [getKeys](#getKeys--) | 辞書からキーを取得します。 |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> プレフィックスで名前空間 URI を取得します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> 名前空間 URI でプレフィックスを取得します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | コレクションの同期オブジェクトを取得します。 |
| [getValues](#getValues--) | 辞書内の値のコレクションを取得します。 |
| [getXmpMetadata](#getXmpMetadata--) | <p> 入力 PDF の XmpMetadata を XML 形式で取得します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> 入力 PDF の XmpMetadata を XML 形式で取得します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | コレクションが固定サイズの場合に true を返します。 |
| [isReadOnly](#isReadOnly--) | コレクションが読み取り専用の場合に true を返します。 |
| [isSynchronized](#isSynchronized--) | コレクションが同期化されている場合に true を返します。 |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | 辞書の列挙子オブジェクトを取得します。 |
| [iteratorIt](#iteratorIt--) | コレクションの列挙子オブジェクトを取得します。 |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> 名前空間 URI を登録します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | コレクションからキーと値のペアを削除します。 |
| [removeItemByKey](#removeItemByKey-int-) | <p> 指定されたキーの要素を削除します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> 辞書からキーを削除します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> キーで値を設定します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> キーで XMP メタデータの値を設定します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> コレクション内の項目数を取得します。 </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | 辞書内でキーを検索し、見つかった場合は値を取得します。 |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> PdfXmpMetadata のコンストラクタ。 </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> PdfXmpMetadata のコンストラクタ。 </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
メタデータに拡張フィールドを追加します。

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> XMP メタデータに値を追加します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
キーと値のペアをディクショナリに追加します。

### addItem {#addItem-java.lang.String-java.lang.Object-}
辞書オブジェクトに新しい要素を追加します。

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> 辞書オブジェクトに新しい要素を追加します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> オブジェクトからすべての要素を削除します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

辞書が指定されたプロパティを含むか確認します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| プロパティ |  | チェックされるプロパティ。 |

**Returns:**
True - 辞書が指定されたプロパティを含む場合は true、そうでなければ false。

### contains {#contains-java.lang.String-}
<p> 辞書が指定されたキーを含むか確認します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
指定されたキーと値のペアがディクショナリに含まれているか確認します。

### containsKey {#containsKey-java.lang.String-}
このディクショナリが指定されたキーを含むかどうかを判断します。

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
メタデータを配列にコピーします。

### get_Item {#get_Item-java.lang.String-}
<p> キーで値を取得します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> キーで XMP メタデータの値を取得します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー |  | 値のキー。 |

**Returns:**
XMP メタデータからの値。 @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> 拡張フィールドのディクショナリを取得します。 </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} オブジェクト

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

辞書からキーを取得します。

**Returns:**
ICollection 要素

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> プレフィックスで名前空間 URI を取得します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> 名前空間 URI でプレフィックスを取得します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

コレクションの同期オブジェクトを取得します。

**Returns:**
オブジェクト要素

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

辞書内の値のコレクションを取得します。

**Returns:**
ICollection オブジェクト

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> 入力 PDF の XmpMetadata を XML 形式で取得します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
XmpMetadata のバイト列。

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> 入力 PDF の XmpMetadata を XML 形式で取得します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
XmpMetadata のバイト列。

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

コレクションが固定サイズの場合に true を返します。

**Returns:**
ブール値

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

コレクションが読み取り専用の場合に true を返します。

**Returns:**
ブール値

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

コレクションが同期化されている場合に true を返します。

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

辞書の列挙子オブジェクトを取得します。

**Returns:**
列挙子オブジェクト。

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

コレクションの列挙子オブジェクトを取得します。

**Returns:**
IEnumerator オブジェクト

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> 名前空間 URI を登録します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
コレクションからキーと値のペアを削除します。

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> 指定されたキーの要素を削除します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー |  | 削除される要素のキー。 @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> 辞書からキーを削除します。 </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> キーで値を設定します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> キーで XMP メタデータの値を設定します。 </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> コレクション内の項目数を取得します。 </p>

**Returns:**
int 値 <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
辞書内でキーを検索し、見つかった場合は値を取得します。
