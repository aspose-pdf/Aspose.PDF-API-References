---
title: "PdfContentEditor.GetViewerPreference"
linktitle: "GetViewerPreference"
articleTitle: "GetViewerPreference"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Returns the view preference."
type: docs
weight: 430
url: "/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/"
product_version: "26.9"
---
## PdfContentEditor.GetViewerPreference method

Returns the view preference.

```csharp
public int GetViewerPreference()
```

### Return Value

Returns set of ViewerPrefernece flags

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

