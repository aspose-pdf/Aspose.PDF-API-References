---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfBookmarkEditor. Cria um marcador para a página especificada
type: docs
weight: 20
url: /pt/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CriarMarcadorDaPagina(string, int) {#createbookmarkofpage}

Cria um marcador para a página especificada.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bookmarkName | String | O nome do marcador especificado. |
| pageNumber | Int32 | A página de destino especificada. |

## Exemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CriarMarcadorDaPagina(string[], int[]) {#createbookmarkofpage_1}

Cria marcadores para as páginas especificadas.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bookmarkName | String[] | Array de títulos dos marcadores. |
| pageNumber | Int32[] | Array de páginas de destino dos marcadores. |

## Exemplos

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)