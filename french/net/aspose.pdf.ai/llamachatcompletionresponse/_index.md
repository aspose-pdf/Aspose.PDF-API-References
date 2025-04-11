---
title: Class LlamaChatCompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.LlamaChatCompletionResponse. Représente une réponse de complétion de chat renvoyée par le modèle basé sur l'entrée fournie
type: docs
weight: 690
url: /fr/net/aspose.pdf.ai/llamachatcompletionresponse/
---
## Classe LlamaChatCompletionResponse

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
| [Created](../../aspose.pdf.ai/llamachatcompletionresponse/created/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) de la création de la complétion de chat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations sur l'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/llamachatcompletionresponse/id/) { get; set; } | Obtient ou définit un identifiant unique pour la complétion de chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [Model](../../aspose.pdf.ai/llamachatcompletionresponse/model/) { get; set; } | Obtient ou définit le modèle utilisé pour la complétion de chat. |
| [Object](../../aspose.pdf.ai/llamachatcompletionresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison de l'erreur. |
| [SystemFingerprint](../../aspose.pdf.ai/llamachatcompletionresponse/systemfingerprint/) { get; set; } | Obtient ou définit l'empreinte qui représente la configuration backend avec laquelle le modèle fonctionne. |
| [Usage](../../aspose.pdf.ai/llamachatcompletionresponse/usage/) { get; set; } | Obtient ou définit les statistiques d'utilisation pour la demande de complétion. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/llamachatcompletionresponse/tostring/)() | Renvoie une représentation sous forme de chaîne du premier choix. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)