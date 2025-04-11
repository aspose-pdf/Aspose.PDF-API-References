---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Collection. Représente la classe pour Collection12.3.5 Collections
type: docs
weight: 3020
url: /fr/net/aspose.pdf/collection/
---
## Classe Collection

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
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Obtient le nombre de fichiers intégrés dans la collection. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Nom de fichier intégré par défaut. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Obtient une valeur indiquant si l'accès à cette collection est synchronisé (sécurisé pour les threads). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Obtient le fichier intégré par son index. (2 indexeurs) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Renvoie la liste des clés de fichiers joints. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Obtient un "Schéma" d'une collection de documents. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès à cette collection. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Ajoute une spécification de fichier intégré dans la collection. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Ajoute un fichier aux fichiers intégrés avec la clé spécifiée. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Copie un tableau d'objets FileSpecification dans la collection. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Supprime tous les fichiers intégrés du document. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Supprime un fichier intégré par son nom. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Supprime un fichier de la collection par sa clé dans la collection. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Renvoie le fichier intégré par son nom. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Renvoie l'énumérateur de la collection. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Obtient une collection de fichiers triés selon la spécification. |

### Voir aussi

* classe [EmbeddedFileCollection](../embeddedfilecollection/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)