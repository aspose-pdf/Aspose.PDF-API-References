---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metod. Ändrar visningspreferensen
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference metod

Ändrar visningspreferensen.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| viewerAttribution | Int32 | Den visningsattribution som definieras i ViewerPreference-klassen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfContentEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)