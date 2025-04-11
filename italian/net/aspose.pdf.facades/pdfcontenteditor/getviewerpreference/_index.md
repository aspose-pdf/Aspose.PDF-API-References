---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodo. Ritorna la preferenza della vista.
type: docs
weight: 390
url: /it/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## Metodo PdfContentEditor.GetViewerPreference

Restituisce la preferenza di visualizzazione.

```csharp
public int GetViewerPreference()
```

### Valore di Ritorno

Restituisce un insieme di flag ViewerPrefernece

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)