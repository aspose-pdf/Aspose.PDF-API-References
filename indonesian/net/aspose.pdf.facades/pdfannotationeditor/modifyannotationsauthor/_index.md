---
title: "PdfAnnotationEditor.ModifyAnnotationsAuthor"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfAnnotationEditor. Mengubah penulis anotasi pada rentang halaman yang ditentukan"
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor method

Mengubah penulis anotasi pada rentang halaman yang ditentukan.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start | Int32 | Nomor halaman awal. |
| end | Int32 | Nomor halaman akhir. |
| srcAuthor | String | Penulis yang harus diubah. |
| desAuthor | String | Penulis baru. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


