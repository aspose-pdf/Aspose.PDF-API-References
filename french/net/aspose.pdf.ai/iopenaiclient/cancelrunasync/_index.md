---
title: "IOpenAIClient.CancelRunAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode IOpenAIClient. Annule une exécution existante dans un fil de manière asynchrone"
type: docs
weight: 10
url: /fr/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## IOpenAIClient.CancelRunAsync method

Annule de manière asynchrone une exécution existante au sein d'un fil.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du thread contenant le run à annuler. |
| runId | String | L'ID du run à annuler. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient la réponse de l'annulation du run.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID de l'exécution est nul ou vide. |

### Voir aussi

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


