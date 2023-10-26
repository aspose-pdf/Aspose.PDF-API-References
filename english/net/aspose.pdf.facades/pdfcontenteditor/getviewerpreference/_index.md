---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Returns the view preference
type: docs
weight: 390
url: /net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


