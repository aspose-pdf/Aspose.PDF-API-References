---
title: "IOpenAIClient.GetFilesAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Récupère une liste de fichiers de façon asynchrone en fonction du but spécifié"
type: docs
weight: 220
url: /fr/net/aspose.pdf.ai/iopenaiclient/getfilesasync/
---
## IOpenAIClient.GetFilesAsync method

Récupère une liste de fichiers de façon asynchrone en fonction du but spécifié.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| purpose | String | Optionnel. Le but des fichiers à récupérer. Si nul, les fichiers pour tous les buts sont récupérés. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient une liste de fichiers.

### Voir aussi

* class [FileListResponse](../../filelistresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


