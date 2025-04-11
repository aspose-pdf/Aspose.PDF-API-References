---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.DataEditor.DictionaryEditor. Une classe pour accéder à un dictionnaire d'arbre de documents, dictionnaire de documents, dictionnaire de pages, dictionnaire de ressources.
type: docs
weight: 3470
url: /fr/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## Classe DictionaryEditor

Une classe pour accéder au dictionnaire d'arbre d'un document (dictionnaire de document, dictionnaire de page, dictionnaire de ressources).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | Collection complète de clés. Contient des clés modifiables et non modifiables. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | Obtient le nombre d'éléments contenus dans le `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | Obtient une valeur indiquant si le `DictionaryEditor` est en lecture seule. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | Obtient ou définit l'élément avec la clé spécifiée. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | Collection de clés modifiables. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | Obtient un ICollection contenant les valeurs dans le `DictionaryEditor`. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Définit [`ICosPdfPrimitive`](../icospdfprimitive/) dans le dictionnaire. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | Définit [`ICosPdfPrimitive`](../icospdfprimitive/) dans le dictionnaire. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | Supprime tous les éléments du `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Détermine si le `DictionaryEditor` contient une valeur spécifique. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | Détermine si le `DictionaryEditor` contient un élément avec la clé spécifiée. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | Renvoie un énumérateur qui itère à travers la collection. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Supprime la première occurrence d'un objet spécifique du `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | Supprime l'élément avec la clé spécifiée du `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | Pour accéder à des types de données simples comme string, name, bool, number. Renvoie null pour d'autres types. |

### Voir aussi

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)