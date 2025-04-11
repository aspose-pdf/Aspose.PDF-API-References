---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfAnnotationEditor. Modifie l'auteur des annotations sur la plage de pages spécifiée
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## Méthode PdfAnnotationEditor.ModifyAnnotationsAuthor

Modifie l'auteur des annotations sur la plage de pages spécifiée.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| start | Int32 | Le numéro de la page de départ. |
| end | Int32 | Le numéro de la page de fin. |
| srcAuthor | String | L'auteur qui doit être modifié. |
| desAuthor | String | Le nouvel auteur. |

## Exemples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfAnnotationEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)