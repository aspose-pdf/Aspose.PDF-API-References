---
title: "Classe RunStepResponse"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.RunStepResponse. Représente une étape dans l'exécution d'un run."
type: docs
weight: 1140
url: /fr/net/aspose.pdf.ai/runstepresponse/
---
## RunStepResponse class

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
| [CancelledAt](../../aspose.pdf.ai/runstepresponse/cancelledat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où l'étape du run a été annulée. |
| [CompletedAt](../../aspose.pdf.ai/runstepresponse/completedat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où l'étape du run a été terminée. |
| [CreatedAt](../../aspose.pdf.ai/runstepresponse/createdat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où l'étape du run a été créée. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [ExpiredAt](../../aspose.pdf.ai/runstepresponse/expiredat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où l'étape du run a expiré. Une étape est considérée comme expirée si le run parent a expiré. |
| [FailedAt](../../aspose.pdf.ai/runstepresponse/failedat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où l'étape du run a échoué. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/runstepresponse/id/) { get; set; } | Obtient ou définit l'identifiant de l'étape du run, qui peut être référencé dans les points de terminaison API. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a réussi. |
| [LastError](../../aspose.pdf.ai/runstepresponse/lasterror/) { get; set; } | Obtient ou définit la dernière erreur associée à cette étape du run. Sera null s'il n'y a aucune erreur. |
| [Metadata](../../aspose.pdf.ai/runstepresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur pouvant être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent contenir au maximum 64 caractères et les valeurs au maximum 512 caractères. |
| [Object](../../aspose.pdf.ai/runstepresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours thread.run.step. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [RunId](../../aspose.pdf.ai/runstepresponse/runid/) { get; set; } | Obtient ou définit l'ID de l'exécution dont cette étape d'exécution fait partie. |
| [RunStepType](../../aspose.pdf.ai/runstepresponse/runsteptype/) { get; set; } | Obtient ou définit le type d'étape d'exécution, qui peut être soit message_creation soit tool_calls. |
| [Status](../../aspose.pdf.ai/runstepresponse/status/) { get; set; } | Obtient ou définit le statut de l'étape d'exécution, qui peut être soit in_progress, cancelled, failed, completed ou expired. |
| [StepDetails](../../aspose.pdf.ai/runstepresponse/stepdetails/) { get; set; } | Obtient ou définit les détails de l'étape d'exécution. |
| [ThreadId](../../aspose.pdf.ai/runstepresponse/threadid/) { get; set; } | Obtient ou définit l'ID du fil qui a été exécuté. |
| [Usage](../../aspose.pdf.ai/runstepresponse/usage/) { get; set; } | Obtient ou définit les statistiques d'utilisation liées à l'étape d'exécution. Cette valeur sera nulle tant que le statut de l'étape d'exécution est in_progress. |

### Voir aussi

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


