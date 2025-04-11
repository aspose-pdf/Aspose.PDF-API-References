---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation de ligne
type: docs
weight: 180
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## Méthode PdfContentEditor.CreateLine

Crée une annotation de ligne.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| contents | String | Le contenu de l'annotation. |
| x1 | Single | La coordonnée horizontale de départ de la ligne. |
| y1 | Single | La coordonnée verticale de départ de la ligne. |
| x2 | Single | La coordonnée horizontale de fin de la ligne. |
| y2 | Single | La coordonnée verticale de fin de la ligne. |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |
| border | Int32 | La largeur de la bordure en points. Si cette valeur est 0, aucune bordure n'est dessinée. La valeur par défaut est 1. |
| clr | Color | La couleur de la ligne. |
| borderStyle | String | Le style de bordure spécifiant la largeur et le motif de tirets à utiliser pour dessiner la ligne. Cette valeur peut être : "S" (Solide), "D" (Tireté), "B" (Biseauté), "I" (Encastré), "U" (Souligné). |
| dashArray | Int32[] | Un tableau de tirets définissant un motif de tirets et d'espaces à utiliser pour dessiner une bordure en tirets. S'il est utilisé, borderSyle doit être réglé sur "D". |
| LEArray | String[] | Un tableau de deux valeurs spécifiant respectivement le style de début et de fin de la ligne dessinée. Les valeurs peuvent être : "Carré", "Cercle", "Diamant", "FlècheOuverte", "FlècheFermée", "Aucun", "Bout", "FlècheOuverteD", "FlècheFerméeD", "BarreOblique". |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Voir aussi

* classe [PdfContentEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)