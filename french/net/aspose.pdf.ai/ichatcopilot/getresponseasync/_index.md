---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IChatCopilot. Obtient de manière asynchrone une réponse pour le message donné
type: docs
weight: 20
url: /fr/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Obtient de manière asynchrone une réponse pour le message donné.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| message | String | Le message d'entrée pour lequel une réponse est demandée. |
| cancellationToken | Nullable`1 | Le jeton d'annulation (facultatif). |

### Valeur de retour

Une tâche représentant l'opération asynchrone avec la chaîne de réponse.

### Voir aussi

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Obtient de manière asynchrone une réponse pour la liste donnée de messages.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| messages | List`1 | La liste des messages d'entrée pour lesquels des réponses sont demandées. |
| cancellationToken | Nullable`1 | Le jeton d'annulation (facultatif). |

### Valeur de retour

Une tâche représentant l'opération asynchrone avec la chaîne de réponse.

### Voir aussi

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)