---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfBookmarkEditor. Membuat bookmark untuk halaman yang ditentukan
type: docs
weight: 20
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Membuat bookmark untuk halaman yang ditentukan.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bookmarkName | String | Nama bookmark yang ditentukan. |
| pageNumber | Int32 | Halaman tujuan yang ditentukan. |

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Membuat bookmark untuk halaman yang ditentukan.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bookmarkName | String[] | Array judul bookmark. |
| pageNumber | Int32[] | Array halaman tujuan bookmark. |

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)