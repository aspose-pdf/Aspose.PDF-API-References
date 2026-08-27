---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor-metod. Modifierar annoteringarna av den angivna typen inom det angivna sidintervallet. Den stöder att ändra följande annoteringsegenskaper: Modifierad, Titel, Innehåll, Färg, Ämne och Öppen."
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

Modifierar annotationerna av den angivna typen på det angivna sidintervallet. Det stöder att ändra följande annotationsegenskaper: Modified, Title, Contents, Color, Subject och Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Startsidans nummer. |
| end | Int32 | Det sista sidnumret. |
| annotation | Annotation | Annotation-objektet innehåller nya egenskaper. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### Se även

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


