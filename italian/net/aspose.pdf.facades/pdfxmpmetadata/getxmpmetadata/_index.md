---
title: "PdfXmpMetadata.GetXmpMetadata"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfXmpMetadata method. Ottiene lo XmpMetadata del PDF di input in formato XML"
type: docs
weight: 190
url: /it/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Ottieni gli XmpMetadata del pdf di input in formato XML.

```csharp
public byte[] GetXmpMetadata()
```

### Valore di ritorno

I byte dello XmpMetadata.

## Esempi

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### Vedi anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Ottieni una parte degli XmpMetadata del pdf di input in base a un nome meta.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | String | Nome dei metadati. |

### Valore di ritorno

Byte dei metadati.

## Esempi

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### Vedi anche

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


