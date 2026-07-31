---
title: "PdfExtractor.BindPdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfExtractor method. Associa il file PDF di input"
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Associa il file PDF di input.

```csharp
public override void BindPdf(string inputFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFile | String | File PDF da associare |

## Esempi

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Associa il Document PDF dallo stream.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | Stream | Stream contenente i dati del documento PDF |

## Esempi

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


