---
title: Stamp.BindPdf
second_title: Aspose.PDF for .NET API Reference
description: Metodo Stamp. Imposta il file PDF e il numero di pagina che verrà utilizzato come timbro
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Imposta il file PDF e il numero di pagina che verrà utilizzato come timbro.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdfFile | String | Percorso del file PDF. |
| pageNumber | Int32 | Numero di pagina nel file PDF |

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

Imposta il file PDF e il numero di pagina che verrà utilizzato come timbro.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | Stream | Stream che contiene il documento PDF. |
| pageNumber | Int32 | Indice della pagina del documento che verrà utilizzato come timbro. |

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