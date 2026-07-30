---
title: "PdfContentEditor.CreatePopup"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Crée une annotation popup dans le document PDF"
type: docs
weight: 250
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

Crée une annotation popup dans le document PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| open | Boolean | Un indicateur spécifiant si l'annotation pop-up doit être affichée ouverte initialement. |
| page | Int32 | Le numéro de la page d'origine où l'annotation sera créée. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


