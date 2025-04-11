---
title: Class Metadata
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Metadata. Fournit un accès au flux de métadonnées XMP
type: docs
weight: 6950
url: /fr/net/aspose.pdf/metadata/
---
## Classe Metadata

Fournit un accès au flux de métadonnées XMP.

```csharp
public sealed class Metadata : IDictionary<string, XmpValue>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf/metadata/count/) { get; } | Obtient le nombre d'éléments dans la collection. |
| [ExtensionFields](../../aspose.pdf/metadata/extensionfields/) { get; } | Obtient le dictionnaire des champs d'extension. |
| [IsFixedSize](../../aspose.pdf/metadata/isfixedsize/) { get; } | Vérifie si la collection a une taille fixe. |
| [IsReadOnly](../../aspose.pdf/metadata/isreadonly/) { get; } | Vérifie si la collection est en lecture seule. |
| [IsSynchronized](../../aspose.pdf/metadata/issynchronized/) { get; } | Vérifie si la collection est synchronisée. |
| [Item](../../aspose.pdf/metadata/item/) { get; set; } | Obtient ou définit des données à partir des métadonnées. |
| [Keys](../../aspose.pdf/metadata/keys/) { get; } | Obtient la collection des clés de métadonnées. |
| [NamespaceManager](../../aspose.pdf/metadata/namespacemanager/) { get; } | Obtient le gestionnaire de noms de domaine. |
| [SyncRoot](../../aspose.pdf/metadata/syncroot/) { get; } | Obtient l'objet de synchronisation de la collection. |
| [Values](../../aspose.pdf/metadata/values/) { get; } | Obtient les valeurs dans les métadonnées. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf/metadata/add/#add)(KeyValuePair&lt;string, XmpValue&gt;) | Ajoute une paire avec clé et valeur dans le dictionnaire. |
| [Add](../../aspose.pdf/metadata/add/#add_3)(string, object) | Ajoute une valeur aux métadonnées. |
| [Add](../../aspose.pdf/metadata/add/#add_1)(string, XmpPdfAExtensionObject) | Ajoute une extension pdf aux métadonnées. |
| [Add](../../aspose.pdf/metadata/add/#add_2)(string, XmpValue) | Ajoute une valeur aux métadonnées. |
| [Clear](../../aspose.pdf/metadata/clear/)() | Efface les métadonnées. |
| [Contains](../../aspose.pdf/metadata/contains/#contains)(KeyValuePair&lt;string, XmpValue&gt;) | Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire. |
| [Contains](../../aspose.pdf/metadata/contains/#contains_1)(string) | Vérifie si la clé est contenue dans les métadonnées. |
| [ContainsKey](../../aspose.pdf/metadata/containskey/)(string) | Détermine si ce dictionnaire contient la clé spécifiée. |
| [CopyTo](../../aspose.pdf/metadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf/metadata/getenumerator/)() | Renvoie l'énumérateur du dictionnaire. |
| [GetNamespaceUriByPrefix](../../aspose.pdf/metadata/getnamespaceuribyprefix/)(string) | Renvoie l'URI de l'espace de noms par préfixe. |
| [GetPrefixByNamespaceUri](../../aspose.pdf/metadata/getprefixbynamespaceuri/)(string) | Renvoie le préfixe par URI de l'espace de noms. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri)(string, string) | Enregistre l'URI de l'espace de noms. |
| [RegisterNamespaceUri](../../aspose.pdf/metadata/registernamespaceuri/#registernamespaceuri_1)(string, string, string) | Enregistre l'URI de l'espace de noms. |
| [Remove](../../aspose.pdf/metadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Supprime la paire clé/valeur de la collection. |
| [Remove](../../aspose.pdf/metadata/remove/#remove_1)(string) | Supprime une entrée des métadonnées. |
| [TryGetValue](../../aspose.pdf/metadata/trygetvalue/)(string, out XmpValue) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |

### Voir aussi

* classe [XmpValue](../xmpvalue/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)