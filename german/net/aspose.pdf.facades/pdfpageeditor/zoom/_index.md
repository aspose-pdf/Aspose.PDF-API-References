---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor-Eigenschaft. Ruft den Zoomkoeffizienten ab oder legt ihn fest. Der Wert 1.0 entspricht 100. Der Standardwert ist 1.0. Das folgende Beispiel zeigt, wie man den Zoom der Dokumentseiten ändert.
type: docs
weight: 110
url: /de/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## PdfPageEditor.Zoom-Eigenschaft

Ruft den Zoomkoeffizienten ab oder legt ihn fest. Der Wert 1.0 entspricht 100%. Der Standardwert ist 1.0. Das folgende Beispiel zeigt, wie man den Zoom der Dokumentseiten ändert.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### Siehe auch

* Klasse [PdfPageEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)