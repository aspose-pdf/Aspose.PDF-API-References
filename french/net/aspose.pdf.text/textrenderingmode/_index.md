---
title: Enum TextRenderingMode
second_title: Aspose.PDF for .NET API Reference
description: Enum TextRenderingMode d'Aspose.Pdf.Text. Le mode de rendu du texte Tmode détermine si l'affichage du texte doit entraîner le traçage des contours des glyphes, leur remplissage, leur utilisation comme limite de découpe ou une combinaison des trois.
type: docs
weight: 11000
url: /fr/net/aspose.pdf.text/textrenderingmode/
---
## Énumération TextRenderingMode

Le mode de rendu du texte, Tmode, détermine si l'affichage du texte doit entraîner le traçage des contours des glyphes, leur remplissage, leur utilisation comme limite de découpe ou une combinaison des trois.

```csharp
public enum TextRenderingMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| FillText | `0` | Remplir le texte. |
| StrokeText | `1` | Traçer le texte. |
| FillThenStrokeText | `2` | Remplir, puis tracer le texte. |
| Invisible | `3` | Ni remplir ni tracer le texte (invisible). |
| FillTextAndAddPathToClipping | `4` | Remplir le texte et ajouter au chemin pour la découpe (voir 9.3.6, "Mode de rendu du texte"). |
| StrokeTextAndAddPathToClipping | `5` | Traçer le texte et ajouter au chemin pour la découpe. |
| FillThenStrokeTextAndAddPathToClipping | `6` | Remplir, puis tracer le texte et ajouter au chemin pour la découpe. |
| AddPathToClipping | `7` | Ajouter le texte au chemin pour la découpe. |

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)