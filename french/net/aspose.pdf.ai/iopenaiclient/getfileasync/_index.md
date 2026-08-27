---
title: "IOpenAIClient.GetFileAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Récupère les détails d'un fichier spécifique de manière asynchrone"
type: docs
weight: 210
url: /fr/net/aspose.pdf.ai/iopenaiclient/getfileasync/
---
## IOpenAIClient.GetFileAsync method

Récupère les détails d'un fichier spécifique de façon asynchrone.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileId | String | L'ID du fichier à récupérer. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient les détails du fichier.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancé lorsque l'ID du fichier est nul ou vide. |

### Voir aussi

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


