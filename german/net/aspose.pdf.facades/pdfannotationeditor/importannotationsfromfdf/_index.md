---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-Methode. Importiert alle Anmerkungen aus der FDF-Datei
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf-Methode

Importiert alle Anmerkungen aus der FDF-Datei.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fdfFile | String | Die Eingabe-FDF-Datei. |

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)