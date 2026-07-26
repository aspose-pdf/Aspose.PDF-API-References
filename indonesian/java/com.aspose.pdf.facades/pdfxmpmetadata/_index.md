---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas untuk manipulasi metadata XMP."
type: docs
weight: 620
url: /id/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Kelas untuk manipulasi metadata XMP.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> Konstruktor untuk PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> Konstruktor untuk PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Menambahkan bidang ekstensi ke metadata. |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> Menambahkan nilai ke metadata XMP. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menambahkan pasangan dengan kunci dan nilai ke dalam kamus. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Menambahkan elemen baru ke objek kamus. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Menambahkan elemen baru ke objek kamus. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> Menghapus semua elemen dari objek. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | Memeriksa apakah kamus berisi properti yang ditentukan. |
| [contains](#contains-java.lang.String-) | <p> Memeriksa apakah kamus berisi kunci yang ditentukan. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus. |
| [containsKey](#containsKey-java.lang.String-) | Menentukan apakah kamus ini berisi kunci yang ditentukan. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Menyalin metadata ke dalam array. |
| [get_Item](#get_Item-java.lang.String-) | <p> Mendapatkan nilai berdasarkan kunci. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> Mendapatkan nilai metadata XMP berdasarkan kunci. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> Mengambil kamus bidang ekstensi. </p> |
| [getKeys](#getKeys--) | Mendapatkan kunci dari kamus. |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> Mendapatkan URI namespace berdasarkan prefiks. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> Mendapatkan prefiks berdasarkan URI namespace. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | Mendapatkan objek sinkronisasi dari koleksi. |
| [getValues](#getValues--) | Mendapatkan koleksi nilai dalam kamus. |
| [getXmpMetadata](#getXmpMetadata--) | <p> Mendapatkan XmpMetadata dari PDF input dalam format xml. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> Mendapatkan XmpMetadata dari PDF input dalam format xml. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | Mengembalikan true jika koleksi memiliki ukuran tetap. |
| [isReadOnly](#isReadOnly--) | Mengembalikan true jika koleksi bersifat hanya-baca. |
| [isSynchronized](#isSynchronized--) | Mengembalikan true jika koleksi disinkronkan. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Mendapatkan objek enumerator dari kamus. |
| [iteratorIt](#iteratorIt--) | Mendapatkan objek enumerator dari koleksi. |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> Mendaftarkan URI namespace. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Menghapus pasangan kunci/nilai dari koleksi. |
| [removeItemByKey](#removeItemByKey-int-) | <p> Menghapus elemen dengan kunci yang ditentukan. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> Menghapus kunci dari kamus. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Menetapkan nilai berdasarkan kunci. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> Menetapkan nilai metadata XMP berdasarkan kunci. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> Mendapatkan jumlah item dalam koleksi. </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan. |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> Konstruktor untuk PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> Konstruktor untuk PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
Menambahkan bidang ekstensi ke metadata.

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> Menambahkan nilai ke metadata XMP. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menambahkan pasangan dengan kunci dan nilai ke dalam kamus.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Menambahkan elemen baru ke objek kamus.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Menambahkan elemen baru ke objek kamus. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> Menghapus semua elemen dari objek. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

Memeriksa apakah kamus berisi properti yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti |  | Properti yang akan diperiksa. |

**Returns:**
True - jika kamus berisi properti yang ditentukan; jika tidak, false.

### contains {#contains-java.lang.String-}
<p> Memeriksa apakah kamus berisi kunci yang ditentukan. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Memeriksa apakah pasangan kunci-nilai yang ditentukan terdapat dalam kamus.

### containsKey {#containsKey-java.lang.String-}
Menentukan apakah kamus ini berisi kunci yang ditentukan.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Menyalin metadata ke dalam array.

### get_Item {#get_Item-java.lang.String-}
<p> Mendapatkan nilai berdasarkan kunci. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> Mendapatkan nilai metadata XMP berdasarkan kunci. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kunci |  | Kunci nilai. |

**Returns:**
Nilai dari metadata XMP. @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Mengambil kamus bidang ekstensi. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} objek

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Mendapatkan kunci dari kamus.

**Returns:**
Elemen ICollection

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> Mendapatkan URI namespace berdasarkan prefiks. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> Mendapatkan prefiks berdasarkan URI namespace. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Mendapatkan objek sinkronisasi dari koleksi.

**Returns:**
Elemen objek

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Mendapatkan koleksi nilai dalam kamus.

**Returns:**
objek ICollection

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> Mendapatkan XmpMetadata dari PDF input dalam format xml. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
Byte dari XmpMetadata.

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> Mendapatkan XmpMetadata dari PDF input dalam format xml. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
Byte dari XmpMetadata.

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Mengembalikan true jika koleksi memiliki ukuran tetap.

**Returns:**
nilai boolean

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mengembalikan true jika koleksi bersifat hanya-baca.

**Returns:**
nilai boolean

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Mengembalikan true jika koleksi disinkronkan.

**Returns:**
nilai boolean

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Mendapatkan objek enumerator dari kamus.

**Returns:**
Objek enumerator.

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

Mendapatkan objek enumerator dari koleksi.

**Returns:**
Objek IEnumerator

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> Mendaftarkan URI namespace. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Menghapus pasangan kunci/nilai dari koleksi.

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> Menghapus elemen dengan kunci yang ditentukan. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kunci |  | Kunci elemen yang akan dihapus. @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> Menghapus kunci dari kamus. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Menetapkan nilai berdasarkan kunci. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> Menetapkan nilai metadata XMP berdasarkan kunci. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> Mendapatkan jumlah item dalam koleksi. </p>

**Returns:**
nilai int <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Mencoba menemukan kunci dalam kamus dan mengambil nilai jika ditemukan.
