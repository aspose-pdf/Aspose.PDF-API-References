---
title: PdfBookmarkEditor.ExtractBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor-metod. Extraherar bokmärken av alla nivåer från dokumentet
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Extraherar bokmärken av alla nivåer från dokumentet.

```csharp
public Bookmarks ExtractBookmarks()
```

### Return Value

Samlingen av bokmärken som finns i dokumentet.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Extraherar bokmärken av alla nivåer från dokumentet.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel | Boolean | Om sant, extraherar endast övre nivå bokmärken. Annars, extraherar alla bokmärken rekursivt. |

### Return Value

Lista över extraherade bokmärken.

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(string) {#extractbookmarks_3}

Extraherar bokmärken med den angivna titeln.

```csharp
public Bookmarks ExtractBookmarks(string title)
```

| Parameter | Type | Description |
| --- | --- | --- |
| title | String | Titel på det extraherade objektet. |

### Return Value

Bokmärkeskollektion har objekt med samma titel.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Extraherar barn till ett bokmärke med en titel som i det angivna bokmärket.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | Bookmark | Det angivna bokmärket. |

### Return Value

Bokmärkeskollektion med barnbokmärken.

## Examples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### See Also

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)