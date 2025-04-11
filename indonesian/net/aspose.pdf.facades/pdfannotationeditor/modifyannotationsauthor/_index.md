---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfAnnotationEditor. Memodifikasi penulis anotasi pada rentang halaman yang ditentukan
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## Metode PdfAnnotationEditor.ModifyAnnotationsAuthor

Memodifikasi penulis anotasi pada rentang halaman yang ditentukan.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start | Int32 | Nomor halaman awal. |
| end | Int32 | Nomor halaman akhir. |
| srcAuthor | String | Penulis yang harus dimodifikasi. |
| desAuthor | String | Penulis baru. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)