---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Remplace l'image spécifiée sur la page spécifiée du document PDF par une autre image
type: docs
weight: 440
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## Méthode PdfContentEditor.ReplaceImage

Remplace l'image spécifiée sur la page spécifiée du document PDF par une autre image.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro de la page sur laquelle l'image est remplacée. |
| index | Int32 | L'index de l'objet image à remplacer. |
| imageFile | String | Le fichier image qui sera utilisé pour le remplacement. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)