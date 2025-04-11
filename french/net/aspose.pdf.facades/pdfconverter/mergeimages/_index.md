---
title: PdfConverter.MergeImages
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfConverter. Fusionne une liste de flux d'images en un seul flux d'image. Les formats de sortie Png/jpg/tiff sont pris en charge en cas d'utilisation d'un flux de sortie au format non pris en charge encodé par défaut en Jpeg
type: docs
weight: 180
url: /fr/net/aspose.pdf.facades/pdfconverter/mergeimages/
---
## Méthode PdfConverter.MergeImages

Fusionne une liste de flux d'images en un seul flux d'image. Les formats de sortie Png/jpg/tiff sont pris en charge, en cas d'utilisation d'un flux de sortie au format non pris en charge encodé par défaut en Jpeg.

```csharp
public static Stream MergeImages(List<Stream> inputImagesStreams, ImageFormat outputImageFormat, 
    ImageMergeMode mergeMode, int? horizontal, int? vertical)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputImagesStreams | List`1 | La liste des flux d'images à fusionner. |
| outputImageFormat | ImageFormat | Format de sortie de l'image pour le flux fusionné. |
| mergeMode | ImageMergeMode | Mode de fusion. Utilisé pour les formats Png/Jpg. |
| horizontal | Nullable`1 | Ratio horizontal pour définir la largeur du canevas pour le flux d'image de sortie. Utilisé uniquement pour les formats Png/Jpg avec ImageMergeMode.Center. |
| vertical | Nullable`1 | Ratio vertical pour définir la hauteur du canevas pour le flux d'image de sortie. Utilisé uniquement pour les formats Png/Jpg avec ImageMergeMode.Center. |

### Valeur de retour

Flux d'image encodé au format d'image de sortie.

### Voir aussi

* enum [ImageFormat](../../../aspose.pdf.drawing/imageformat/)
* enum [ImageMergeMode](../../imagemergemode/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)