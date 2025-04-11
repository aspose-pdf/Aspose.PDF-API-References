---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Menghapus beberapa stempel di halaman yang ditentukan berdasarkan indeks stempel
type: docs
weight: 330
url: /id/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## Metode PdfContentEditor.DeleteStamp

Menghapus beberapa stempel di halaman yang ditentukan berdasarkan indeks stempel.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Nomor halaman tempat stempel akan dihapus. |
| index | Int32[] | Indeks stempel. |

## Contoh

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)