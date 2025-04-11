---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes. Le PDF converti peut contenir des images raster .png .jpeg etc. Cet enum définit les méthodes de gestion des images raster lors de la conversion de PDF en HTML
type: docs
weight: 5720
url: /fr/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## Énumération HtmlSaveOptions.RasterImagesSavingModes

Le PDF converti peut contenir des images raster (.png, *.jpeg etc.) Cet enum définit les méthodes de gestion des images raster lors de la conversion de PDF en HTML

```csharp
public enum RasterImagesSavingModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | pour chaque fichier raster distinct, une image SVG enveloppante sera générée, et l'image raster sera intégrée sous forme de chaînes encodées en Base64 dans cette image SVG |
| AsExternalPngFilesReferencedViaSvg | `1` | les images raster distinctes seront mises à part en tant que fichiers PNG mais seront référencées via des images SVG enveloppantes, c'est-à-dire qu'un fichier PNG et un SVG seront générés pour chaque image raster, et chacun de ces SVG contiendra des liens vers le fichier PNG correspondant |
| AsEmbeddedPartsOfPngPageBackground | `2` | Un grand fichier d'arrière-plan PNG sera généré pour chaque page de résultat. Les images raster seront intégrées dans ce fichier et rendues comme des régions de cette image. Aucun fichier PNG externe pour chaque image ne sera généré, seulement un fichier PNG par page sera présent dans l'ensemble des fichiers de résultats de conversion. |
| DontSave | `3` | Ne pas enregistrer les images pour la mise en page fixe |

### Voir aussi

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)