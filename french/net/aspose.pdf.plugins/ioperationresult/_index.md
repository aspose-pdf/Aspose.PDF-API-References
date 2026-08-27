---
title: "Interface IOperationResult"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Interface Aspose.Pdf.Plugins.IOperationResult. Interface de résultat d'opération générale qui définit les méthodes communes qu'un résultat d'opération de plugin concret doit implémenter"
type: docs
weight: 8980
url: /fr/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult interface

Interface générale de résultat d'opération qui définit les méthodes communes que le résultat d'opération de plugin concret doit implémenter.

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
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Tente de convertir le résultat en fichier. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Tente de convertir le résultat en objet flux. |

### Voir aussi

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


