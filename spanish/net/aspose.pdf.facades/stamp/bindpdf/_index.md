---
title: BindPdf
second_title: Referencia de API de Aspose.PDF para .NET
description: Establece el archivo PDF y el número de página que se usará como sello.
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/stamp/bindpdf/
---
## BindPdf(string, int) {#bindpdf_1}

Establece el archivo PDF y el número de página que se usará como sello.

```csharp
public void BindPdf(string pdfFile, int pageNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pdfFile | String | Ruta al archivo PDF. |
| pageNumber | Int32 | Número de página en archivo PDF |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//La primera página se usará como sello.
stamp.BindPdf("stamp.pdf", 1);
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ver también

* class [Stamp](../../stamp)
* espacio de nombres [Aspose.Pdf.Facades](../../stamp)
* asamblea [Aspose.PDF](../../../)

---

## BindPdf(Stream, int) {#bindpdf}

Establece el archivo PDF y el número de página que se usará como sello.

```csharp
public void BindPdf(Stream pdfStream, int pageNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pdfStream | Stream | Secuencia que contiene el documento PDF. |
| pageNumber | Int32 | Índice de página del documento que se utilizará como sello. |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
//La primera página se usará como sello.
Stream stream = new FileStream("stamp.pdf", FileMode.Open, FileAccess.Read);
stamp.BindPdf(stream, 1);
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Ver también

* class [Stamp](../../stamp)
* espacio de nombres [Aspose.Pdf.Facades](../../stamp)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
