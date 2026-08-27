---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FreeTextAnnotation. Définit le formatage déterminé par le paramètre textStyle pour tout le texte de l'annotation"
type: docs
weight: 150
url: /fr/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

Définit le formatage déterminé par le paramètre textStyle pour tout le texte de l'annotation.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Style(s) appliqué(s) au texte de l'annotation. |
| fontName | String | Nom de police appliqué au texte de l'annotation. |
| fontSize | Double | Taille de police appliquée au texte de l'annotation. |
| fontColor | Color | Couleur de police appliquée au texte de l'annotation. |

### Voir aussi

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

Définit le formatage déterminé par le paramètre textStyle pour un fragment de texte de l'index fromInd à l'index toInd.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fromInd | Int32 | Indice de départ du fragment de texte (à partir de 0). |
| toInd | Int32 | Indice de fin du fragment de texte (en comptant à partir de 0, cet indice n'est pas inclus). |
| textStyles | RichTextFontStyles | Style(s) appliqué(s) au fragment de texte. |

### Voir aussi

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


