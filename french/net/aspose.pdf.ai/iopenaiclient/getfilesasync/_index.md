---
title: IOpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IOpenAIClient. Récupère une liste de fichiers de manière asynchrone en fonction de l'objectif spécifié
type: docs
weight: 220
url: /fr/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## Méthode IOpenAIClient.GetFilesAsync

Récupère une liste de fichiers de manière asynchrone en fonction de l'objectif spécifié.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| purpose | String | Optionnel. L'objectif des fichiers à récupérer. Si null, les fichiers pour tous les objectifs sont récupérés. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste de fichiers.

### Voir aussi

* classe [FileListResponse](../../filelistresponse/)
* interface [IOpenAIClient](../)
* espace de noms [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)