---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfBookmarkEditor. Mengekstrak bookmark dari semua level dari dokumen
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## EkstrakBookmark() {#extractbookmarks}

Mengekstrak bookmark dari semua level dari dokumen.

```csharp
public Bookmarks ExtractBookmarks()
```

### Nilai Kembali

Koleksi bookmark dari semua bookmark yang ada di dokumen.

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Lihat Juga

* kelas [Bookmarks](../../bookmarks/)
* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EkstrakBookmark(bool) {#extractbookmarks_2}

Mengekstrak bookmark dari semua level dari dokumen.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| upperLevel | Boolean | Jika true, hanya mengekstrak bookmark level atas. Jika tidak, mengekstrak semua bookmark secara rekursif. |

### Nilai Kembali

Daftar bookmark yang diekstrak.

### Lihat Juga

* kelas [Bookmarks](../../bookmarks/)
* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EkstrakBookmark(string) {#extractbookmarks_3}

Mengekstrak bookmark dengan judul yang ditentukan.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| title | String | Judul item yang diekstrak. |

### Nilai Kembali

Koleksi bookmark memiliki item dengan judul yang sama.

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Lihat Juga

* kelas [Bookmarks](../../bookmarks/)
* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EkstrakBookmark(Bookmark) {#extractbookmarks_1}

Mengekstrak anak-anak dari bookmark dengan judul seperti di bookmark yang ditentukan.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bookmark | Bookmark | Bookmark yang ditentukan. |

### Nilai Kembali

Koleksi bookmark dengan bookmark anak.

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Lihat Juga

* kelas [Bookmarks](../../bookmarks/)
* kelas [Bookmark](../../bookmark/)
* kelas [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)