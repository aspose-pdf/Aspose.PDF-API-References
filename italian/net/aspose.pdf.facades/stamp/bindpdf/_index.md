---
title: "Stamp.BindPdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Stamp. Imposta il file PDF e il numero di pagina che verrà usato come timbro"
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Imposta il file PDF e il numero di pagina che saranno usati come timbro.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfFile | String | Percorso al file PDF. |
| pageNumber | Int32 | Numero di pagina nel file PDF |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//La prima pagina verrà usata come timbro.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi anche

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Imposta il file PDF e il numero di pagina che saranno usati come timbro.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfStream | Stream | Stream che contiene il documento PDF. |
| pageNumber | Int32 | Indice della pagina del documento che verrà usato come timbro. |

## Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//La prima pagina verrà usata come timbro.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Vedi anche

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


