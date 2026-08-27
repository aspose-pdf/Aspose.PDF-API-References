---
title: "PdfContentEditor.ReplaceImage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Remplace l'image spécifiée sur la page spécifiée du document PDF par une autre image"
type: docs
weight: 440
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage method

Remplace l'image spécifiée sur la page spécifiée du document PDF par une autre image.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro de la page sur laquelle l'image est remplacée. |
| index | Int32 | L'index de l'objet image à remplacer. |
| imageFile | String | Le fichier image sera utilisé pour le remplacement. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


