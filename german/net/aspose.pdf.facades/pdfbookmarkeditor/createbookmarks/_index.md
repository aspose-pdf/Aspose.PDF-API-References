---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor-Methode. Erstellt Lesezeichen für alle Seiten
type: docs
weight: 30
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Erstellt Lesezeichen für alle Seiten.

```csharp
public void CreateBookmarks()
```

## Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Erstellt das angegebene Lesezeichen im Dokument. Die Methode kann verwendet werden, um eine verschachtelte Lesezeichenhierarchie zu bilden.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bookmark | Bookmark | Das Lesezeichen wird dem Dokument hinzugefügt. |

## Beispiele

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

### Siehe auch

* Klasse [Bookmark](../../bookmark/)
* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Erstellt Lesezeichen für alle Seiten mit der angegebenen Farbe und dem Stil (fett, kursiv).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | Color | Die Farbe des Titels. |
| boldFlag | Boolean | Das Flag für fette Zuschreibung. |
| italicFlag | Boolean | Das Flag für kursive Zuschreibung. |

## Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)