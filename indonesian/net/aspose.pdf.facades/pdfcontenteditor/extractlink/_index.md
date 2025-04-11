---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Mengekstrak koleksi instance Link yang terdapat dalam dokumen PDF
type: docs
weight: 370
url: /id/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## Metode PdfContentEditor.ExtractLink

Mengekstrak koleksi instance Link yang terdapat dalam dokumen PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Nilai Kembali

Koleksi objek Link

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // work with Link instance
}
```

### Lihat Juga

* kelas [Annotation](../../../aspose.pdf.annotations/annotation/)
* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)