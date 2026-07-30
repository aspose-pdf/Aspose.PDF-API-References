---
title: "Classe RunResponse"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.RunResponse. Représente une exécution sur un thread"
type: docs
weight: 1100
url: /fr/net/aspose.pdf.ai/runresponse/
---
## RunResponse class

Représente une exécution sur un thread.

```csharp
public class RunResponse : BaseResponse, IStatus
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RunResponse](runresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Obtient ou définit l'ID de l'assistant utilisé pour l'exécution de ce run. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le run a été annulé. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le run a été terminé. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le run a été créé. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le run expirera. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le run a échoué. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Obtient ou définit l'identifiant, qui peut être référencé dans les points de terminaison API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Obtient ou définit les détails expliquant pourquoi le run est incomplet. Sera null si le run n'est pas incomplet. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Obtient ou définit les instructions que l'assistant a utilisées pour ce run. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a réussi. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Obtient ou définit la dernière erreur associée à ce run. Sera null s'il n'y a aucune erreur. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons de complétion spécifié comme ayant été utilisés au cours du run. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons d'invite spécifié comme ayant été utilisés au cours du run. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur pouvant être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent contenir au maximum 64 caractères et les valeurs au maximum 512 caractères. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Obtient ou définit le modèle que l'assistant a utilisé pour ce run. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Obtient ou définit les détails de l'action requise pour poursuivre le run. Sera null si aucune action n'est requise. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Obtient ou définit le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Le définir sur { \"type\": \"json_object\" } active le mode JSON, qui garantit que le message généré par le modèle est du JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également demander au modèle de produire du JSON vous‑même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux infini d'espaces blancs jusqu'à ce que la génération atteigne la limite de jetons, entraînant une requête longue et apparemment « bloquée ». Notez également que le contenu du message peut être partiellement tronqué si finish_reason=\"length\", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où le run a été démarré. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Obtient ou définit l'état du run, qui peut être soit queued, in_progress, requires_action, cancelling, cancelled, failed, completed, incomplete ou expired. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage utilisée pour ce run. Si non définie, la valeur par défaut est 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Obtient ou définit l'ID du thread qui a été exécuté dans le cadre de ce run. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Obtient ou définit quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto est la valeur par défaut et signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils avant de répondre à l'utilisateur. Spécifier un outil particulier comme {\"type\": \"file_search\"} ou {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} oblige le modèle à appeler cet outil. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Obtient ou définit la liste des outils que l'assistant a utilisés pour ce run. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Obtient ou définit la valeur de l'échantillonnage nucleus utilisée pour ce run. Si non définie, la valeur par défaut est 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Obtient ou définit la stratégie de troncature qui contrôle la façon dont un fil sera tronqué avant l'exécution. Utilisez-la pour contrôler la fenêtre de contexte initiale de l'exécution. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Obtient ou définit les statistiques d'utilisation liées à l'exécution. Cette valeur sera nulle si l'exécution n'est pas dans un état terminal (c.-à-d. en cours, en file d'attente, etc.). |

### Voir aussi

* class [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


