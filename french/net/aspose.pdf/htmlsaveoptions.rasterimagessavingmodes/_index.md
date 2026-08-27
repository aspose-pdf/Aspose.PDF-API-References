---
title: "Énum HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes enum. Le PDF converti peut contenir des images raster .png, .jpeg, etc. Cette énumération définit les méthodes de gestion des images raster lors de la conversion du PDF en HTML."
type: docs
weight: 5850
url: /fr/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

Le PDF converti peut contenir des images raster (.png, *.jpeg, etc.) Cette énumération définit les méthodes de gestion des images raster lors de la conversion du PDF en HTML.

```csharp
public enum RasterImagesSavingModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | Pour chaque fichier raster distinct, une image SVG d’enveloppe sera générée, et l’image raster sera intégrée sous forme de chaînes encodées en Base64 dans cette image SVG. |
| AsExternalPngFilesReferencedViaSvg | `1` | Les images raster distinctes seront séparées en fichiers PNG mais seront référencées via des images SVG d’enveloppe, c’est‑à‑dire qu’un fichier PNG et un SVG seront générés pour chaque image raster, et chaque SVG contiendra des liens vers le fichier PNG correspondant. |
| AsEmbeddedPartsOfPngPageBackground | `2` | Un grand fichier PNG d’arrière‑plan sera généré pour chaque page de résultat. Les images raster seront intégrées dans ce fichier et rendues comme des régions de cette image. Aucun fichier PNG externe ne sera généré pour chaque image, un seul fichier PNG par page sera présent dans l’ensemble de fichiers résultant de la conversion. |
| DontSave | `3` | Ne pas enregistrer les images pour la mise en page fixe. |

### Voir aussi

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


