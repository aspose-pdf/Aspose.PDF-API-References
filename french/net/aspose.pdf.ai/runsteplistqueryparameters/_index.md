---
title: "Classe RunStepListQueryParameters"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.RunStepListQueryParameters. Objet de paramètres de requête pour l'énumération des étapes d'exécution"
type: docs
weight: 1120
url: /fr/net/aspose.pdf.ai/runsteplistqueryparameters/
---
## RunStepListQueryParameters class

Objet des paramètres de requête pour lister les étapes d'exécution.

```csharp
public class RunStepListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RunStepListQueryParameters](runsteplistqueryparameters/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtient ou définit un curseur à utiliser pour la pagination. after est un ID d'objet qui définit votre position dans la liste. Par exemple, si vous effectuez une requête de liste et recevez 100 objets, se terminant par obj_foo, votre appel suivant peut inclure after=obj_foo afin de récupérer la page suivante de la liste. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtient ou définit un curseur à utiliser pour la pagination. before est un ID d'objet qui définit votre position dans la liste. Par exemple, si vous effectuez une requête de liste et recevez 100 objets, se terminant par obj_foo, votre appel suivant peut inclure before=obj_foo afin de récupérer la page précédente de la liste. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtient ou définit une limite sur le nombre d'objets à retourner. La limite peut varier entre 1 et 100, et la valeur par défaut est 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtient ou définit l'ordre de tri par le horodatage created_at des objets. asc pour l'ordre croissant et desc pour l'ordre décroissant. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/runsteplistqueryparameters/getqueryparameters/)() | Obtient les paramètres de requête pour lister les étapes d'exécution. |

### Voir aussi

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


