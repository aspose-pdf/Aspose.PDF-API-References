---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Crea un marcador para la página especificada
type: docs
weight: 20
url: /es/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Crea un marcador para la página especificada.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bookmarkName | String | El nombre del marcador especificado. |
| pageNumber | Int32 | La página de destino especificada. |

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Crea marcadores para las páginas especificadas.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bookmarkName | String[] | Array de títulos de marcadores. |
| pageNumber | Int32[] | Array de páginas de destino de marcadores. |

## Ejemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfBookmarkEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)