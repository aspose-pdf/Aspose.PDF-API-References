---
title: PdfPageEditor.GetPageBoxSize
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfPageEditor. Restituisce la dimensione della casella specificata nel documento
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## Metodo PdfPageEditor.GetPageBoxSize

Restituisce la dimensione della casella specificata nel documento.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Indice della pagina. Le pagine del documento sono numerate a partire da 1. |
| pageBoxName | String | Nome del tipo di casella. I valori validi sono: "art", "bleed", "crop", "media", "trim". |

### Valore di Ritorno

Rettangolo che contiene la casella richiesta.

## Esempi

Il seguente esempio dimostra come ottenere la casella media della 1ª pagina:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Vedi Anche

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)