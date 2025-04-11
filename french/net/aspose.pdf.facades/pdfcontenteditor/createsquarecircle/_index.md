---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation carré-cercle
type: docs
weight: 280
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## Méthode PdfContentEditor.CreateSquareCircle

Crée une annotation carré-cercle.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| clr | Color | La couleur du carré ou du cercle. |
| square | Boolean | Vrai (carré), faux (cercle). |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |
| borderWidth | Int32 | La largeur de la bordure du carré ou du cercle. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)