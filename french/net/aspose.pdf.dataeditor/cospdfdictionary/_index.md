---
title: "Classe CosPdfDictionary"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.DataEditor.CosPdfDictionary. Une classe pour accéder au dictionnaire d'un objet."
type: docs
weight: 3540
url: /fr/net/aspose.pdf.dataeditor/cospdfdictionary/
---
## CosPdfDictionary class

Une classe pour accéder au dictionnaire d'un objet.

```csharp
public class CosPdfDictionary : CosPdfPrimitive, IDictionary<string, ICosPdfPrimitive>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CosPdfDictionary](cospdfdictionary/)(Resources) | Crée un dictionnaire à partir des ressources. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/cospdfdictionary/allkeys/) { get; } | Collection complète de clés. Contient des clés modifiables et non modifiables. |
| [Count](../../aspose.pdf.dataeditor/cospdfdictionary/count/) { get; } | Obtient le nombre d'éléments contenus dans le `CosPdfDictionary`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/cospdfdictionary/isreadonly/) { get; } | Obtient une valeur indiquant si le `CosPdfDictionary` est en lecture seule. |
| [Item](../../aspose.pdf.dataeditor/cospdfdictionary/item/) { get; set; } | Obtient ou définit l'élément avec la clé spécifiée. |
| [Keys](../../aspose.pdf.dataeditor/cospdfdictionary/keys/) { get; } | Collection de clés modifiables. |
| [Values](../../aspose.pdf.dataeditor/cospdfdictionary/values/) { get; } | Obtient une ICollection contenant les valeurs du `CosPdfDictionary`. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary)(Document) | Crée un dictionnaire vide qui sera attaché au document. |
| static [CreateEmptyDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/createemptydictionary/#createemptydictionary_1)(Page) | Crée un dictionnaire vide qui sera attaché à la page. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Définir [`ICosPdfPrimitive`](../icospdfprimitive/) sur le dictionnaire. |
| [Add](../../aspose.pdf.dataeditor/cospdfdictionary/add/#add_1)(string, ICosPdfPrimitive) | Définir [`ICosPdfPrimitive`](../icospdfprimitive/) sur le dictionnaire. |
| [Clear](../../aspose.pdf.dataeditor/cospdfdictionary/clear/)() | Supprime tous les éléments du `CosPdfDictionary`. |
| [Contains](../../aspose.pdf.dataeditor/cospdfdictionary/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Détermine si le `CosPdfDictionary` contient une valeur spécifique. |
| [ContainsKey](../../aspose.pdf.dataeditor/cospdfdictionary/containskey/)(string) | Détermine si le `CosPdfDictionary` contient un élément avec la clé spécifiée. |
| [CopyTo](../../aspose.pdf.dataeditor/cospdfdictionary/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/cospdfdictionary/getenumerator/)() | Renvoie un énumérateur qui parcourt la collection. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | Supprime la première occurrence d'un objet spécifique du `CosPdfDictionary`. |
| [Remove](../../aspose.pdf.dataeditor/cospdfdictionary/remove/#remove_1)(string) | Supprime l'élément avec la clé spécifiée du `CosPdfDictionary`. |
| virtual [ToCosPdfBoolean](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfboolean/)() | Tente de convertir cette instance en [`CosPdfBoolean`](../cospdfboolean/). |
| override [ToCosPdfDictionary](../../aspose.pdf.dataeditor/cospdfdictionary/tocospdfdictionary/)() | Tente de convertir cette instance en `CosPdfDictionary`. |
| virtual [ToCosPdfName](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfname/)() | Tente de convertir cette instance en [`CosPdfName`](../cospdfname/). |
| virtual [ToCosPdfNumber](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfnumber/)() | Tente de convertir cette instance en [`CosPdfNumber`](../cospdfnumber/). |
| virtual [ToCosPdfString](../../aspose.pdf.dataeditor/cospdfprimitive/tocospdfstring/)() | Tente de convertir cette instance en [`CosPdfString`](../cospdfstring/). |
| [TryGetValue](../../aspose.pdf.dataeditor/cospdfdictionary/trygetvalue/)(string, out ICosPdfPrimitive) | Pour accéder à des types de données simples comme string, name, bool, number. Renvoie null pour les autres types. |

### Voir aussi

* class [CosPdfPrimitive](../cospdfprimitive/)
* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


