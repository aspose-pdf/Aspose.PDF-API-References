---
title: OptimizationOptions
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe qui décrit lalgorithme doptimisation de document. Linstance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources.
type: docs
weight: 5740
url: /fr/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

Classe qui décrit l'algorithme d'optimisation de document. L'instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources().

```csharp
public class OptimizationOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [OptimizationOptions](optimizationoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent) { get; set; } | Si le vrai contenu de la page sera réutilisé lorsque le document est optimisé pour des pages égales. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions) { get; } | Ensemble d'options décrivant les images du document à compresser et les paramètres de compression. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding) { get; set; } | Encodeur d'image qui sera utilisé. |
| [LinkDuplcateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplcatestreams) { get; set; } | Si cet indicateur est défini sur vrai, les flux de ressources seront analysés. Si des flux en double sont trouvés (c'est-à-dire si le contenu du flux est égal), alors ces flux seront stockés comme un seul objet. Cela permet de réduire la taille du document dans certains cas (par exemple, lorsque le même document a été concaténé plusieurs fois). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion) { get; set; } | Spécifie la résolution maximale des images. Si l'image a une résolution plus élevée, elle sera mise à l'échelle |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo) { get; set; } | Supprimer les informations privées (informations sur les éléments de page). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects) { get; set; } | Si cet indicateur est défini sur vrai, tous les objets du document seront vérifiés et les objets inutilisés (c'est-à-dire les objets qui n'ont aucune référence) sont supprimés du document. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams) { get; set; } | Si cet indicateur est défini sur vrai, chaque ressource est vérifiée sur son utilisation. Si la ressource n'est jamais utilisée, alors les ressources sont supprimées. Cela peut réduire la taille du document, par exemple lorsque des pages ont été extraites du document. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts) { get; set; } | Les polices seront converties en sous-ensembles si elles sont définies sur true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts) { get; set; } | Rendre les polices non incorporées si défini sur true. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all)() | Crée une stratégie d'optimisation avec toutes les options activées. Veuillez noter que seules les options activées ne modifient aucune fonctionnalité du document. C'est-à-dire que la compression d'image et la désintégration des polices ne seront pas activées (et peuvent être intégrées manuellement). |

### Voir également

* espace de noms [Aspose.Pdf.Optimization](../../aspose.pdf.optimization)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
