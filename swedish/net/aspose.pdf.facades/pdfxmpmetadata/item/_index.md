---
title: "PdfXmpMetadata.Item"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfXmpMetadata-egenskapen. Hämtar eller anger värde efter nyckel"
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

Hämtar eller anger värde efter nyckel.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| nyckel | Nyckelnamnet för att hämta/ange. |

### Returvärde

Objekt efter nyckel

## Exempel

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Se även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

Hämtar värde för XMP-metadata efter nyckel.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parameter | Beskrivning |
| --- | --- |
| nyckel | Nyckeln för värdet. |

### Returvärde

Värde från XMP-metadata.

## Exempel

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Se även

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


