---
title: "PdfXmpMetadata"
linktitle: "PdfXmpMetadata"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة للتعامل مع بيانات XMP الوصفية."
type: docs
weight: 620
url: /ar/java/com.aspose.pdf.facades/pdfxmpmetadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfXmpMetadata, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfXmpMetadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class PdfXmpMetadata extends SaveableFacade implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

فئة للتعامل مع بيانات XMP الوصفية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfXmpMetadata](#PdfXmpMetadata--) | <p> منشئ لـ PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |
| [PdfXmpMetadata](#PdfXmpMetadata-com.aspose.pdf.IDocument-) | <p> منشئ لـ PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-) | يضيف حقل امتداد إلى البيانات الوصفية. |
| [addItem](#addItem-int-com.aspose.pdf.XmpValue-) | <p> يضيف قيمة إلى بيانات XMP الوصفية. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre> |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يضيف زوجًا بالمفتاح والقيمة إلى القاموس. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | يضيف عنصرًا جديدًا إلى كائن القاموس. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | <p> يضيف عنصرًا جديدًا إلى كائن القاموس. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre> |
| [clear](#clear--) | <p> يزيل جميع العناصر من الكائن. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre> |
| [contains](#contains-int-) | يتحقق مما إذا كان القاموس يحتوي على الخاصية المحددة. |
| [contains](#contains-java.lang.String-) | <p> يتحقق مما إذا كان القاموس يحتوي على المفتاح المحدد. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre> |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس. |
| [containsKey](#containsKey-java.lang.String-) | يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | نسخ البيانات الوصفية إلى مصفوفة. |
| [get_Item](#get_Item-java.lang.String-) | <p> يحصل على القيمة حسب المفتاح. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [getByDefaultMetadataProperties](#getByDefaultMetadataProperties-int-) | <p> يحصل على قيمة بيانات XMP الوصفية حسب المفتاح. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [getExtensionFields](#getExtensionFields--) | <p> يحصل على قاموس حقول الامتداد. </p> |
| [getKeys](#getKeys--) | يحصل على المفاتيح من القاموس. |
| [getNamespaceURIByPrefix](#getNamespaceURIByPrefix-java.lang.String-) | <p> يحصل على URI مساحة الاسم حسب البادئة. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre> |
| [getPrefixByNamespaceURI](#getPrefixByNamespaceURI-java.lang.String-) | <p> يحصل على البادئة حسب URI مساحة الاسم. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre> |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن المزامنة للمجموعة. |
| [getValues](#getValues--) | يحصل على مجموعة القيم في القاموس. |
| [getXmpMetadata](#getXmpMetadata--) | <p> احصل على XmpMetadata لملف PDF المدخل بصيغة XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [getXmpMetadata](#getXmpMetadata-java.lang.String-) | <p> احصل على XmpMetadata لملف PDF المدخل بصيغة XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre> |
| [isFixedSize](#isFixedSize--) | يعيد true إذا كان التجميع ذو حجم ثابت. |
| [isReadOnly](#isReadOnly--) | يعيد true إذا كان التجميع للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يعيد true إذا كان التجميع متزامنًا. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | يحصل على كائن enumerator للقاموس. |
| [iteratorIt](#iteratorIt--) | يحصل على كائن enumerator للمجموعة. |
| [registerNamespaceURI](#registerNamespaceURI-java.lang.String-java.lang.String-) | <p> يسجل عنوان URI للمساحة الاسمية. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre> |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | يزيل زوج المفتاح/القيمة من المجموعة. |
| [removeItemByKey](#removeItemByKey-int-) | <p> يزيل العنصر بالمفتاح المحدد. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre> |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | <p> يزيل المفتاح من القاموس. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre> |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | <p> يضبط القيمة حسب المفتاح. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre> |
| [setByDefaultMetadataProperties](#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-) | <p> يضبط قيمة بيانات XMP الوصفية حسب المفتاح. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre> |
| [size](#size--) | <p> يحصل على عدد العناصر في المجموعة. </p> |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها. |

### PdfXmpMetadata {#PdfXmpMetadata--}
```
public PdfXmpMetadata()
```

<p> منشئ لـ PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### PdfXmpMetadata {#PdfXmpMetadata-com.aspose.pdf.IDocument-}
<p> منشئ لـ PdfXmpMetadata. </p> <hr> <pre> PdfXmlMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); </pre>

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-java.lang.String-java.lang.String-java.lang.String-}
يضيف حقل امتداد إلى البيانات الوصفية.

### addItem {#addItem-int-com.aspose.pdf.XmpValue-}
<p> يضيف قيمة إلى بيانات XMP الوصفية. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add(DefaultMetadataProperties.Nickname, "name1"); xmp.save(TestSettings.getOutputFile("XMP_AddedValue.pdf")); </pre>

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يضيف زوجًا بالمفتاح والقيمة إلى القاموس.

### addItem {#addItem-java.lang.String-java.lang.Object-}
يضيف عنصرًا جديدًا إلى كائن القاموس.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
<p> يضيف عنصرًا جديدًا إلى كائن القاموس. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); </pre>

### clear {#clear--}
```
public void clear()
```

<p> يزيل جميع العناصر من الكائن. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.clear(); </pre>

### contains {#contains-int-}
```
public boolean contains(int property)
```

يتحقق مما إذا كان القاموس يحتوي على الخاصية المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية |  | الخاصية التي سيتم فحصها. |

**Returns:**
True - إذا كان القاموس يحتوي على الخاصية المحددة؛ وإلا false.

### contains {#contains-java.lang.String-}
<p> يتحقق مما إذا كان القاموس يحتوي على المفتاح المحدد. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.add("xmp:Nickname", "Nickname1"); if (!xmp.contains("xmp:Nickname")) System.out.println("Key does not exists"); </pre>

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يتحقق مما إذا كان زوج المفتاح-القيمة المحدد موجودًا في القاموس.

### containsKey {#containsKey-java.lang.String-}
يحدد ما إذا كان هذا القاموس يحتوي على المفتاح المحدد.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
نسخ البيانات الوصفية إلى مصفوفة.

### get_Item {#get_Item-java.lang.String-}
<p> يحصل على القيمة حسب المفتاح. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### getByDefaultMetadataProperties {#getByDefaultMetadataProperties-int-}
```
public XmpValue getByDefaultMetadataProperties(int key)
```

<p> يحصل على قيمة بيانات XMP الوصفية حسب المفتاح. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| key |  | مفتاح القيمة. |

**Returns:**
قيمة من بيانات XMP الوصفية. @see DefaultMetadataProperties

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> يحصل على قاموس حقول الامتداد. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} كائن

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

يحصل على المفاتيح من القاموس.

**Returns:**
عنصر ICollection

### getNamespaceURIByPrefix {#getNamespaceURIByPrefix-java.lang.String-}
<p> يحصل على URI مساحة الاسم حسب البادئة. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getNamespaceURIByPrefix("xmp")); </pre>

### getPrefixByNamespaceURI {#getPrefixByNamespaceURI-java.lang.String-}
<p> يحصل على البادئة حسب URI مساحة الاسم. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); System.out.println(xmp.getPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/")); </pre>

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن المزامنة للمجموعة.

**Returns:**
عنصر Object

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

يحصل على مجموعة القيم في القاموس.

**Returns:**
ICollection كائن

### getXmpMetadata {#getXmpMetadata--}
```
public byte[] getXmpMetadata()
```

<p> احصل على XmpMetadata لملف PDF المدخل بصيغة XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
البايتات الخاصة بـ XmpMetadata.

### getXmpMetadata {#getXmpMetadata-java.lang.String-}
<p> احصل على XmpMetadata لملف PDF المدخل بصيغة XML. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); byte[] data = pxm.getXmpMetadata(); </pre>

**Returns:**
البايتات الخاصة بـ XmpMetadata.

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

يعيد true إذا كان التجميع ذو حجم ثابت.

**Returns:**
قيمة منطقية

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يعيد true إذا كان التجميع للقراءة فقط.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يعيد true إذا كان التجميع متزامنًا.

**Returns:**
قيمة منطقية

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

يحصل على كائن enumerator للقاموس.

**Returns:**
كائن enumerator.

### iteratorIt {#iteratorIt--}
```
public com.aspose.ms.System.Collections.IEnumerator iteratorIt()
```

يحصل على كائن enumerator للمجموعة.

**Returns:**
كائن IEnumerator

### registerNamespaceURI {#registerNamespaceURI-java.lang.String-java.lang.String-}
<p> يسجل عنوان URI للمساحة الاسمية. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf"); xmp.registerNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/"); </pre>

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
يزيل زوج المفتاح/القيمة من المجموعة.

### removeItemByKey {#removeItemByKey-int-}
```
public void removeItemByKey(int key)
```

<p> يزيل العنصر بالمفتاح المحدد. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove(DefaultMetadataProperties.Nickname); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| key |  | مفتاح العنصر الذي سيتم حذفه. @see DefaultMetadataProperties |

### removeItemByKey {#removeItemByKey-java.lang.String-}
<p> يزيل المفتاح من القاموس. </p> <hr> <pre> PdfXmpMetadata xmp = new PdfXmpMetadata(); xmp.bindPdf("input.pdf"); xmp.remove("xmp:Nickname"); </pre>

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
<p> يضبط القيمة حسب المفتاح. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item("xmp:Nickname")); </pre>

### setByDefaultMetadataProperties {#setByDefaultMetadataProperties-int-com.aspose.pdf.XmpValue-}
<p> يضبط قيمة بيانات XMP الوصفية حسب المفتاح. </p> <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println(pxm.get_Item(DefaultMetadataProperties.CreatorTool)); </pre>

### size {#size--}
```
public int size()
```

<p> يحصل على عدد العناصر في المجموعة. </p>

**Returns:**
قيمة int <hr> <pre> PdfXmpMetadata pxm = new PdfXmpMetadata(); pxm.bindPdf("PdfFile.pdf"); System.out.println("Count = " + pxm.size()); </pre>

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
يحاول العثور على المفتاح في القاموس ويسترجع القيمة إذا تم العثور عليها.
