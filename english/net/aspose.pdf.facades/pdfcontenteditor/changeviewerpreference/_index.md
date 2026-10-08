---
title: "PdfContentEditor.ChangeViewerPreference"
linktitle: "ChangeViewerPreference"
articleTitle: "ChangeViewerPreference"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Changes the view preference."
type: docs
weight: 420
url: "/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/"
product_version: "26.9"
---
## PdfContentEditor.ChangeViewerPreference method

Changes the view preference.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parameter | Type | Description |
| --- | --- | --- |
| viewerAttribution | Int32 | The view attribution defined in the ViewerPreference class. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

