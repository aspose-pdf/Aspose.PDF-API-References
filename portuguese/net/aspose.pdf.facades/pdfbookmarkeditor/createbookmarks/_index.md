---
title: PdfBookmarkEditor.CreateBookmarks
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Cria marcadores para todas as páginas
type: docs
weight: 30
url: /pt/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/
---
## CreateBookmarks() {#createbookmarks}

Cria marcadores para todas as páginas.

```csharp
public void CreateBookmarks()
```

## Exemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks();
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Bookmark) {#createbookmarks_1}

Cria o marcador especificado no documento. O método pode ser usado para formar uma hierarquia de marcadores aninhados.

```csharp
public void CreateBookmarks(Bookmark bookmark)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bookmark | Bookmark | O marcador será adicionado ao documento. |

## Exemplos

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

### Veja Também

* classe [Bookmark](../../bookmark/)
* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarks(Color, bool, bool) {#createbookmarks_2}

Cria marcadores para todas as páginas com a cor e estilo especificados (negrito, itálico).

```csharp
public void CreateBookmarks(Color color, bool boldFlag, bool italicFlag)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| color | Color | A cor do título. |
| boldFlag | Boolean | O indicador de atribuição em negrito. |
| italicFlag | Boolean | O indicador de atribuição em itálico. |

## Exemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarks(System.Drawing.Color.Red, true, true);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)