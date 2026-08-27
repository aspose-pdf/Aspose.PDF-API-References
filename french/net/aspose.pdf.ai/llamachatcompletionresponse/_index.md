---
title: "Classe LlamaChatCompletionResponse"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.LlamaChatCompletionResponse. Représente une réponse de complétion de chat renvoyée par le modèle en fonction de l'entrée fournie."
type: docs
weight: 740
url: /fr/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## LlamaChatCompletionResponse class

Représente une réponse de complétion de chat renvoyée par le modèle, basée sur l'entrée fournie.

```csharp
public class LlamaChatCompletionResponse : BaseResponse
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LlamaChatCompletionResponse](llamachatcompletionresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/llamachatcompletionresponse/choices/) { get; set; } | Obtient ou définit une liste de choix de complétion de chat. Peut être plus d'un si n est supérieur à 1. |
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où la complétion de chat a été créée. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Obtient ou définit un identifiant unique pour la complétion de chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a réussi. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Obtient ou définit le modèle utilisé pour la complétion de chat. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Obtient ou définit l'empreinte digitale qui représente la configuration du backend avec laquelle le modèle s'exécute. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Obtient ou définit les statistiques d'utilisation pour la requête de complétion. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Renvoie une représentation sous forme de chaîne du premier choix. |

### Voir aussi

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


