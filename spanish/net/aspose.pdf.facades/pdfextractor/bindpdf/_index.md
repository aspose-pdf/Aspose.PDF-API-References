---
title: PdfExtractor.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Vincular archivo PDF de entrada
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/pdfextractor/bindpdf/
---
## BindPdf(string) {#bindpdf_2}

Vincular archivo PDF de entrada.

```csharp
public override void BindPdf(string inputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | String | Archivo PDF a vincular |

## Ejemplos

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindPdf("sample.pdf");
```

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## BindPdf(Stream) {#bindpdf_1}

Vincula documento PDF desde un flujo.

```csharp
public override void BindPdf(Stream inputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | Stream | Flujo que contiene datos del documento PDF |

## Ejemplos

```csharp
PdfExtractor ext = new PdfExtractor();
Stream stream = new FileStream("sample.pdf", FileMode.Open, FileAccess.Read);
ext.BindPdf(stream);
```

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)