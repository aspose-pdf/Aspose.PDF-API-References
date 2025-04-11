---
title: Class RunStepResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.RunStepResponse. Représente une étape dans l'exécution d'un run
type: docs
weight: 1060
url: /fr/net/aspose.pdf.ai/runstepresponse/
---
## Classe RunStepResponse

Représente une étape dans l'exécution d'un run.

```csharp
public class RunStepResponse : BaseResponse
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RunStepResponse](runstepresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runstepresponse/assistantid/) { get; set; } | Obtient ou définit l'ID de l'assistant associé à l'étape du run. |
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'étape du run a été annulée. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'étape du run a été complétée. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'étape du run a été créée. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'étape du run a expiré. Une étape est considérée comme expirée si le run parent est expiré. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'étape du run a échoué. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Obtient ou définit l'identifiant de l'étape du run, qui peut être référencé dans les points de terminaison de l'API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Obtient ou définit la dernière erreur associée à cette étape du run. Sera null s'il n'y a pas d'erreurs. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur qui peuvent être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent avoir une longueur maximale de 64 caractères et les valeurs peuvent avoir une longueur maximale de 512 caractères. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison de l'erreur. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Obtient ou définit l'ID du run dont cette étape du run fait partie. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Obtient ou définit le type d'étape du run, qui peut être soit message_creation soit tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Obtient ou définit le statut de l'étape du run, qui peut être soit in_progress, cancelled, failed, completed, ou expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Obtient ou définit les détails de l'étape du run. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Obtient ou définit l'ID du thread qui a été exécuté. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Obtient ou définit les statistiques d'utilisation liées à l'étape du run. Cette valeur sera null tant que le statut de l'étape du run est in_progress. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)