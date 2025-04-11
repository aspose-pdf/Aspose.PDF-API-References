---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Método Stamp. Establece el archivo PDF y el número de página que se utilizará como sello
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Establece el archivo PDF y el número de página que se utilizará como sello.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdfFile | String | Ruta al archivo PDF. |
| pageNumber | Int32 | Número de página en el archivo PDF |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Establece el archivo PDF y el número de página que se utilizará como sello.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | Stream | Flujo que contiene el documento PDF. |
| pageNumber | Int32 | Índice de página del documento que se utilizará como sello. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//First page will be used as stamp.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### See Also

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)