---
title: Class CompletionResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CompletionResponse. Représente une réponse de complétion de chat renvoyée par le modèle basé sur l'entrée fournie
type: docs
weight: 240
url: /fr/net/aspose.pdf.ai/completionresponse/
---
## Classe CompletionResponse

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
| [Created](../../aspose.pdf.ai/completionresponse/created/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) de la création de la complétion de chat. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations sur l'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/completionresponse/id/) { get; set; } | Obtient ou définit un identifiant unique pour la complétion de chat. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [Model](../../aspose.pdf.ai/completionresponse/model/) { get; set; } | Obtient ou définit le modèle utilisé pour la complétion de chat. |
| [Object](../../aspose.pdf.ai/completionresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours chat.completion. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison de l'erreur. |
| [SystemFingerprint](../../aspose.pdf.ai/completionresponse/systemfingerprint/) { get; set; } | Obtient ou définit l'empreinte qui représente la configuration backend avec laquelle le modèle fonctionne. Peut être utilisé en conjonction avec le paramètre de requête seed pour comprendre quand des changements backend ont été effectués qui pourraient impacter le déterminisme. |
| [Usage](../../aspose.pdf.ai/completionresponse/usage/) { get; set; } | Obtient ou définit les statistiques d'utilisation pour la requête de complétion. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.ai/completionresponse/tostring/)() | Renvoie le contenu du premier choix sous forme de chaîne. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)