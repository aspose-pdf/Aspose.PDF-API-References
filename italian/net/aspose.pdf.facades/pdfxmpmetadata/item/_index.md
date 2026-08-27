---
title: "PdfXmpMetadata.Item"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà PdfXmpMetadata. Ottiene o imposta il valore per chiave"
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
| chiave | Il nome della chiave da ottenere/impostare. |

### Valore di ritorno

Oggetto per chiave

## Esempi

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm["xmp:Nickname"]);
```

### Vedi anche

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## PdfXmpMetadata indexer (2 of 2)

Ottiene il valore dei metadati XMP per chiave.

```csharp
public XmpValue this[DefaultMetadataProperties key] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| chiave | Chiave del valore. |

### Valore di ritorno

Valore dai metadati XMP.

## Esempi

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
Console.WriteLine(pxm[DefaultMetadataProperties.CreatorTool]);
```

### Vedi anche

* class [XmpValue](../../../aspose.pdf/xmpvalue/)
* enum [DefaultMetadataProperties](../../defaultmetadataproperties/)
* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


