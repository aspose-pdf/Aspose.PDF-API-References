---
title: PdfPageEditor.GetPageSize
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor method. Returns the page size of the specified page
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## Metodo PdfPageEditor.GetPageSize

Restituisce la dimensione della pagina della pagina specificata.

```csharp
public PageSize GetPageSize(int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Indice della pagina. Le pagine del documento sono numerate a partire da 1. |

### Valore di ritorno

Il risultato è un'istanza di PageSize. Utilizzare le proprietà Width e Height dell'oggetto restituito per ottenere la larghezza e l'altezza della pagina.

## Esempi

Il seguente esempio dimostra l'uso del metodo GetPageSize:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### Vedi Anche

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)