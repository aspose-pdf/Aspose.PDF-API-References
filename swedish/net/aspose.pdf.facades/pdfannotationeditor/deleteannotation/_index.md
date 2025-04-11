---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-metod. Tar bort annoteringen med angivet annoteringsnamn
type: docs
weight: 20
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation metod

Tar bort annoteringen med angivet annoteringsnamn.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotName | Sträng | Annoteringsnamnet |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)