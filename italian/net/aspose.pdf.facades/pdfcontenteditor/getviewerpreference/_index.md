---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Restituisce la preferenza di visualizzazione"
type: docs
weight: 390
url: /it/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

Restituisce la preferenza di visualizzazione.

```csharp
public int GetViewerPreference()
```

### Valore di ritorno

Restituisce l'insieme di flag ViewerPrefernece

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


