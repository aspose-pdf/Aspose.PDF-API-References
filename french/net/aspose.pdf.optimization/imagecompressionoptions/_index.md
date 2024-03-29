---
title: ImageCompressionOptions
second_title: Référence de l'API Aspose.PDF pour .NET
description: La classe contient des options définies pour la compression dimage.
type: docs
weight: 5710
url: /fr/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

La classe contient des options définies pour la compression d'image.

```csharp
public class ImageCompressionOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages) { get; set; } | Si cet indicateur est défini sur vrai, les images seront compressées dans le document. le niveau de compression est spécifié avec la propriété ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding) { get; set; } | Obtient ou définit l'encodage utilisé pour stocker les images. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality) { get; set; } | Spécifie le niveau de compression d'image lorsque l'indicateur CompressIamges est utilisé. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution) { get; set; } | Spécifie la résolution maximale des images. Si l'image a une résolution plus élevée, elle sera mise à l'échelle |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages) { get; set; } | Si cet indicateur est défini sur vrai et que CompressImages est vrai, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version) { get; set; } | Version de l'algorithme de compression. Les valeurs possibles sont : 1. compression standard, 2. rapide (compression améliorée qui est plus rapide que la norme mais peut ne pas s'appliquer à toutes les images), 3. mixte (la compression standard est appliquée aux images qui ne peuvent pas être compressées par un algorithme plus rapide, ceci peut donner la meilleure compression mais un algorithme plus lent que "rapide". La version "Fast" n'est pas applicable pour le redimensionnement des images (la méthode standard sera utilisée). La valeur par défaut est "Standard". |

### Voir également

* espace de noms [Aspose.Pdf.Optimization](../../aspose.pdf.optimization)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
