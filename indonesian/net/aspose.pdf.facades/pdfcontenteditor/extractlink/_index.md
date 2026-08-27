---
title: "PdfContentEditor.ExtractLink"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Mengekstrak koleksi instance Link yang terdapat dalam dokumen PDF"
type: docs
weight: 370
url: /id/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

Mengekstrak koleksi instance Link yang terdapat dalam dokumen PDF.

```csharp
public IList<Annotation> ExtractLink()
```

### Nilai Kembalian

Koleksi objek Link

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // bekerja dengan instance Link
}
```

### Lihat Juga

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


