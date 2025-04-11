---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-Methode. Löscht die Annotation mit dem angegebenen Annotationsnamen
type: docs
weight: 20
url: /de/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation-Methode

Löscht die Annotation mit dem angegebenen Annotationsnamen.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| annotName | String | Der Annotationsname |

## Beispiele

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)