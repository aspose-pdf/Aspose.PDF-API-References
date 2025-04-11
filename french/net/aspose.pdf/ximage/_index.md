---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.XImage. Classe représentant un objet image X
type: docs
weight: 11350
url: /fr/net/aspose.pdf/ximage/
---
## Classe XImage

Classe représentant un objet image X.

```csharp
public sealed class XImage
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Si l'image contient de la transparence, retourne vrai ; sinon, faux. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Obtient le type de filtre de l'image. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Obtient la version en niveaux de gris de l'image. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Obtient la hauteur de l'image. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Obtient un indicateur indiquant si l'image doit être traitée comme un masque d'image (voir 8.9.6, "Images masquées"). Si cet indicateur est vrai, la valeur de BitsPerComponent doit être 1 et Mask et ColorSpace ne doivent pas être spécifiés ; les zones non masquées doivent être peintes en utilisant la couleur non traçante actuelle. Valeur par défaut : faux. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Métadonnées de l'image. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Obtient ou définit le nom de l'image. Veuillez noter que si vous changez le nom de l'image qui a des références dans le contenu de la page, le document peut devenir incorrect. Veuillez utiliser la méthode XImage.Rename dans ce cas. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Obtient la largeur de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Ajoute un masque de pochoir à l'XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Retourne le type de couleur de l'image. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Retourne le nom de l'image dans sa collection. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Récupère les données brutes de l'image à partir de l'image source. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Retourne vrai si les deux images font référence au même objet. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Renomme l'image et remplace toutes les références à l'image par le nouveau nom |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Enregistre les données de l'image dans le flux en tant qu'image JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Enregistre l'image dans le flux avec le format demandé. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Enregistre les données de l'image dans le flux en tant qu'image JPEG avec la résolution spécifiée. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Enregistre l'image dans le flux avec le format demandé avec la résolution spécifiée. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Retourne le flux d'image original. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)