---
title: PdfXmpMetadata.Add
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfXmpMetadata. تضيف قيمة إلى بيانات XMP
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/add/
---
## Add(DefaultMetadataProperties, XmpValue) {#add}

تضيف قيمة إلى بيانات XMP.

```csharp
public void Add(DefaultMetadataProperties key, XmpValue value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | DefaultMetadataProperties | اسم المفتاح. |
| value | XmpValue | القيمة التي ستتم إضافتها. |

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add(DefaultMetadataProperties.Nickname, "name1");
xmp.Save(TestSettings.GetOutputFile("XMP_AddedValue.pdf"));
```

### See Also

* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(XmpPdfAExtensionObject, string, string, string) {#add_1}

تضيف حقل امتداد إلى البيانات الوصفية.

```csharp
public void Add(XmpPdfAExtensionObject xmpPdfAExtensionObject, string namespacePrefix, 
    string namespaceUri, string schemaDescription)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xmpPdfAExtensionObject | XmpPdfAExtensionObject | كائن امتداد PDF لإضافته. |
| namespacePrefix | String | بادئة المخطط. |
| namespaceUri | String | URI مساحة الأسماء للمخطط. |
| schemaDescription | String | الوصف الاختياري للمخطط. |

### See Also

* class [XmpPdfAExtensionObject](../../../aspose.pdf/xmppdfaextensionobject/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, XmpValue) {#add_3}

تضيف عنصرًا جديدًا إلى كائن القاموس.

```csharp
public void Add(string key, XmpValue value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | مفتاح العنصر الجديد. |
| value | XmpValue | قيمة العنصر. |

## Examples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata();
xmp.BindPdf("input.pdf");
xmp.Add("xmp:Nickname", "Nickname1");
```

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(string, object) {#add_4}

تضيف عنصرًا جديدًا إلى كائن القاموس.

```csharp
public void Add(string key, object value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| key | String | مفتاح العنصر الجديد. |
| value | Object | قيمة العنصر. |

### See Also

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Add(KeyValuePair&lt;string, XmpValue&gt;) {#add_2}

تضيف زوجًا مع مفتاح وقيمة إلى القاموس.

```csharp
public void Add(KeyValuePair<string, XmpValue> item)
```

| Parameter | Type | Description |
| --- | --- | --- |
| item | KeyValuePair`2 | العنصر الذي سيتم إضافته. |

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)