---
title: "PdfBookmarkEditor.ExtractBookmarks"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfBookmarkEditor metod. Extraherar bokmärken på alla nivåer från dokumentet"
type: docs
weight: 60
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/
---
## ExtractBookmarks() {#extractbookmarks}

Extraherar bokmärken på alla nivåer från dokumentet.

```csharp
public Bookmarks ExtractBookmarks()
```

### Returvärde

Bokmärkeskollektionen av alla bokmärken som finns i dokumentet.

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks();
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Se även

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(bool) {#extractbookmarks_2}

Extraherar bokmärken på alla nivåer från dokumentet.

```csharp
public Bookmarks ExtractBookmarks(bool upperLevel)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| upperLevel | Boolean | Om true, extraherar endast överordnade bokmärken. Annars extraheras alla bokmärken rekursivt. |

### Returvärde

Lista över extraherade bokmärken.

### Se även

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

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| titel | String | Extraherad objekttitel. |

### Returvärde

Bokmärkeskollektionen har objekt med samma titel.

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmarks bms = editor.ExtractBookmarks("Title");
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Se även

* class [Bookmarks](../../bookmarks/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractBookmarks(Bookmark) {#extractbookmarks_1}

Extraherar underordnade till ett bokmärke med en titel som i det angivna bokmärket.

```csharp
public Bookmarks ExtractBookmarks(Bookmark bookmark)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bokmärke | Bokmärke | Det angivna bokmärket. |

### Returvärde

Bokmärkeskollektion med underbokmärken.

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
Bookmark bookmark = new Bookmark();
bookmark.Title = "Title";
Bookmarks bms = editor.ExtractBookmarks(bookmark);
foreach(Bookmark bm in bms)
    Console.WriteLine(bm.Title);
```

### Se även

* class [Bookmarks](../../bookmarks/)
* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


