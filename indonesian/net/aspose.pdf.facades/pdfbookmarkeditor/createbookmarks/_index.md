---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfBookmarkEditor. Membuat bookmark untuk semua halaman
type: docs
weight: 30
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Membuat bookmark untuk semua halaman.

```csharp
public void CreateBookmarks()
```

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Membuat bookmark yang ditentukan dalam dokumen. Metode ini dapat digunakan untuk membentuk hierarki bookmark bersarang.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bookmark | Bookmark | Bookmark akan ditambahkan ke dokumen. |

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bm1=new Bookmark();
bm1.PageNumber=1;
bm1.Title="First child";
Bookmark bm2=new Bookmark();
bm2.PageNumber=2;
bm2.Title="Second child";
Bookmark bm=new Bookmark();
bm.Action="GoTo";
bm.PageNumber=1;
bm.Title="Parent";
Bookmarks bms=new Bookmarks();
bms.Add(bm1);
bms.Add(bm2);
bm.ChildItem=bms;
editor.CreateBookmarks(bm);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [Bookmark](../../bookmark/)
* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Buat bookmark untuk semua halaman dengan warna dan gaya yang ditentukan (tebal, miring).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| color | Color | Warna judul. |
| boldFlag | Boolean | Bendera atribusi tebal. |
| italicFlag | Boolean | Bendera atribusi miring. |

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)