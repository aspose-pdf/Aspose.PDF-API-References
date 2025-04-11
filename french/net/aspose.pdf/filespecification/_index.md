---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.FileSpecification. Classe représentant un fichier intégré
type: docs
weight: 4850
url: /fr/net/aspose.pdf/filespecification/
---
## Classe FileSpecification

Classe représentant un fichier intégré.

```csharp
public sealed class FileSpecification : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | Créer une nouvelle spécification de fichier vide. |
| [FileSpecification](filespecification/#constructor_3)(string) | Constructeur pour FileSpecification |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | Constructeur pour la spécification de fichier. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | Constructeur pour FileSpecification. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | Constructeur pour FileSpecification. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | Constructeur pour FileSpecification. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | Relation de fichier associée. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | Obtient un élément de collection de la spécification de fichier. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | Obtient ou définit le fichier de contenu. Cette propriété retourne des données chargées en mémoire, ce qui peut provoquer une exception de mémoire insuffisante pour de grandes données. Pour réduire l'utilisation de la mémoire, veuillez utiliser StreamContents. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | Obtient ou définit le texte associé à la spécification de fichier. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | Obtient ou définit le format d'encodage. Valeurs possibles : Zip - le fichier est compressé avec ZIP, None - le fichier n'est pas compressé. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | Obtient la charge utile chiffrée. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | Obtient ou définit le nom du système de fichiers. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | Si vrai, le contenu du fichier sera inclus dans la spécification de fichier. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | Obtient le sous-type du fichier intégré |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | Obtient ou définit le nom de la spécification de fichier. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | Obtient les paramètres du fichier. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | Obtient le contenu du fichier sous forme de flux. Le contenu n'est pas chargé en mémoire, ce qui permet de réduire l'utilisation de la mémoire. Mais ce flux ne prend pas en charge le positionnement et la propriété Length. Si vous avez besoin de ces fonctionnalités, veuillez utiliser la propriété Contents à la place. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | Obtient ou définit le nom unicode de la spécification de fichier. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | Libérer le contenu. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | Obtient un paramètre spécifique à l'application. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | Définit un paramètre spécifique à l'application. |

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)