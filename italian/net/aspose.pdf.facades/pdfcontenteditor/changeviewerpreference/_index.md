---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Cambia la preferenza di visualizzazione
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## Metodo PdfContentEditor.ChangeViewerPreference

Cambia la preferenza di visualizzazione.

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

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)