---
title: "Classe OptimizationOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Optimization.OptimizationOptions classe. Classe qui décrit l'algorithme d'optimisation du document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources."
type: docs
weight: 8120
url: /fr/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

Classe qui décrit l'algorithme d'optimisation du document. Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources().

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
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Si vrai, le contenu des pages sera réutilisé lorsque le document est optimisé pour des pages identiques. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Si ce drapeau est réglé sur `true`, les objets Pdf seront empaquetés dans des Objest Streams et compressés pour réduire la taille du fichier pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Ensemble d'options décrivant comment les images du document seront compressées et les paramètres de la compression. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Encodage d'image qui sera utilisé. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Si ce drapeau est réglé sur true, les flux de ressources seront analysés. Si des flux en double sont trouvés (c.-à-d. si le contenu du flux est identique), alors ces flux seront stockés comme un seul objet. Cela permet de diminuer la taille du document dans certains cas (par exemple, lorsque le même document a été concaténé plusieurs fois). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Spécifie la résolution maximale des images. Si une image a une résolution supérieure, elle sera redimensionnée. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Supprimer les informations privées (info de morceau de page). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Si ce drapeau est réglé sur true, tous les objets du document seront vérifiés et les objets inutilisés (c.-à-d. les objets qui n'ont aucune référence) seront supprimés du document. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Si ce drapeau est réglé sur true, chaque ressource est vérifiée quant à son utilisation. Si une ressource n'est jamais utilisée, alors la ressource est supprimée. Cela peut réduire la taille du document, par exemple lorsque des pages ont été extraites du document. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Les polices seront converties en sous-ensembles si réglées sur true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Ne pas incorporer les polices si réglé sur true. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Crée une stratégie d'optimisation avec toutes les options activées. Veuillez noter que seules les options qui ne modifient aucune fonctionnalité du document sont activées. Par exemple, la compression d'image et le désincorporation des polices ne seront pas activées (et peuvent être incorporées manuellement). |

### Voir aussi

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


