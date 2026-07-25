---
title: "HtmlSaveOptions.RasterImagesSavingModes"
linktitle: "HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le PDF converti peut contenir des images raster (.png, *.jpeg, etc.). Cette énumération définit les méthodes de gestion des images raster lors de la conversion de PDF en HTML."
type: docs
weight: 2140
url: /fr/java/com.aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.RasterImagesSavingModes

```
public static final class HtmlSaveOptions.RasterImagesSavingModes extends com.aspose.ms.System.Enum
```

Le PDF converti peut contenir des images raster (.png, *.jpeg, etc.). Cette énumération définit les méthodes de gestion des images raster lors de la conversion de PDF en HTML.

## Champs

| Champ | Description |
| --- | --- |
| [AsEmbeddedPartsOfPngPageBackground](#AsEmbeddedPartsOfPngPageBackground) | Un seul fichier PNG d'arrière-plan volumineux sera généré pour chaque page de résultat. Les images raster seront intégrées dans ce fichier et rendues comme des régions de cette image. Aucun fichier PNG externe ne sera généré pour chaque image, un seul fichier PNG par page sera présent dans l'ensemble des fichiers de résultat de conversion. |
| [AsExternalPngFilesReferencedViaSvg](#AsExternalPngFilesReferencedViaSvg) | Les images raster distinctes seront séparées en fichiers PNG mais seront référencées via des images SVG enveloppantes, c’est‑à‑dire qu’un fichier PNG et un fichier SVG seront générés pour chaque image raster, et chacun de ces SVG contiendra des liens vers le fichier PNG correspondant. |
| [AsPngImagesEmbeddedIntoSvg](#AsPngImagesEmbeddedIntoSvg) | Pour chaque fichier raster distinct, une image SVG d’enveloppe sera générée, et l’image raster sera intégrée sous forme de chaînes encodées en Base64 dans cette image SVG. |
| [DontSave](#DontSave) | Ne pas enregistrer les images pour la mise en page fixe |

### AsEmbeddedPartsOfPngPageBackground {#AsEmbeddedPartsOfPngPageBackground}
```
public static final int AsEmbeddedPartsOfPngPageBackground
```

Un seul fichier PNG d'arrière-plan volumineux sera généré pour chaque page de résultat. Les images raster seront intégrées dans ce fichier et rendues comme des régions de cette image. Aucun fichier PNG externe ne sera généré pour chaque image, un seul fichier PNG par page sera présent dans l'ensemble des fichiers de résultat de conversion.

### AsExternalPngFilesReferencedViaSvg {#AsExternalPngFilesReferencedViaSvg}
```
public static final int AsExternalPngFilesReferencedViaSvg
```

Les images raster distinctes seront séparées en fichiers PNG mais seront référencées via des images SVG enveloppantes, c’est‑à‑dire qu’un fichier PNG et un fichier SVG seront générés pour chaque image raster, et chacun de ces SVG contiendra des liens vers le fichier PNG correspondant.

### AsPngImagesEmbeddedIntoSvg {#AsPngImagesEmbeddedIntoSvg}
```
public static final int AsPngImagesEmbeddedIntoSvg
```

Pour chaque fichier raster distinct, une image SVG d’enveloppe sera générée, et l’image raster sera intégrée sous forme de chaînes encodées en Base64 dans cette image SVG.

### DontSave {#DontSave}
```
public static final int DontSave
```

Ne pas enregistrer les images pour la mise en page fixe
