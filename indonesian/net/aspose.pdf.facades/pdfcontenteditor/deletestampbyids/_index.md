---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfContentEditor metode. Menghapus stempel dengan ID yang ditentukan dari semua halaman dokumen"
type: docs
weight: 350
url: /id/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Menghapus stempel dengan ID yang ditentukan dari semua halaman dokumen.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stampIds | Int32[] | Array ID stempel. |

## Contoh

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Menghapus stempel pada halaman yang ditentukan berdasarkan beberapa ID stempel.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Nomor halaman tempat stempel akan dihapus. |
| stampIds | Int32[] | Array ID stempel. |

## Contoh

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Lihat Juga

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


