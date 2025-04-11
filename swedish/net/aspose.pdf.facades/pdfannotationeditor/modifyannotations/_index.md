---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-metod. Modifierar annotationerna av den angivna typen på det angivna sidintervallet. Den stöder att modifiera följande annotationsegenskaper: Modifierad, Titel, Innehåll, Färg, Ämne och Öppen
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations metod

Modifierar annotationerna av den angivna typen på det angivna sidintervallet. Den stöder att modifiera följande annotationsegenskaper: Modifierad, Titel, Innehåll, Färg, Ämne och Öppen.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Det första sidnumret. |
| end | Int32 | Det sista sidnumret. |
| annotation | Annotation | Annoteringen objektet innehåller nya egenskaper. |

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

### Se Även

* klass [Annotation](../../../aspose.pdf.annotations/annotation/)
* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)