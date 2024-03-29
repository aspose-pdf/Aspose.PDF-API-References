---
title: Item
second_title: Aspose.PDF per .NET API Reference
description: Ottiene o imposta il valore per chiave.
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/item/
---
## PdfXmpMetadata indexer (1 of 2)

Ottiene o imposta il valore per chiave.

```csharp
public XmpValue this[string key] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| key | Il nome della chiave da ottenere/impostare. |

### Valore di ritorno

Oggetto per chiave

### Esempi

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Guarda anche

* class [XmpValue](../../../aspose.pdf/xmpvalue)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* assemblea [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

Ottiene il valore dei metadati XMP per chiave.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| key | Chiave del valore. |

### Valore di ritorno

Valore dai metadati XMP.

### Esempi

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Guarda anche

* class [XmpValue](../../../aspose.pdf/xmpvalue)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties)
* class [PdfXmpMetadata](../../pdfxmpmetadata)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
