---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfBookmarkEditor. Crea un segnalibro per la pagina specificata
type: docs
weight: 20
url: /it/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Crea un segnalibro per la pagina specificata.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bookmarkName | String | Il nome del segnalibro specificato. |
| pageNumber | Int32 | La pagina di destinazione specificata. |

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Crea segnalibri per le pagine specificate.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bookmarkName | String[] | Array dei titoli dei segnalibri. |
| pageNumber | Int32[] | Array delle pagine di destinazione dei segnalibri. |

## Esempi

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)