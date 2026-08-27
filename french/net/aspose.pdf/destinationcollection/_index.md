---
title: "Classe DestinationCollection"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.DestinationCollection. La classe représente la collection de toutes les destinations, un arbre de noms associant des chaînes de noms aux destinations, voir 12.3.2.3 Destinations nommées et voir 7.7.4 Dictionnaire des noms dans le document pdf"
type: docs
weight: 3630
url: /fr/net/aspose.pdf/destinationcollection/
---
## DestinationCollection class

La classe représente la collection de toutes les destinations (un arbre de noms mappant des chaînes de noms aux destinations (voir 12.3.2.3, "Named Destinations") et (voir 7.7.4, "Name Dictionary")) dans le document pdf.

```csharp
public sealed class DestinationCollection : ICollection<KeyValuePair<string, object>>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf/destinationcollection/count/) { get; } | Obtient le nombre d'éléments contenus dans la collection. |
| [IsReadOnly](../../aspose.pdf/destinationcollection/isreadonly/) { get; } | Obtient une valeur indiquant si la collection est en lecture seule. |
| [Item](../../aspose.pdf/destinationcollection/item/) { get; } | Obtient l'objet destination par indice. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf/destinationcollection/add/)(KeyValuePair&lt;string, object&gt;) | Ajoute l'élément spécifié. La collection est en lecture seule. Lance toujours une exception NotSupportedException. |
| [Clear](../../aspose.pdf/destinationcollection/clear/)() | La collection est en lecture seule. Lance toujours une exception NotSupportedException. |
| [Contains](../../aspose.pdf/destinationcollection/contains/)(KeyValuePair&lt;string, object&gt;) | Détermine si cette instance contient l'objet. |
| [CopyTo](../../aspose.pdf/destinationcollection/copyto/)(KeyValuePair&lt;string, object&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/destinationcollection/getenumerator/)() | Renvoie l'énumérateur. |
| [GetExplicitDestination](../../aspose.pdf/destinationcollection/getexplicitdestination/)(string, bool) | Renvoie la destination explicite par le nom. |
| [GetPageNumber](../../aspose.pdf/destinationcollection/getpagenumber/)(string, bool) | Renvoie le numéro de page de la destination par le nom. |
| [IndexOf](../../aspose.pdf/destinationcollection/indexof/)(KeyValuePair&lt;string, object&gt;) | Renvoie l'indice de la destination dans la collection. |
| [Remove](../../aspose.pdf/destinationcollection/remove/)(KeyValuePair&lt;string, object&gt;) | Supprime l'élément spécifié. La collection est en lecture seule. Lance toujours une exception NotSupportedException. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


