---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Menghapus gambar yang ditentukan pada halaman yang ditentukan
type: docs
weight: 320
url: /id/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

Menghapus gambar yang ditentukan pada halaman yang ditentukan.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Nomor halaman di mana gambar harus dihapus. |
| index | Int32[] | Sebuah array yang mewakili indeks gambar. |

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Menghapus semua gambar dari dokumen PDF.

```csharp
public void DeleteImage()
```

## Contoh

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)