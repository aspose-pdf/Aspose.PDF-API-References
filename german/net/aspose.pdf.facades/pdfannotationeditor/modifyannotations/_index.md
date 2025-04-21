---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor-Methode. Modifiziert die Annotationen des angegebenen Typs im angegebenen Seitenbereich. Es unterstützt die Modifikation der nächsten Annotations-Eigenschaften Modifiziert, Titel, Inhalte, Farbe, Betreff und Offen
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations-Methode

Modifiziert die Annotationen des angegebenen Typs im angegebenen Seitenbereich. Es unterstützt die Modifikation der nächsten Annotations-Eigenschaften: Modifiziert, Titel, Inhalte, Farbe, Betreff und Offen.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| start | Int32 | Die Startseitenzahl. |
| end | Int32 | Die Endseitenzahl. |
| annotation | Annotation | Das Annotationsobjekt enthält neue Eigenschaften. |

## Beispiele

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

### Siehe auch

* Klasse [Annotation](../../../aspose.pdf.annotations/annotation/)
* Klasse [PdfAnnotationEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)