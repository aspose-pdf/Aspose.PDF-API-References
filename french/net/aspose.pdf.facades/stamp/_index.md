---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.Stamp. Classe représentant un tampon
type: docs
weight: 4720
url: /fr/net/aspose.pdf.facades/stamp/
---
## Classe Stamp

Classe représentant un tampon.

```csharp
public sealed class Stamp
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Stamp](stamp/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Obtient ou définit une valeur BlendingColorSpace qui définit un espace colorimétrique utilisé pour effectuer des opérations de transparence et de mélange sur la page. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Obtient ou définit l'état de fond. Si vrai, le tampon sera placé en arrière-plan de la page tamponnée. Par défaut, il est défini sur faux. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Obtient ou définit l'opacité du tampon. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Obtient ou définit le numéro de page. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Obtient ou définit un tableau avec les numéros de pages qui seront affectées par le tampon. Si Pages = null, toutes les pages du document sont affectées. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Obtient ou définit la qualité de l'image du tampon en pourcentage. Valeurs valides de 0 à 100 %. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Obtient ou définit la rotation du tampon en degrés. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Obtient ou définit l'identifiant du tampon. |

## Méthodes

| Nom | Description |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Définit l'image qui sera utilisée comme tampon. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Définit l'image comme un tampon. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Définit le texte comme tampon. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Définit le fichier PDF et le numéro de page qui seront utilisés comme tampon. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Définit l'état du texte du tampon. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Définit la taille de l'image du tampon. L'image sera mise à l'échelle selon les valeurs spécifiées. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Définit la position sur la page où le tampon sera placé. |

### Voir aussi

* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)