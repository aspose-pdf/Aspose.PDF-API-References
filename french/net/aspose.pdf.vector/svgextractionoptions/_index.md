---
title: "Classe SvgExtractionOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Vector.SvgExtractionOptions. Représente une classe d'options pour extraire les graphiques vectoriels de la page du document PDF."
type: docs
weight: 11430
url: /fr/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

Représente une classe d'options pour extraire les graphiques vectoriels de la page du document PDF.

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
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Obtient et définit l'option de regrouper automatiquement les subpaths en images. Cette option exclut l'option [`GroupStrength`](./groupstrength/). |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Obtient et définit l'option d'extraire chaque subpath d'un document PDF en images SVG séparées. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Obtient et définit le rectangle englobant qui détermine la zone d'extraction pour l'extraction SVG. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Obtient et définit une option : la force du regroupement des subpaths en images. Permet de configurer le degré de regroupement des subpaths. La valeur varie de 0 à 1. Une valeur de 0 correspond à l'activation de l'option [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/). Une valeur de 1 créera une image unique pour tous les chemins vectoriels de la page. L'option a un effet lorsque [`AutoGrouping`](./autogrouping/) est false. La valeur par défaut est `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Obtient ou définit la largeur de trait minimale qui sera utilisée dans le SVG résultant. Si le PDF utilise une largeur de trait plus fine, elle sera remplacée par cette largeur. La valeur par défaut est 0,5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Obtient et définit une option pour vérifier strictement si les subpaths se trouvent à l'intérieur du rectangle spécifié dans [`ExtractionAreaBound`](./extractionareabound/). Si elle est définie sur false, les subpaths qui ne sont pas entièrement inclus dans [`ExtractionAreaBound`](./extractionareabound/) seront extraits. La valeur par défaut est `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Obtient et définit un indicateur qui détermine si les XFrom trouvés sur les pages doivent être décompressés ou non. Les éléments XFrom peuvent se retrouver dans différents fichiers SVG. Seuls les XForms rendus par les instructions Do du contenu de la page sont décompressés. Les XForms imbriqués ne le sont pas. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Obtient et définit l'option de décompresser uniquement le XForm correspondant au prédicat spécifié. |

### Voir aussi

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


