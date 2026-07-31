---
title: "PdfPageEditor.GetPageBoxSize"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfPageEditor. Restituisce la dimensione della casella specificata nel documento"
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdfpageeditor/getpageboxsize/
---
## PdfPageEditor.GetPageBoxSize method

Restituisce la dimensione della casella specificata nel documento.

```csharp
public Rectangle GetPageBoxSize(int page, string pageBoxName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Int32 | Indice della pagina. Le pagine del documento sono numerate a partire da 1. |
| pageBoxName | String | Nome del tipo di casella. I valori validi sono: "art", "bleed", "crop", "media", "trim". |

### Valore di ritorno

Rectangle che contiene la casella richiesta.

## Esempi

Il seguente esempio dimostra come ottenere la media box della prima pagina:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
System.Drawing.Rectangle rect = editor.GetBoxSize(1, "media");
```

### Vedi anche

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


