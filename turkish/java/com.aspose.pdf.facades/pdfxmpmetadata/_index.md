---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "Aspose.PDF for Java API Referansı"
description: "XMP meta verileriyle manipülasyon için sınıf."
type: docs
weight: 620
url: /tr/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

XMP meta verileriyle manipülasyon için sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> PdfXmpMetadata için yapıcı. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> PdfXmpMetadata için yapıcı. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); </pre> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | Meta veriye uzantı alanı ekler. |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> XMP meta verisine değer ekler. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.add(DefaultMetadataProperties.Nickname, \"name1\"); xmp.save(TestSettings.getOutputFile(\"XMP_AddedValue.pdf\")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Anahtar ve değer çifti sözlüğe ekler. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Sözlük nesnesine yeni öğe ekler. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Sözlük nesnesine yeni öğe ekler. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.add(\"xmp:Nickname\", \"Nickname1\"); </pre> |
| [clear](#clear--) | <p> Nesneden tüm öğeleri kaldırır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.clear(); </pre> |
| [contains](#contains-int-) | Sözlüğün belirtilen özelliği içerip içermediğini kontrol eder. |
| [contains](#contains-java.lang.String-) | <p> Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.add(\"xmp:Nickname\", \"Nickname1\"); if (!xmp.contains(\"xmp:Nickname\")) System.out.println(\"Key does not exists\"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder. |
| [containsKey](#containsKey-java.lang.String-) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Meta veriyi diziye kopyalar. |
| [get_Item](#get_Item-java.lang.String-) | <p> Anahtara göre değeri alır. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(pxm.get_Item(\"xmp:Nickname\")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> Anahtara göre XMP meta verisinin değerini alır. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> Uzantı alanlarının sözlüğünü alır. </p> |
| [getKeys](#getKeys--) | Sözlükten anahtarları alır. |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> Önek ile ad alanı URI'sını alır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(\"input.pdf\"); System.out.println(xmp.getNamespaceURIByPrefix(\"xmp\")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> Ad alanı URI'sına göre öneki alır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(\"input.pdf\"); System.out.println(xmp.getPrefixByNamespaceURI(\"http://ns.adobe.com/xap/1.0/\")); </pre> |
| [getSyncRoot](#getSyncRoot--) | Koleksiyonun senkronizasyon nesnesini alır. |
| [getValues](#getValues--) | Sözlükteki değer koleksiyonunu alır. |
| [getXmpMetadata](#getXmpMetadata--) | <p> Girdi PDF'nin XmpMetadata'sını XML formatında al. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> Girdi PDF'nin XmpMetadata'sını XML formatında al. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | Koleksiyon sabit boyuta sahipse true döndürür. |
| [isReadOnly](#isReadOnly--) | Koleksiyon yalnızca okunabilir ise true döndürür. |
| [isSynchronized](#isSynchronized--) | Koleksiyon senkronize ise true döndürür. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Sözlüğün yineleyici nesnesini alır. |
| [iteratorIt](#iteratorIt--) | Koleksiyonun yineleyici nesnesini alır. |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> Namespace URI'sini kaydeder. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Koleksiyondan anahtar/değer çiftini kaldırır. |
| [removeItemByKey](#removeItemByKey-int-) | <p> Belirtilen anahtara sahip öğeyi kaldırır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> Sözlükten anahtarı kaldırır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> Anahtara göre değeri ayarlar. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> Anahtara göre XMP meta verisinin değerini ayarlar. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> Koleksiyondaki öğelerin sayısını alır. </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir. |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> PdfXmpMetadata için yapıcı. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> PdfXmpMetadata için yapıcı. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
Meta veriye uzantı alanı ekler.

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> XMP meta verisine değer ekler. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.add(DefaultMetadataProperties.Nickname, \"name1\"); xmp.save(TestSettings.getOutputFile(\"XMP_AddedValue.pdf\")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Anahtar ve değer çifti sözlüğe ekler.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Sözlük nesnesine yeni öğe ekler.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Sözlük nesnesine yeni öğe ekler. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.add(\"xmp:Nickname\", \"Nickname1\"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> Nesneden tüm öğeleri kaldırır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

Sözlüğün belirtilen özelliği içerip içermediğini kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik |  | Kontrol edilecek özellik. |

**Returns:**
True - sözlük belirtilen özelliği içeriyorsa; aksi takdirde false.

### contains {#contains-java.lang.String-}
<p> Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf(\"input.pdf\"); xmp.add(\"xmp:Nickname\", \"Nickname1\"); if (!xmp.contains(\"xmp:Nickname\")) System.out.println(\"Key does not exists\"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Belirtilen anahtar-değer çiftinin sözlükte bulunup bulunmadığını kontrol eder.

### containsKey {#containsKey-java.lang.String-}
Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Meta veriyi diziye kopyalar.

### get_Item {#get_Item-java.lang.String-}
<p> Anahtara göre değeri alır. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(pxm.get_Item(\"xmp:Nickname\")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> Anahtara göre XMP meta verisinin değerini alır. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar |  | Değerin anahtarı. |

**Returns:**
XMP meta verisinden değer. @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Uzantı alanlarının sözlüğünü alır. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} nesnesi

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Sözlükten anahtarları alır.

**Returns:**
ICollection öğesi

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> Önek ile ad alanı URI'sını alır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(\"input.pdf\"); System.out.println(xmp.getNamespaceURIByPrefix(\"xmp\")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> Ad alanı URI'sına göre öneki alır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(\"input.pdf\"); System.out.println(xmp.getPrefixByNamespaceURI(\"http://ns.adobe.com/xap/1.0/\")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Koleksiyonun senkronizasyon nesnesini alır.

**Returns:**
Nesne öğesi

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Sözlükteki değer koleksiyonunu alır.

**Returns:**
ICollection nesnesi

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> Girdi PDF'nin XmpMetadata'sını XML formatında al. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
XmpMetadata'nın baytları.

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> Girdi PDF'nin XmpMetadata'sını XML formatında al. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf(\"PdfFile.pdf\"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
XmpMetadata'nın baytları.

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Koleksiyon sabit boyuta sahipse true döndürür.

**Returns:**
boolean değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Koleksiyon yalnızca okunabilir ise true döndürür.

**Returns:**
boolean değer

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Koleksiyon senkronize ise true döndürür.

**Returns:**
boolean değer

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Sözlüğün yineleyici nesnesini alır.

**Returns:**
Yineleyici nesnesi.

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

Koleksiyonun yineleyici nesnesini alır.

**Returns:**
IEnumerator nesnesi

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> Namespace URI'sini kaydeder. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Koleksiyondan anahtar/değer çiftini kaldırır.

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> Belirtilen anahtara sahip öğeyi kaldırır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar |  | Silinecek öğenin anahtarı. @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> Sözlükten anahtarı kaldırır. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> Anahtara göre değeri ayarlar. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> Anahtara göre XMP meta verisinin değerini ayarlar. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> Koleksiyondaki öğelerin sayısını alır. </p>

**Returns:**
int değer <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir.
