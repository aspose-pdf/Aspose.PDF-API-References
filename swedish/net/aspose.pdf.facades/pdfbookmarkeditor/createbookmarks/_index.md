---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor-metod. Skapar bokmärken för alla sidor
type: docs
weight: 30
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Skapar bokmärken för alla sidor.

```csharp
public void CreateBookmarks()
```

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Skapar det angivna bokmärket i dokumentet. Metoden kan användas för att bilda en hierarki av nästlade bokmärken.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bookmark | Bookmark | Bokmärket kommer att läggas till i dokumentet. |

## Exempel

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

### Se Även

* klass [Bookmark](../../bookmark/)
* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Skapa bokmärken för alla sidor med angiven färg och stil (fet, kursiv).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | Color | Färgen på titeln. |
| boldFlag | Boolean | Flaggan för fet stil. |
| italicFlag | Boolean | Flaggan för kursiv stil. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfBookmarkEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)