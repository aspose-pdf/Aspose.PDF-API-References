---
title: PdfXmpMetadata.GetXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: PdfXmpMetadata-Methode. Holen Sie sich die XmpMetadata des Eingabe-PDFs im XML-Format
type: docs
weight: 190
url: /de/net/aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/
---
## GetXmpMetadata() {#getxmpmetadata}

Holen Sie sich die XmpMetadata des Eingabe-PDFs im XML-Format.

```csharp
public byte[] GetXmpMetadata()
```

### Rückgabewert

Die Bytes der XmpMetadata.

## Beispiele

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata();
```

### Siehe auch

* Klasse [PdfXmpMetadata](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## GetXmpMetadata(string) {#getxmpmetadata_1}

Holen Sie sich einen Teil der XmpMetadata des Eingabe-PDFs gemäß einem Metanamen.

```csharp
public byte[] GetXmpMetadata(string name)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | String | Metadatenname. |

### Rückgabewert

Bytes der Metadaten.

## Beispiele

```csharp
PdfXmpMetadata pxm = new PdfXmpMetadata();
pxm.BindPdf("PdfFile.pdf");
byte[] data = pxm.GetXmpMetadata("dc:creator");
```

### Siehe auch

* Klasse [PdfXmpMetadata](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)