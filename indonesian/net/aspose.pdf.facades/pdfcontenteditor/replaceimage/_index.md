---
title: "PdfContentEditor.ReplaceImage"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfContentEditor. Mengganti gambar yang ditentukan pada halaman yang ditentukan dari dokumen PDF dengan gambar lain"
type: docs
weight: 440
url: /id/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

Mengganti gambar yang ditentukan pada halaman yang ditentukan dari dokumen PDF dengan gambar lain.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Jumlah halaman tempat gambar diganti. |
| index | Int32 | Indeks objek gambar yang harus diganti. |
| imageFile | String | File gambar akan digunakan untuk penggantian. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


