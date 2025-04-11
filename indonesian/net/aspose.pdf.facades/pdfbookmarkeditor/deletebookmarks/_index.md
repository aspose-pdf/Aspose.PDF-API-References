---
title: PdfBookmarkEditor.DeleteBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfBookmarkEditor. Menghapus semua bookmark dari dokumen PDF
type: docs
weight: 40
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

Menghapus semua bookmark dari dokumen PDF.

```csharp
public void DeleteBookmarks()
```

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

Menghapus bookmark dari dokumen PDF.

```csharp
public void DeleteBookmarks(string title)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| title | String | Judul bookmark yang dihapus. |

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)