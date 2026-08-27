---
title: "PdfContentEditor.CreateText"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfContentEditor. Crée une annotation de texte dans le document PDF"
type: docs
weight: 290
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

Crée une annotation de texte dans le document PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| title | String | Le titre de l'annotation. |
| contents | String | Le contenu de l'annotation. |
| open | Boolean | Un indicateur spécifiant si l'annotation doit être affichée ouverte initialement. |
| icon | String | Le nom d'une icône sera utilisé pour afficher l'annotation. Cette valeur peut être : "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| page | Int32 | Le numéro de la page d'origine où l'annotation de texte sera créée. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


