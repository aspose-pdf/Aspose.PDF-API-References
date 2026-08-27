---
title: "Classe Collection"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Collection. Représente la classe pour Collection12.3.5 Collections"
type: docs
weight: 3130
url: /fr/net/aspose.pdf/collection/
---
## Collection class

Représente la classe pour Collection(12.3.5 Collections).

```csharp
public class Collection : EmbeddedFileCollection
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Collection](collection/)() | Initialise un nouvel objet Collection. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Obtient le nombre de fichiers incorporés dans la collection. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Nom de fichier incorporé par défaut. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Obtient une valeur indiquant si l'accès à cette collection est synchronisé (thread‑safe). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Obtient le fichier incorporé par son index. (2 indexeurs) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Renvoie la liste des clés de pièces jointes de fichiers. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Obtient un "Schéma" d'une collection de documents. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Obtient un objet pouvant être utilisé pour synchroniser l'accès à cette collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Ajoute la spécification du fichier incorporé dans la collection. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Ajoute le fichier aux fichiers incorporés avec la clé spécifiée. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Copie le tableau d'objets FileSpecification dans la colleciton. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Supprime tous les fichiers incorporés du document. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Supprime le fichier incorporé par son nom. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Supprime le fichier de la collection par sa clé dans la collection. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Renvoie le fichier incorporé par son nom. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Renvoie l'énumérateur de colleciton. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Obtient une collection de fichiers triés selon la spécification. |

### Voir aussi

* class [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


