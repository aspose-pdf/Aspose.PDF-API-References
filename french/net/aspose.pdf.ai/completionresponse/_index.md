---
title: "Classe CompletionResponse"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.CompletionResponse class. Représente une réponse de complétion de chat renvoyée par le modèle en fonction de l'entrée fournie"
type: docs
weight: 250
url: /fr/net/aspose.pdf.ai/completionresponse/
---
## CompletionResponse class

Représente une réponse de complétion de chat renvoyée par le modèle, basée sur l'entrée fournie.

```csharp
public class CompletionResponse : BaseResponse
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CompletionResponse](completionresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/completionresponse/choices/) { get; set; } | Obtient ou définit une liste de choix de complétion de chat. Peut être plus d'un si n est supérieur à 1. |
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où la complétion de chat a été créée. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Obtient ou définit un identifiant unique pour la complétion de chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a réussi. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Obtient ou définit le modèle utilisé pour la complétion de chat. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Obtient ou définit l'empreinte qui représente la configuration du backend avec laquelle le modèle s'exécute. Peut être utilisé conjointement avec le paramètre de requête seed pour comprendre quand des changements du backend ont été effectués et pourraient affecter le déterminisme. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Obtient ou définit les statistiques d'utilisation pour la requête de complétion. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Renvoie le contenu du premier choix sous forme de chaîne. |

### Voir aussi

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


