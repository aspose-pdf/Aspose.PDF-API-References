---
title: Class AssistantListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.AssistantListQueryParameters. Représente l'objet des paramètres de requête pour lister les assistants
type: docs
weight: 110
url: /fr/net/aspose.pdf.ai/assistantlistqueryparameters/
---
## Classe AssistantListQueryParameters

Représente l'objet des paramètres de requête pour lister les assistants.

```csharp
public class AssistantListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AssistantListQueryParameters](assistantlistqueryparameters/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtient ou définit un curseur à utiliser dans la pagination. after est un ID d'objet qui définit votre position dans la liste. Par exemple, si vous faites une demande de liste et recevez 100 objets, se terminant par obj_foo, votre appel suivant peut inclure after=obj_foo afin de récupérer la page suivante de la liste. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtient ou définit un curseur à utiliser dans la pagination. before est un ID d'objet qui définit votre position dans la liste. Par exemple, si vous faites une demande de liste et recevez 100 objets, se terminant par obj_foo, votre appel suivant peut inclure before=obj_foo afin de récupérer la page précédente de la liste. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtient ou définit une limite sur le nombre d'objets à retourner. Limit peut varier entre 1 et 100, et la valeur par défaut est 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtient ou définit l'ordre de tri par le timestamp created_at des objets. asc pour l'ordre croissant et desc pour l'ordre décroissant. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/assistantlistqueryparameters/getqueryparameters/)() | Obtient les paramètres de requête pour lister les assistants. |

### Voir aussi

* classe [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)