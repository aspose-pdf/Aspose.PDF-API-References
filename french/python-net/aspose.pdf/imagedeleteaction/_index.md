---
title: "ImageDeleteAction"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Action effectuée avec l'objet image lorsque l'image est supprimée de la collection. Si l'objet image est supprimé"
type: docs
weight: 6450
url: /fr/python-net/aspose.pdf/imagedeleteaction/
---

## ImageDeleteAction enumeration

Action effectuée avec l'objet image lorsque l'image est supprimée de la collection. Si l'objet image est supprimé

## Members
| Nom du membre | Description |
| :- | :- |
| KEEP_CONTENTS | L'image sera supprimée de la collection. Si le contenu de la page contient des références à l'image, elles ne seront pas supprimées. Le document peut devenir invalide. |
| NONE | L'image sera supprimée de la collection et du contenu de la page, mais l'objet image ne sera pas supprimé. La taille du fichier ne sera pas réduite. |
| FORCE_DELETE | L'image sera supprimée de la collection et l'objet image sera retiré du document. Si d'autres références sur le même objet existent, le document peut être corrompu. |
| CHECK | L'image sera supprimée de la collection et l'objet image sera retiré uniquement s'il n'existe aucune autre référence à l'image depuis d'autres pages. Cela peut nécessiter plus de temps en comparaison avec l'option ForceDelete. |

### Voir aussi

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

