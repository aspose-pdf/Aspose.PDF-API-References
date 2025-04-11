---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Vector.SvgExtractionOptions. Représente une classe d'options pour extraire des graphiques vectoriels de la page du document PDF
type: docs
weight: 11240
url: /fr/net/aspose.pdf.vector/svgextractionoptions/
---
## Classe SvgExtractionOptions

Représente une classe d'options pour extraire des graphiques vectoriels de la page du document PDF.

```csharp
public class SvgExtractionOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Obtient et définit l'option de regrouper automatiquement les sous-chemins en images. Cette option exclut l'option [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Obtient et définit l'option d'extraire chaque sous-chemin d'un document PDF en images SVG séparées. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Obtient et définit le rectangle englobant qui définit la zone d'extraction pour l'extraction SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Obtient et définit une option pour la force de regroupement des sous-chemins en images. Permet de configurer le degré de regroupement des sous-chemins. La plage de valeurs est de 0 à 1. Une valeur de 0 correspond à l'option [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) étant activée. Une valeur de 1 créera une image unique pour tous les chemins vectoriels sur la page. L'option a un effet lorsque [`AutoGrouping`](./autogrouping/) est faux. La valeur par défaut est `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Obtient ou définit la largeur de trait minimale qui sera utilisée dans le SVG résultant. Si le PDF utilise une largeur de trait plus fine, elle sera remplacée par cette largeur. La valeur par défaut est 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Obtient et définit une option pour vérifier strictement si les sous-chemins sont dans le rectangle spécifié dans [`ExtractionAreaBound`](./extractionareabound/). Si défini sur faux, alors les sous-chemins qui ne sont pas complètement inclus dans [`ExtractionAreaBound`](./extractionareabound/) seront extraits. La valeur par défaut est `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Obtient et définit un indicateur qui détermine si les XForms trouvés sur les pages doivent être décompressés ou non. Les éléments XForm peuvent se retrouver dans différents fichiers SVG. Seuls les XForms qui sont rendus par des instructions Do à partir du contenu de la page sont décompressés. Les XForms imbriqués ne sont pas décompressés. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Obtient et définit l'option de décompresser uniquement le XForm correspondant au prédicat spécifié. |

### Voir aussi

* espace de noms [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)