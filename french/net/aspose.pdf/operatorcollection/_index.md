---
title: "Classe OperatorCollection"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.OperatorCollection. La classe représente une collection d’opérateurs."
type: docs
weight: 7220
url: /fr/net/aspose.pdf/operatorcollection/
---
## OperatorCollection class

La classe représente une collection d'opérateurs

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Obtient le nombre d’opérateurs dans la collection. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Indique si la collection est limitée à une extraction rapide de texte. |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Obtient l’opérateur par son indice. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Accepte l’objet visiteur IOperatorSelector pour traiter les opérateurs. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Ajoute à la collection tous les opérateurs d’une autre collection. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Ajoute un nouvel opérateur dans la collection. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Ajoute des opérateurs à la fin des opérateurs de contenu. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Annule la dernière mise à jour. Cette méthode peut être appelée lorsque la modification ne doit pas déclencher de mise à jour du contenu. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Supprime tous les opérateurs de la liste. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Renvoie true si la collection contient l’opérateur donné. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Copie les opérateurs dans la liste des opérateurs. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Supprime les opérateurs de la collection. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Supprime l’opérateur de la collection. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Supprime les opérateurs de la collection. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Effectue les tâches définies par l’application associées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Renvoie un énumérateur pour la collection |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Insérer les opérateurs à la position donnée. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Insère un opérateur dans la collection. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Insérer les opérateurs à la position donnée. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Supprime l'opérateur de la collection. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Remplace les opérateurs de la collection par d'autres opérateurs. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Reprend la mise à jour du document. Met à jour le flux de contenu au cas où il y aurait des modifications en attente. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Reprend la mise à jour du document. Met à jour le flux de contenu au cas où il y aurait des modifications en attente. Marque tous les opérateurs comme "changed" si le paramètre invalidate est vrai. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Supprime la mise à jour des données de contenu. Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Renvoie la représentation textuelle de l'opérateur. |

### Voir aussi

* class [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


