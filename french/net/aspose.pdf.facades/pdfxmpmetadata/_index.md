---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfXmpMetadata. Classe pour la manipulation des métadonnées XMP
type: docs
weight: 4640
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/
---
## Classe PdfXmpMetadata

Classe pour la manipulation des métadonnées XMP.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Constructeur pour PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Initialise un nouvel objet `PdfXmpMetadata` sur la base du *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Obtient le nombre d'éléments dans la collection. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur lequel elle travaille. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Obtient le dictionnaire des champs d'extension. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Renvoie vrai si la collection a une taille fixe. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Renvoie vrai si la collection est en lecture seule. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Renvoie vrai si la collection est synchronisée. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Obtient ou définit la valeur par clé. (2 indexeurs) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Obtient les clés du dictionnaire. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Obtient l'objet de synchronisation de la collection. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Obtient la collection de valeurs dans le dictionnaire. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Ajoute une paire avec clé et valeur dans le dictionnaire. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Ajoute une valeur aux métadonnées XMP. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Ajoute un nouvel élément à l'objet dictionnaire. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Ajoute un nouvel élément à l'objet dictionnaire. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Ajoute un champ d'extension dans les métadonnées. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Supprime tous les éléments de l'objet. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Dispose d'Aspose.Pdf.Document lié à une façade. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Vérifie si le dictionnaire contient la propriété spécifiée. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Vérifie si le dictionnaire contient la clé spécifiée. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Détermine si ce dictionnaire contient la clé spécifiée. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose de la façade. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Obtient l'objet énumérateur du dictionnaire. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Obtient l'URI de l'espace de noms par préfixe. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Obtient le préfixe par URI d'espace de noms. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Obtient les métadonnées XmpMetadata du pdf d'entrée au format xml. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Obtient une partie des métadonnées XmpMetadata du pdf d'entrée selon un nom de métadonnée. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Enregistre l'URI de l'espace de noms. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Supprime l'élément avec la clé spécifiée. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Supprime la paire clé/valeur de la collection. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Supprime la clé du dictionnaire. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Enregistre le document PDF dans le fichier spécifié. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si trouvée. |

### Voir aussi

* classe [SaveableFacade](../saveablefacade/)
* classe [XmpValue](../../aspose.pdf/xmpvalue/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)