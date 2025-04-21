---
title: ImageCompressionOptions.Version
second_title: Aspose.PDF for .NET API Reference
description: Propriété ImageCompressionOptions. Version de l'algorithme de compression. Les valeurs possibles sont 1. compression standard 2. compression rapide améliorée qui est plus rapide que la standard mais peut ne pas être applicable à toutes les images 3. compression standard mixte est appliquée aux images qui ne peuvent pas être compressées par un algorithme plus rapide, cela peut donner la meilleure compression mais plus lent que l'algorithme "rapide". La version "Rapide" n'est pas applicable pour le redimensionnement des images . Par défaut, c'est "Standard".
type: docs
weight: 70
url: /fr/net/aspose.pdf.optimization/imagecompressionoptions/version/
---
## Propriété ImageCompressionOptions.Version

Version de l'algorithme de compression. Les valeurs possibles sont : 1. compression standard, 2. rapide (compression améliorée qui est plus rapide que la standard mais peut ne pas être applicable à toutes les images), 3. mixte (la compression standard est appliquée aux images qui ne peuvent pas être compressées par un algorithme plus rapide, cela peut donner la meilleure compression mais plus lent que l'algorithme "rapide". La version "Rapide" n'est pas applicable pour le redimensionnement des images (la méthode standard sera utilisée). Par défaut, c'est "Standard".

```csharp
public ImageCompressionVersion Version { get; set; }
```

### Voir aussi

* enum [ImageCompressionVersion](../../imagecompressionversion/)
* class [ImageCompressionOptions](../)
* namespace [Aspose.Pdf.Optimization](../../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../../)