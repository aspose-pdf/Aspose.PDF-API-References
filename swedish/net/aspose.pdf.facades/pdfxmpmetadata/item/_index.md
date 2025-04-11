---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-egenskap. Hämtar eller ställer in värde efter nyckel
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 av 2)

Hämtar eller ställer in värde efter nyckel.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| key | Nyckelnamn för att hämta/ställa in. |

### Returvärde

Objekt efter nyckel

## Exempel

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Se Även

* klass [XmpValue](../../../aspose.pdf/xmpvalue/)
* klass [PdfXmpMetadata](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 av 2)

Hämtar värde av XMP-metadata efter nyckel.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| key | Nyckel för värdet. |

### Returvärde

Värde från XMP-metadata.

## Exempel

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Se Även

* klass [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* klass [PdfXmpMetadata](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)