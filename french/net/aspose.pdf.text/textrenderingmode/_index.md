---
title: "Enum TextRenderingMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Text.TextRenderingMode enum. Le mode de rendu du texte Tmode détermine si l'affichage du texte doit entraîner le tracé des contours des glyphes, le remplissage, l'utilisation comme limite de découpe ou une combinaison des trois."
type: docs
weight: 11180
url: /fr/net/aspose.pdf.text/textrenderingmode/
---
## TextRenderingMode enumeration

Le mode de rendu du texte, Tmode, détermine si l'affichage du texte doit entraîner le tracé des contours des glyphes, leur remplissage, leur utilisation comme limite de découpe, ou une combinaison de ces trois options.

```csharp
public enum TextRenderingMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| FillText | `0` | Remplir le texte. |
| StrokeText | `1` | Tracer le texte. |
| FillThenStrokeText | `2` | Remplir, puis tracer le texte. |
| Invisible | `3` | Ni remplissage ni tracé du texte (invisible). |
| FillTextAndAddPathToClipping | `4` | Remplir le texte et l'ajouter au chemin pour la découpe (voir 9.3.6, "Text Rendering Mode,"). |
| StrokeTextAndAddPathToClipping | `5` | Tracer le texte et l'ajouter au chemin pour la découpe. |
| FillThenStrokeTextAndAddPathToClipping | `6` | Remplir, puis tracer le texte et l'ajouter au chemin pour la découpe. |
| AddPathToClipping | `7` | Ajouter le texte au chemin pour la découpe. |

### Voir aussi

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


