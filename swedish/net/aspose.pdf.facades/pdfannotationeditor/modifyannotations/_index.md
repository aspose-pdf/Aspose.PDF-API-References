---
title: ModifyAnnotations
second_title: Aspose.PDF för .NET API Referens
description: Modifierar anteckningarna av den angivna typen på det angivna sidintervallet. Det stöder att ändra nästa anteckningsegenskaper Modifierad Titel Innehåll Färg Ämne och Öppna.
type: docs
weight: 110
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

Modifierar anteckningarna av den angivna typen på det angivna sidintervallet. Det stöder att ändra nästa anteckningsegenskaper: Modifierad, Titel, Innehåll, Färg, Ämne och Öppna.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start | Int32 | Startsidans nummer. |
| end | Int32 | Slutsidans nummer. |
| annotation | Annotation | Anteckningsobjektet innehåller nya egenskaper. |

### Exempel

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

* class [Annotation](../../../aspose.pdf.annotations/annotation)
* class [PdfAnnotationEditor](../../pdfannotationeditor)
* namnutrymme [Aspose.Pdf.Facades](../../pdfannotationeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->