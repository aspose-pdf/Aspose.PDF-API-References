---
title: "Classe XImage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.XImage. Classe représentant l'objet XObject d'image"
type: docs
weight: 11540
url: /fr/net/aspose.pdf/ximage/
---
## XImage class

Classe représentant un X-Object image.

```csharp
public sealed class XImage
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Si l'image contient de la transparence, renvoie true ; sinon, false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Obtient le type de filtre de l'image. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Obtient la version en niveaux de gris de l'image. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Obtient la hauteur de l'image. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Obtient un indicateur indiquant si l'image doit être traitée comme un masque d'image (voir 8.9.6, "Masked Images"). Si cet indicateur est true, la valeur de BitsPerComponent doit être 1 et Mask et ColorSpace ne doivent pas être spécifiés ; les zones non masquées doivent être peintes en utilisant la couleur de tracé actuelle. Valeur par défaut : false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Métadonnées de l'image. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Obtient ou définit le nom de l'image. Veuillez noter que si vous modifiez le nom de l'image qui possède des références dans le contenu des pages, le document peut devenir incorrect. Veuillez utiliser la méthode XImage.Rename dans ce cas. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Obtient la largeur de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Ajoute un masque pochoir à la XImage. |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | Renvoie une liste de chaînes contenant le texte alternatif pour une XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Renvoie le type de couleur de l'image. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Renvoie le nom de l'image dans sa collection. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Récupère les données brutes de l'image à partir de l'image source. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Renvoie true si les deux images font référence au même objet. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Renomme l'image et remplace toutes les références à l'image par le nouveau nom |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Enregistre les données de l'image dans le flux sous forme d'image JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Enregistre l'image dans le flux avec le format demandé. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Enregistre les données de l'image dans le flux sous forme d'image JPEG avec la résolution spécifiée. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Enregistre l'image dans le flux avec le format demandé et la résolution spécifiée. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Renvoie le flux d'image original. |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | Définit le texte alternatif pour un XImage sur la page. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


