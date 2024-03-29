---
title: Add
second_title: Aspose.PDF لمرجع .NET API
description: إضافة قيمة إلى بيانات تعريف XMP .
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

إضافة قيمة إلى بيانات تعريف XMP .

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| key | DefaultMetadataProperties | اسم المفتاح. |
| value | XmpValue | القيمة التي ستضاف. |

### أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### أنظر أيضا

* enum [DefaultMetadataProperties](../../defaultmetadataproperties)
* class [XmpValue](../../../aspose.pdf/xmpvalue)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* المجسم [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

يتم إضافة حقل الامتداد إلى البيانات الوصفية .

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | كائن امتداد pdf المراد إضافته. |
| namespacePrefix | String | بادئة المخطط. |
| namespaceUri | String | معرف مساحة الاسم للمخطط. |
| schemaDescription | String | الوصف الاختياري للمخطط. |

### أنظر أيضا

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* المجسم [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

إضافة عنصر جديد إلى كائن القاموس.

```csharp
public void Add(string key, XmpValue value)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| key | String | مفتاح عنصر جديد. |
| value | XmpValue | قيمة العنصر. |

### أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### أنظر أيضا

* class [XmpValue](../../../aspose.pdf/xmpvalue)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* المجسم [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

إضافة عنصر جديد إلى كائن القاموس.

```csharp
public void Add(string key, object value)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| key | String | مفتاح عنصر جديد. |
| value | Object | قيمة العنصر. |

### أنظر أيضا

* class [PdfXmpMetadata](../../pdfxmpmetadata)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* المجسم [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

إضافة زوج بالمفتاح والقيمة إلى القاموس.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| item | KeyValuePair`2 | العنصر المراد إضافته. |

### أنظر أيضا

* class [XmpValue](../../../aspose.pdf/xmpvalue)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
