---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Optimization.ImageCompressionOptions. La classe contient un ensemble d'options pour la compression d'images
type: docs
weight: 7950
url: /fr/net/aspose.pdf.optimization/imagecompressionoptions/
---
## Classe ImageCompressionOptions

La classe contient un ensemble d'options pour la compression d'images.

```csharp
public class ImageCompressionOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Si ce drapeau est défini sur vrai, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Obtient ou définit l'encodage utilisé pour stocker les images. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Spécifie le niveau de compression d'image lorsque le drapeau CompressImages est utilisé. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Spécifie la résolution maximale des images. Si l'image a une résolution plus élevée, elle sera redimensionnée. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Si ce drapeau est défini sur vrai et que CompressImages est vrai, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Version de l'algorithme de compression. Les valeurs possibles sont : 1. compression standard, 2. rapide (compression améliorée qui est plus rapide que la standard mais peut ne pas être applicable à toutes les images), 3. mixte (la compression standard est appliquée aux images qui ne peuvent pas être compressées par l'algorithme plus rapide, cela peut donner la meilleure compression mais plus lent que l'algorithme "rapide". La version "Rapide" n'est pas applicable pour le redimensionnement des images (la méthode standard sera utilisée). Par défaut, c'est "Standard". |

### Voir aussi

* espace de noms [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)