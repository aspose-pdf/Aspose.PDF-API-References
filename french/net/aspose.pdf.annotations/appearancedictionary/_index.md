---
title: Class AppearanceDictionary
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.AppearanceDictionary. Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page
type: docs
weight: 1490
url: /fr/net/aspose.pdf.annotations/appearancedictionary/
---
## Classe AppearanceDictionary

Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page.

```csharp
public sealed class AppearanceDictionary : IDictionary<string, XForm>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf.annotations/appearancedictionary/count/) { get; } | Obtient le nombre d'éléments contenus dans le dictionnaire. |
| [IsFixedSize](../../aspose.pdf.annotations/appearancedictionary/isfixedsize/) { get; } | Obtient une valeur indiquant si le dictionnaire a une taille fixe. |
| [IsReadOnly](../../aspose.pdf.annotations/appearancedictionary/isreadonly/) { get; } | Obtient une valeur indiquant si le dictionnaire est en lecture seule. |
| [IsSynchronized](../../aspose.pdf.annotations/appearancedictionary/issynchronized/) { get; } | Obtient une valeur indiquant si l'accès au dictionnaire est synchronisé (sécurisé pour les threads). |
| [Item](../../aspose.pdf.annotations/appearancedictionary/item/) { get; set; } | Représente une forme pratique pour obtenir des flux d'apparence. |
| [Keys](../../aspose.pdf.annotations/appearancedictionary/keys/) { get; } | Obtient les clés du dictionnaire. Si le dictionnaire d'apparence a des sous-dictionnaires, alors [`Keys`](./keys/) contient des valeurs d'état (N&#x7C;R&#x7C;D), où N - apparence normale, R - apparence au survol, D - apparence enfoncée et état - le nom de l'état (par exemple, On, Off pour les cases à cocher). |
| [SyncRoot](../../aspose.pdf.annotations/appearancedictionary/syncroot/) { get; } | Obtient un objet qui peut être utilisé pour synchroniser l'accès au dictionnaire. |
| [Values](../../aspose.pdf.annotations/appearancedictionary/values/) { get; } | Obtient la liste des valeurs du dictionnaire. La collection résultante contient la liste des objets XForm. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add)(KeyValuePair&lt;string, XForm&gt;) | Ajoute une paire avec clé et valeur dans le dictionnaire. |
| [Add](../../aspose.pdf.annotations/appearancedictionary/add/#add_2)(string, XForm) | Ajoute un formulaire X pour la clé spécifiée. |
| [Clear](../../aspose.pdf.annotations/appearancedictionary/clear/)() | Supprime tous les éléments du dictionnaire. |
| [Contains](../../aspose.pdf.annotations/appearancedictionary/contains/)(KeyValuePair&lt;string, XForm&gt;) | Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire. |
| [ContainsKey](../../aspose.pdf.annotations/appearancedictionary/containskey/)(string) | Détermine si ce dictionnaire contient la clé spécifiée. |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto_1)(KeyValuePair&lt;string, XForm&gt;[], int) |  |
| [CopyTo](../../aspose.pdf.annotations/appearancedictionary/copyto/#copyto)(XForm[], int) | Copie les éléments du dictionnaire dans un tableau, en commençant à un index de tableau particulier. |
| [GetEnumerator](../../aspose.pdf.annotations/appearancedictionary/getenumerator/)() | Renvoie un objet IDictionaryEnumerator pour le dictionnaire. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove)(KeyValuePair&lt;string, XForm&gt;) | Supprime la paire clé/valeur de la collection. |
| [Remove](../../aspose.pdf.annotations/appearancedictionary/remove/#remove_1)(string) | Supprime la clé du dictionnaire. |
| [TryGetValue](../../aspose.pdf.annotations/appearancedictionary/trygetvalue/)(string, out XForm) | Tente de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |

### Voir aussi

* classe [XForm](../../aspose.pdf/xform/)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)