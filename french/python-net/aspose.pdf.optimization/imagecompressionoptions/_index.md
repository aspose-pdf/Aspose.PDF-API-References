---
title: "ImageCompressionOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "La classe contient un ensemble d'options pour la compression d'image."
type: docs
weight: 10
url: /fr/python-net/aspose.pdf.optimization/imagecompressionoptions/
---

## ImageCompressionOptions class

La classe contient un ensemble d'options pour la compression d'image.

Le type ImageCompressionOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| ImageCompressionOptions() | Initialise une nouvelle instance de la classe ImageCompressionOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| compress_images | Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality. |
| resize_images | Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié. |
| image_quality | Spécifie le niveau de compression d'image lorsque le drapeau CompressIamges est utilisé. |
| max_resolution | Spécifie la résolution maximale des images. Si une image a une résolution supérieure, elle sera mise à l'échelle. |
| version | Version de l'algorithme de compression. Les valeurs possibles sont : 1. compression standard, 2. rapide (compression améliorée qui est plus rapide que la standard mais peut ne pas être applicable à toutes les images), 3. mixte (la compression standard est appliquée aux images qui ne peuvent pas être compressées par un algorithme plus rapide, cela peut donner la meilleure compression mais plus lente que l'algorithme \"fast\". La version \"Fast\" n'est pas applicable au redimensionnement des images (la méthode standard sera utilisée). La valeur par défaut est \"Standard\"). |
| encodage | Obtient ou définit l'encodage utilisé pour stocker les images. |

### Voir aussi

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

