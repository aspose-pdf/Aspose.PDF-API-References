---
title: "PdfXmpMetadata.Add"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfXmpMetadata. تُضيف قيمة إلى بيانات XMP الوصفية"
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

يضيف قيمة إلى بيانات XMP الوصفية.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | DefaultMetadataProperties | اسم المفتاح. |
| القيمة | XmpValue | القيمة التي سيتم إضافتها. |

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### انظر أيضًا

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

يضيف حقل امتداد إلى البيانات الوصفية.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | كائن امتداد pdf لإضافته. |
| namespacePrefix | String | بادئة المخطط. |
| namespaceUri | String | معرف URI للمساحة الاسمية للمخطط. |
| schemaDescription | String | الوصف الاختياري للمخطط. |

### انظر أيضًا

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

يضيف عنصرًا جديدًا إلى كائن القاموس.

```csharp
public void Add(string key, XmpValue value)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | String | مفتاح العنصر الجديد. |
| القيمة | XmpValue | قيمة العنصر. |

## أمثلة

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### انظر أيضًا

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

يضيف عنصرًا جديدًا إلى كائن القاموس.

```csharp
public void Add(string key, object value)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| المفتاح | String | مفتاح العنصر الجديد. |
| القيمة | كائن | قيمة العنصر. |

### انظر أيضًا

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

يضيف زوجًا من المفتاح والقيمة إلى القاموس.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| item | KeyValuePair`2 | العنصر الذي سيتم إضافته. |

### انظر أيضًا

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


