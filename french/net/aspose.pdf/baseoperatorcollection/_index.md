---
title: "Classe BaseOperatorCollection"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.BaseOperatorCollection. Représente la classe de base pour la collection d'opérateurs."
type: docs
weight: 2940
url: /fr/net/aspose.pdf/baseoperatorcollection/
---
## BaseOperatorCollection class

Représente la classe de base pour la collection d'opérateurs.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Propriétés

| Nom | Description |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Obtient le nombre d’opérateurs dans la collection. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indique si la collection est limitée à une extraction rapide de texte. |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Renvoie true si la collection est en lecture seule. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Obtient l’opérateur par son indice. |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Ajoute un nouvel opérateur dans la collection. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Annule la dernière mise à jour. Cette méthode peut être appelée lorsque la modification ne doit pas déclencher de mise à jour du contenu. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Efface la collection. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Vérifie si l'opérateur existe dans la collection. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Copie les opérateurs dans la liste des opérateurs. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Renvoie un énumérateur pour la collection |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Insère un opérateur dans la collection. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Supprime l'opérateur de la collection. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Reprend la mise à jour du document. Met à jour le flux de contenu au cas où il y aurait des modifications en attente. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Supprime la mise à jour des données de contenu. Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |

### Voir aussi

* class [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


