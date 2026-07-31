---
title: "PdfBookmarkEditor.ExtractBookmarks"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfBookmarkEditor. Mengekstrak bookmark dari semua level dalam dokumen"
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Mengekstrak bookmark dari semua level dalam dokumen.

```csharp
public Bookmarks ExtractBookmarks()
```

### Nilai Kembalian

Koleksi bookmark dari semua bookmark yang ada dalam dokumen.

## Contoh

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Lihat Juga

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Mengekstrak bookmark dari semua level dalam dokumen.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| upperLevel | Boolean | Jika true, mengekstrak hanya bookmark level atas. Jika tidak, mengekstrak semua bookmark secara rekursif. |

### Nilai Kembalian

Daftar bookmark yang diekstrak.

### Lihat Juga

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Mengekstrak bookmark dengan judul yang ditentukan.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| title | String | Judul item yang diekstrak. |

### Nilai Kembalian

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

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Mengekstrak anak‑anak bookmark dengan judul seperti pada bookmark yang ditentukan.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bookmark | Bookmark | Bookmark yang ditentukan. |

### Nilai Kembalian

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

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


