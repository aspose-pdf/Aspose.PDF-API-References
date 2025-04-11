---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.Plugins.IOperationResult. Interface générale de résultat d'opération qui définit des méthodes communes que le résultat d'opération de plugin concret doit implémenter
type: docs
weight: 8850
url: /fr/net/aspose.pdf.plugins/ioperationresult/
---
## Interface IOperationResult

Interface générale de résultat d'opération qui définit des méthodes communes que le résultat d'opération de plugin concret doit implémenter.

```csharp
public interface IOperationResult
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Obtient les données brutes. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Indique si le résultat est un chemin vers un fichier de sortie. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Indique si le résultat est un flux de sortie. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Indique si le résultat est une chaîne de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Essaie de convertir le résultat en fichier. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Essaie de convertir le résultat en objet de flux. |

### Voir aussi

* espace de noms [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)