---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.BaseOperatorCollection. Représente la classe de base pour la collection d'opérateurs
type: docs
weight: 2830
url: /fr/net/aspose.pdf/baseoperatorcollection/
---
## Classe BaseOperatorCollection

Représente la classe de base pour la collection d'opérateurs.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Propriétés

| Nom | Description |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Obtient le nombre d'opérateurs dans la collection. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indique si la collection est limitée à l'extraction de texte rapide. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Renvoie vrai si la collection est en lecture seule. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Obtient l'opérateur par son index. |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Ajoute un nouvel opérateur à la collection. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Annule la dernière mise à jour. Cette méthode peut être appelée lorsque le changement ne doit pas déclencher de mise à jour du contenu. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Efface la collection. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Vérifie si l'opérateur existe dans la collection. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Copie les opérateurs dans la liste des opérateurs. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Renvoie un énumérateur pour la collection. |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Insère un opérateur dans la collection. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Supprime un opérateur de la collection. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Reprend la mise à jour du document. Met à jour le flux de contenu en cas de changements en attente. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Supprime les données de mise à jour du contenu. Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |

### Voir aussi

* classe [Operator](../operator/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)