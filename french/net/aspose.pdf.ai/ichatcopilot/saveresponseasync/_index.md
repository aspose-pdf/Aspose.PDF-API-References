---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Méthode IChatCopilot. Enregistre de manière asynchrone la réponse pour le message donné dans un fichier PDF
type: docs
weight: 40
url: /fr/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Enregistre de manière asynchrone la réponse pour le message donné dans un fichier PDF.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| message | String | Le message d'entrée pour lequel la réponse est enregistrée. |
| outputFileName | String | Le nom du fichier PDF de sortie pour enregistrer la réponse. |
| cancellationToken | Nullable`1 | Le jeton d'annulation (optionnel). |

### Valeur de retour

Une tâche représentant l'opération asynchrone.

### Voir aussi

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Enregistre de manière asynchrone la réponse pour le message donné dans un fichier avec le format spécifié.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| message | String | Le message d'entrée pour lequel la réponse est enregistrée. |
| outputFileName | String | Le nom du fichier de sortie pour enregistrer la réponse. |
| saveFormat | SaveFormat | Le format dans lequel enregistrer la réponse (PDF si non spécifié). |
| cancellationToken | Nullable`1 | Le jeton d'annulation (optionnel). |

### Valeur de retour

Une tâche représentant l'opération asynchrone.

### Voir aussi

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Enregistre de manière asynchrone les réponses pour la liste donnée de messages dans un fichier PDF.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| messages | List`1 | La liste des messages d'entrée pour lesquels les réponses sont enregistrées. |
| outputFileName | String | Le nom du fichier PDF de sortie pour enregistrer les réponses. |
| cancellationToken | Nullable`1 | Le jeton d'annulation (optionnel). |

### Valeur de retour

Une tâche représentant l'opération asynchrone.

### Voir aussi

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Enregistre de manière asynchrone les réponses pour la liste donnée de messages dans un fichier avec le format spécifié.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| messages | List`1 | La liste des messages d'entrée pour lesquels les réponses sont enregistrées. |
| outputFileName | String | Le nom du fichier de sortie pour enregistrer les réponses. |
| saveFormat | SaveFormat | Le format dans lequel enregistrer les réponses (PDF si non spécifié). |
| cancellationToken | Nullable`1 | Le jeton d'annulation (optionnel). |

### Valeur de retour

Une tâche représentant l'opération asynchrone.

### Voir aussi

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)