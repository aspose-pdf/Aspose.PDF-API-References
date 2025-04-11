---
title: Class ThreadMessageListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.ThreadMessageListQueryParameters. Objet de paramètres de requête pour lister les messages de fil
type: docs
weight: 1130
url: /fr/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## Classe ThreadMessageListQueryParameters

Objet de paramètres de requête pour lister les messages de fil.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtient ou définit un curseur à utiliser dans la pagination. after est un ID d'objet qui définit votre position dans la liste. Par exemple, si vous faites une demande de liste et recevez 100 objets, se terminant par obj_foo, votre appel suivant peut inclure after=obj_foo afin de récupérer la page suivante de la liste. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtient ou définit un curseur à utiliser dans la pagination. before est un ID d'objet qui définit votre position dans la liste. Par exemple, si vous faites une demande de liste et recevez 100 objets, se terminant par obj_foo, votre appel suivant peut inclure before=obj_foo afin de récupérer la page précédente de la liste. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtient ou définit une limite sur le nombre d'objets à retourner. Limit peut varier entre 1 et 100, et la valeur par défaut est 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtient ou définit l'ordre de tri par le timestamp created_at des objets. asc pour l'ordre croissant et desc pour l'ordre décroissant. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Filtrer les messages par l'ID d'exécution qui les a générés. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Obtient les paramètres de requête pour lister les messages de fil. |

### Voir aussi

* classe [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)