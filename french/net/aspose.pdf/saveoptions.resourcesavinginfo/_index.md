---
title: Class SaveOptions.ResourceSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SaveOptionsResourceSavingInfo. Cette classe représente un ensemble de données liées à la sauvegarde de fichiers de ressources externes qui se produit lors de la conversion d'un PDF vers un autre format, par exemple, HTML.
type: docs
weight: 9940
url: /fr/net/aspose.pdf/saveoptions.resourcesavinginfo/
---
## Classe SaveOptions.ResourceSavingInfo

Cette classe représente un ensemble de données liées à la sauvegarde de fichiers de ressources externes qui se produit lors de la conversion d'un PDF vers un autre format (par exemple, HTML).

```csharp
public class ResourceSavingInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où sauvegarder ce fichier. |

## Champs

| Nom | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Défini par le convertisseur. Représente le contenu binaire du fichier sauvegardé. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Ce drapeau doit être défini sur "true" dans le code personnalisé si, pour une raison quelconque, le fichier proposé doit être traité non pas avec le code personnalisé mais avec le code du convertisseur lui-même de manière standard pour le convertisseur. Ainsi, le fait de le définir sur true signifie que le code personnalisé n'a pas traité le fichier référencé et que le convertisseur doit le gérer lui-même (dans les deux sens - pour le sauvegarder quelque part et pour le nommer dans le fichier référencé). |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Défini par le convertisseur. Nom de fichier supposé qui passe du convertisseur au code de la méthode personnalisée. Peut être utilisé dans le code personnalisé pour décider comment traiter ou où sauvegarder ce fichier. |

### Voir aussi

* classe [SaveOptions](../saveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)