---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfBookmarkEditor. Crée des signets pour toutes les pages
type: docs
weight: 30
url: /fr/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Crée des signets pour toutes les pages.

```csharp
public void CreateBookmarks()
```

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfBookmarkEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Crée le signet spécifié dans le document. La méthode peut être utilisée pour former une hiérarchie de signets imbriqués.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| bookmark | Bookmark | Le signet sera ajouté au document. |

## Exemples

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

### Voir aussi

* classe [Bookmark](../../bookmark/)
* classe [PdfBookmarkEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Crée des signets pour toutes les pages avec la couleur et le style spécifiés (gras, italique).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| color | Color | La couleur du titre. |
| boldFlag | Boolean | Le drapeau d'attribution en gras. |
| italicFlag | Boolean | Le drapeau d'attribution en italique. |

## Exemples

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfBookmarkEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)