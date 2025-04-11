---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: خاصية PdfXmpMetadata. الحصول على القيمة أو تعيينها بواسطة المفتاح
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

الحصول على القيمة أو تعيينها بواسطة المفتاح.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parameter | Description |
| --- | --- |
| key | اسم المفتاح للحصول على/تعيين. |

### Return Value

كائن بواسطة المفتاح

## Examples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

الحصول على قيمة بيانات XMP الوصفية بواسطة المفتاح.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parameter | Description |
| --- | --- |
| key | مفتاح القيمة. |

### Return Value

قيمة من بيانات XMP الوصفية.

## Examples

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### See Also

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)