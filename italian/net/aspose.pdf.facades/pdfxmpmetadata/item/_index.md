---
title: PdfXmpMetadata.Item
second_title: Aspose.PDF for .NET API Reference
description: Proprietà PdfXmpMetadata. Ottiene o imposta il valore per chiave
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## Indicizzatore PdfXmpMetadata (1 di 2)

Ottiene o imposta il valore per chiave.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| key | Il nome della chiave da ottenere/impostare. |

### Valore di ritorno

Oggetto per chiave

## Esempi

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Vedi Anche

* classe [XmpValue](../../../aspose.pdf/xmpvalue/)
* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Indicizzatore PdfXmpMetadata (2 di 2)

Ottiene il valore dei metadati XMP per chiave.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| key | Chiave del valore. |

### Valore di ritorno

Valore dai metadati XMP.

## Esempi

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Vedi Anche

* classe [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)