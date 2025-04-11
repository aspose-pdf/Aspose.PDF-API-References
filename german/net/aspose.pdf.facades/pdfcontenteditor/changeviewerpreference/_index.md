---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Ändert die Ansichtseinstellung
type: docs
weight: 90
url: /de/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## PdfContentEditor.ChangeViewerPreference-Methode

Ändert die Ansichtseinstellung.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| viewerAttribution | Int32 | Die Ansichtseinstellung, die in der Klasse ViewerPreference definiert ist. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)