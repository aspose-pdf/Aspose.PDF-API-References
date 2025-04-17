---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfAnnotationEditor. Modifie les annotations du type spécifié sur la plage de pages spécifiée. Elle permet de modifier les propriétés suivantes des annotations  Modifié, Titre, Contenu, Couleur, Sujet et Ouvert.
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## Méthode PdfAnnotationEditor.ModifyAnnotations

Modifie les annotations du type spécifié sur la plage de pages spécifiée. Elle permet de modifier les propriétés suivantes des annotations : Modifié, Titre, Contenu, Couleur, Sujet et Ouvert.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| start | Int32 | Le numéro de la page de début. |
| end | Int32 | Le numéro de la page de fin. |
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

* classe [Annotation](../../../aspose.pdf.annotations/annotation/)
* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)