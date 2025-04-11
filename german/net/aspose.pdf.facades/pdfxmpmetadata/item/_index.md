---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-Eigenschaft. Ruft den Wert nach Schlüssel ab oder setzt ihn
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata-Indexer (1 von 2)

Ruft den Wert nach Schlüssel ab oder setzt ihn.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parameter | Beschreibung |
| --- | --- |
| key | Der Schlüsselname, um abzurufen/zu setzen. |

### Rückgabewert

Objekt nach Schlüssel

## Beispiele

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Siehe auch

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata-Indexer (2 von 2)

Ruft den Wert der XMP-Metadaten nach Schlüssel ab.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parameter | Beschreibung |
| --- | --- |
| key | Schlüssel des Wertes. |

### Rückgabewert

Wert aus den XMP-Metadaten.

## Beispiele

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Siehe auch

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)