---
title: "PdfContentEditor.ChangeViewerPreference"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfContentEditor‑metod. Ändrar visningsinställningen."
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference method

Ändrar visningsinställningen.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| viewerAttribution | Int32 | Visningsattributet som definieras i ViewerPreference‑klassen. |

## Exempel

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


