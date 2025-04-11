---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metodu. Belgedeki tüm seviyelerdeki yer imlerini çıkarır
type: docs
weight: 60
url: /tr/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Belgedeki tüm seviyelerdeki yer imlerini çıkarır.

```csharp
public Bookmarks ExtractBookmarks()
```

### Dönüş Değeri

Belgedeki mevcut tüm yer imlerinin koleksiyonu.

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Ayrıca Bakınız

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Belgedeki tüm seviyelerdeki yer imlerini çıkarır.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| upperLevel | Boolean | Eğer doğruysa, yalnızca üst seviye yer imlerini çıkarır. Aksi takdirde, tüm yer imlerini özyinelemeli olarak çıkarır. |

### Dönüş Değeri

Çıkarılan yer imlerinin listesi.

### Ayrıca Bakınız

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Belirtilen başlığa sahip yer imlerini çıkarır.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| title | String | Çıkarılan öğe başlığı. |

### Dönüş Değeri

Aynı başlığa sahip yer imlerini içeren koleksiyon.

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Ayrıca Bakınız

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Belirtilen yer imindeki başlığa benzer bir yer iminin çocuklarını çıkarır.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bookmark | Bookmark | Belirtilen yer imi. |

### Dönüş Değeri

Çocuk yer imleri ile birlikte yer imi koleksiyonu.

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Ayrıca Bakınız

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)