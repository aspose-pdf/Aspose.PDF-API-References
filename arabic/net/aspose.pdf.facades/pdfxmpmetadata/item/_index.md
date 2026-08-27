---
title: "PdfXmpMetadata.Item"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية PdfXmpMetadata. يحصل أو يضبط القيمة حسب المفتاح"
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

يحصل أو يضبط القيمة حسب المفتاح.

```csharp
public XmpValue this[string key] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| المفتاح | اسم المفتاح للحصول/التعيين. |

### قيمة الإرجاع

كائن حسب المفتاح

## أمثلة

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### انظر أيضًا

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

يحصل على قيمة بيانات XMP الوصفية حسب المفتاح.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| المفتاح | مفتاح القيمة. |

### قيمة الإرجاع

قيمة من بيانات XMP الوصفية.

## أمثلة

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### انظر أيضًا

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


