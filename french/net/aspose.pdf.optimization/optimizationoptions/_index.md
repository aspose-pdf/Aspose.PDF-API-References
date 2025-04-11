---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Optimization.OptimizationOptions. Classe qui décrit l'algorithme d'optimisation de document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources.
type: docs
weight: 7980
url: /fr/net/aspose.pdf.optimization/optimizationoptions/
---
## Classe OptimizationOptions

Classe qui décrit l'algorithme d'optimisation de document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources().

```csharp
public class OptimizationOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Si vrai, le contenu des pages sera réutilisé lorsque le document est optimisé pour des pages égales. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Si ce drapeau est défini sur `true`, les objets Pdf seront regroupés dans des flux d'objets et compressés pour réduire la taille du fichier pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Ensemble d'options qui décrivent si les images dans le document seront compressées et les paramètres de compression. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Encodeur d'image qui sera utilisé. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Si ce drapeau est défini sur vrai, les flux de ressources seront analysés. Si des flux dupliqués sont trouvés (c'est-à-dire si le contenu du flux est égal), alors ces flux seront stockés comme un seul objet. Cela permet de réduire la taille du document dans certains cas (par exemple, lorsque le même document a été concaténé plusieurs fois). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Niveau de scan. Des scans plus profonds (valeur plus élevée) prennent plus de temps mais peuvent produire des fichiers de résultat plus petits. Valeur par défaut : 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Spécifie la résolution maximale des images. Si l'image a une résolution plus élevée, elle sera redimensionnée. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Supprimer les informations privées (informations sur les morceaux de page). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Si ce drapeau est défini sur vrai, tous les objets du document seront vérifiés et les objets inutilisés (c'est-à-dire les objets qui n'ont aucune référence) seront supprimés du document. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Si ce drapeau est défini sur vrai, chaque ressource est vérifiée pour son utilisation. Si la ressource n'est jamais utilisée, alors la ressource est supprimée. Cela peut réduire la taille du document, par exemple lorsque des pages ont été extraites du document. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Les polices seront converties en sous-ensembles si défini sur vrai. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Rendre les polices non intégrées si défini sur vrai. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Crée une stratégie d'optimisation avec toutes les options activées. Veuillez noter que seules les options activées qui ne changent aucune fonctionnalité du document. C'est-à-dire que la compression d'image et le désintégration des polices ne seront pas activés (et peuvent être intégrés manuellement). |

### Voir aussi

* espace de noms [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)