---
title: "PdfBookmarkEditor.CreateBookmarks"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfBookmarkEditor. Crea segnalibri per tutte le pagine"
type: docs
weight: 30
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Crea segnalibri per tutte le pagine.

```csharp
public void CreateBookmarks()
```

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Crea il segnalibro specificato nel Document. Il metodo può essere utilizzato per formare una gerarchia di segnalibri nidificati.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bookmark | Bookmark | Il segnalibro verrà aggiunto al documento. |

## Esempi

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

### Vedi anche

* class [Bookmark](../../bookmark/)
* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Crea segnalibri per tutte le pagine con colore e stile specificati (grassetto, corsivo).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | Color | Il colore del titolo. |
| boldFlag | Boolean | Il flag di attribuzione grassetto. |
| italicFlag | Boolean | Il flag di attribuzione corsivo. |

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


