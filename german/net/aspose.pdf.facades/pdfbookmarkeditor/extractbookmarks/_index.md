---
title: ExtractBookmarks
second_title: Aspose.PDF für .NET-API-Referenz
description: Extrahiert Lesezeichen aller Ebenen aus dem Dokument.
type: docs
weight: 60
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Extrahiert Lesezeichen aller Ebenen aus dem Dokument.

```csharp
public Bookmarks ExtractBookmarks()
```

### Rückgabewert

Die Lesezeichensammlung aller Lesezeichen, die im Dokument vorhanden sind.

### Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Siehe auch

* class [Bookmarks](../../bookmarks)
* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namensraum [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* Montage [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Extrahiert Lesezeichen aller Ebenen aus dem Dokument.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| upperLevel | Boolean | Wenn wahr, werden nur Lesezeichen der oberen Ebene extrahiert. Andernfalls werden alle Lesezeichen rekursiv extrahiert. |

### Rückgabewert

Liste der extrahierten Lesezeichen.

### Siehe auch

* class [Bookmarks](../../bookmarks)
* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namensraum [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* Montage [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Extrahiert die Lesezeichen mit dem angegebenen Titel.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| title | String | Titel des extrahierten Elements. |

### Rückgabewert

Die Lesezeichensammlung enthält Elemente mit demselben Titel.

### Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Siehe auch

* class [Bookmarks](../../bookmarks)
* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namensraum [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* Montage [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Extrahiert die Kinder eines Lesezeichens mit einem Titel wie im angegebenen bookamrk.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bookmark | Bookmark | Das angegebene Lesezeichen. |

### Rückgabewert

Lesezeichensammlung mit untergeordneten Lesezeichen.

### Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Siehe auch

* class [Bookmarks](../../bookmarks)
* class [Bookmark](../../bookmark)
* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* namensraum [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->