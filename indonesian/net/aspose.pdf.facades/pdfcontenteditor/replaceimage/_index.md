---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Mengganti gambar yang ditentukan pada halaman yang ditentukan dari dokumen PDF dengan gambar lain
type: docs
weight: 440
url: /id/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## Metode PdfContentEditor.ReplaceImage

Mengganti gambar yang ditentukan pada halaman yang ditentukan dari dokumen PDF dengan gambar lain.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Nomor halaman di mana gambar diganti. |
| index | Int32 | Indeks objek gambar yang harus diganti. |
| imageFile | String | File gambar yang akan digunakan untuk mengganti. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)