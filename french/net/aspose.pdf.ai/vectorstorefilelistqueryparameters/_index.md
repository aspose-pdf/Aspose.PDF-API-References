---
title: "Classe VectorStoreFileListQueryParameters"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.VectorStoreFileListQueryParameters classe. Objet de paramètres de requête pour l’énumération des fichiers du magasin de vecteurs."
type: docs
weight: 1420
url: /fr/net/aspose.pdf.ai/vectorstorefilelistqueryparameters/
---
## VectorStoreFileListQueryParameters class

Objet des paramètres de requête pour lister les fichiers du magasin vectoriel.

```csharp
public class VectorStoreFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [VectorStoreFileListQueryParameters](vectorstorefilelistqueryparameters/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Obtient ou définit un curseur à utiliser pour la pagination. after est un ID d'objet qui définit votre position dans la liste. Par exemple, si vous effectuez une requête de liste et recevez 100 objets, se terminant par obj_foo, votre appel suivant peut inclure after=obj_foo afin de récupérer la page suivante de la liste. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Obtient ou définit un curseur à utiliser pour la pagination. before est un ID d'objet qui définit votre position dans la liste. Par exemple, si vous effectuez une requête de liste et recevez 100 objets, se terminant par obj_foo, votre appel suivant peut inclure before=obj_foo afin de récupérer la page précédente de la liste. |
| [Filter](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/filter/) { get; set; } | Obtient ou définit un filtre par statut de fichier. L’une des valeurs : in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Obtient ou définit une limite sur le nombre d'objets à retourner. La limite peut varier entre 1 et 100, et la valeur par défaut est 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Obtient ou définit l'ordre de tri par le horodatage created_at des objets. asc pour l'ordre croissant et desc pour l'ordre décroissant. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilelistqueryparameters/getqueryparameters/)() | Obtient les paramètres de requête pour l’énumération des fichiers du magasin de vecteurs. |

### Voir aussi

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


