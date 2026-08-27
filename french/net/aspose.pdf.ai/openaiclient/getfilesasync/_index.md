---
title: "OpenAIClient.GetFilesAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OpenAIClient. Récupère une liste de fichiers de manière asynchrone en fonction du but spécifié"
type: docs
weight: 230
url: /fr/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## OpenAIClient.GetFilesAsync method

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
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


