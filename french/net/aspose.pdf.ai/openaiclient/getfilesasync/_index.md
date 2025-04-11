---
title: OpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode OpenAIClient. Récupère une liste de fichiers de manière asynchrone en fonction du but spécifié
type: docs
weight: 230
url: /fr/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## Méthode OpenAIClient.GetFilesAsync

Récupère une liste de fichiers de manière asynchrone en fonction du but spécifié.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| purpose | String | Optionnel. Le but des fichiers à récupérer. Si null, les fichiers pour tous les buts sont récupérés. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste de fichiers.

### Voir aussi

* classe [FileListResponse](../../filelistresponse/)
* classe [OpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)