---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Modifica le preferenze di visualizzazione"
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

Modifica le preferenze di visualizzazione.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| viewerAttribution | Int32 | L'attribuzione di visualizzazione definita nella classe ViewerPreference. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


