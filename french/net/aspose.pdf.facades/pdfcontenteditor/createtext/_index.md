---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation de texte dans un document PDF
type: docs
weight: 290
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## Méthode PdfContentEditor.CreateText

Crée une annotation de texte dans un document PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| title | String | Le titre de l'annotation. |
| contents | String | Le contenu de l'annotation. |
| open | Boolean | Un indicateur spécifiant si l'annotation doit être affichée initialement ouverte. |
| icon | String | Le nom d'une icône qui sera utilisée pour afficher l'annotation. Cette valeur peut être : "Commentaire", "Clé", "Note", "Aide", "NouveauParagraphe", "Paragraphe", "Insérer" |
| page | Int32 | Le numéro de la page originale où l'annotation de texte sera créée. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)