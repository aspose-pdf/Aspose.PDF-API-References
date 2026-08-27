---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfAnnotationEditor. Modifie les annotations du type spécifié sur la plage de pages spécifiée. Elle permet de modifier les propriétés d'annotation suivantes : Modified Title Contents Color Subject et Open."
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

Modifie les annotations du type spécifié sur la plage de pages spécifiée. Il prend en charge la modification des propriétés d'annotation suivantes : Modified, Title, Contents, Color, Subject et Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| start | Int32 | Le numéro de page de début. |
| end | Int32 | Le numéro de page de fin. |
| annotation | Annotation | L'objet annotation contient de nouvelles propriétés. |

## Exemples

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

### Voir aussi

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


