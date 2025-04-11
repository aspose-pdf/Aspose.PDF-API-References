---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfContentEditor. Menghapus stempel pada halaman yang ditentukan berdasarkan ID stempel
type: docs
weight: 340
url: /id/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Menghapus stempel pada halaman yang ditentukan berdasarkan ID stempel.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Nomor halaman tempat stempel akan dihapus. |
| stampId | Int32 | Identifikasi stempel yang harus dihapus. |

## Contoh

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Hapus stempel berdasarkan ID dari semua halaman dokumen.

```csharp
public void DeleteStampById(int stampId)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stampId | Int32 | Identifikasi stempel yang harus dihapus. |

## Contoh

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Lihat Juga

* kelas [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)