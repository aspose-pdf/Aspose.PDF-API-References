---
title: BindPdf
second_title: Aspose.PDF für .NET-API-Referenz
description: PDF-Eingabedatei binden.
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

PDF-Eingabedatei binden.

```csharp
public override void BindPdf(string inputFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFile | String | PDF-Feld zum Binden |

### Beispiele

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Bindet PDF-Dokument aus Stream.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | Stream | Stream mit PDF-Dokumentdaten |

### Beispiele

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Siehe auch

* class [PdfExtractor](../../pdfextractor)
* namensraum [Aspose.Pdf.Facades](../../pdfextractor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
