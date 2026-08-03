---
title: "PdfAnnotationEditor.DeleteAnnotation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor metod. Raderar annotationen med angivet annotationsnamn"
type: docs
weight: 20
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation method

Tar bort Annotation med angivet Annotation‑namn.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| annotName | String | Annoteringens namn |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


