---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor metod. Returnerar visningspreferensen"
type: docs
weight: 390
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

Returnerar visningspreferensen.

```csharp
public int GetViewerPreference()
```

### Returvärde

Returnerar en uppsättning av ViewerPrefernece-flaggor

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


