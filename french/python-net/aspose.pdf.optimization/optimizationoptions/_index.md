---
title: "OptimizationOptions"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe qui décrit l'algorithme d'optimisation de document.<br/>            Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources()."
type: docs
weight: 20
url: /fr/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Classe qui décrit l'algorithme d'optimisation de document.<br/>            Une instance de cette classe peut être utilisée comme paramètre de la méthode OptimizeResources().

Le type OptimizationOptions expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| OptimizationOptions() | Initialise une nouvelle instance de la classe OptimizationOptions |
## Propriétés
| Nom | Description |
| :- | :- |
| link_duplcate_streams | Si ce drapeau est défini sur true, les flux de ressources seront analysés. Si des flux en double sont trouvés (c'est‑à‑dire si le contenu du flux est identique), alors ces flux seront stockés comme un seul objet. <br/>            Cela permet de réduire la taille du document dans certains cas (par exemple, lorsque le même document a été concaténé plusieurs fois). |
| allow_reuse_page_content | Si true, le contenu des pages sera réutilisé lorsque le document est optimisé pour des pages identiques. |
| remove_unused_streams | Si ce drapeau est défini sur true, chaque ressource est vérifiée quant à son utilisation. Si une ressource n'est jamais utilisée, elle est supprimée.<br/>            Cela peut réduire la taille du document, par exemple lorsque des pages ont été extraites du document. |
| remove_unused_objects | Si ce drapeau est défini sur true, tous les objets du document seront vérifiés et les objets inutilisés (c'est‑à‑dire les objets qui n'ont aucune référence) seront supprimés du document. |
| image_compression_options | Ensemble d'options décrivant si les images du document seront compressées et les paramètres de la compression. |
| compress_images | Si ce drapeau est défini sur true, les images seront compressées dans le document. Le niveau de compression est spécifié avec la propriété ImageQuality. |
| resize_images | Si ce drapeau est défini sur true et que CompressImages est true, les images seront redimensionnées si la résolution de l'image est supérieure au paramètre MaxResolution spécifié. |
| image_quality | Spécifie le niveau de compression d'image lorsque le drapeau CompressIamges est utilisé. |
| max_resoultion | Spécifie la résolution maximale des images. Si une image a une résolution supérieure, elle sera mise à l'échelle. |
| unembed_fonts | Ne pas incorporer les polices si défini sur true. |
| subset_fonts | Les polices seront converties en sous-ensembles si définies sur true. |
| remove_private_info | Supprimer les informations privées (informations de page). |
| image_encoding | Encodage d'image qui sera utilisé. |
## Méthodes
| Nom | Description |
| :- | :- |
| all() | Crée une stratégie d'optimisation avec toutes les options activées.<br/>            Veuillez noter que seules les options qui ne modifient aucune fonctionnalité du document sont activées.<br/>            Par exemple, la compression d'image et le désincorporation des polices ne seront pas activés (et peuvent être incorporés manuellement). |

### Voir aussi

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

