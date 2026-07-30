---
title: "OpenAIClient.WaitForThreadMessageToCompleteAsync"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OpenAIClient. Attend qu'un message de fil spécifique se termine de manière asynchrone"
type: docs
weight: 490
url: /fr/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## OpenAIClient.WaitForThreadMessageToCompleteAsync method

Attend qu'un message de fil de discussion spécifique se termine de manière asynchrone.

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| threadId | String | L'ID du fil contenant le message. |
| threadMessageId | String | L'ID du message à surveiller jusqu'à son achèvement. |
| cancellationToken | Nullable`1 | Un jeton pour annuler l'opération. |

### Valeur de retour

Une tâche qui représente l'opération asynchrone. Le résultat de la tâche contient l'état final du message.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du fil est nul ou vide. |
| [AIClientException](../../aiclientexception/) | Lancée lorsque l'ID du message de fil est nul ou vide. |

### Voir aussi

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


