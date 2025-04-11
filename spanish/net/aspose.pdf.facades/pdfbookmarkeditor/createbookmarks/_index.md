---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Crea marcadores para todas las páginas
type: docs
weight: 30
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Crea marcadores para todas las páginas.

```csharp
public void CreateBookmarks()
```

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Crea el marcador especificado en el documento. El método se puede usar para formar una jerarquía de marcadores anidados.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bookmark | Bookmark | El marcador se añadirá al documento. |

## Ejemplos

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

### Ver También

* clase [Bookmark](../../bookmark/)
* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Crea marcadores para todas las páginas con el color y estilo especificados (negrita, cursiva).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | Color | El color del título. |
| boldFlag | Boolean | La bandera de atribución en negrita. |
| italicFlag | Boolean | La bandera de atribución en cursiva. |

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)