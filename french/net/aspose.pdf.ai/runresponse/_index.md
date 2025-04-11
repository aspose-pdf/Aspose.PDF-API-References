---
title: Class RunResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.RunResponse. Représente une exécution sur un thread
type: docs
weight: 1020
url: /fr/net/aspose.pdf.ai/runresponse/
---
## Classe RunResponse

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
| [AssistantId](../../aspose.pdf.ai/runresponse/assistantid/) { get; set; } | Obtient ou définit l'ID de l'assistant utilisé pour l'exécution de cette exécution. |
| [CancelledAt](../../aspose.pdf.ai/runresponse/cancelledat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'exécution a été annulée. |
| [CompletedAt](../../aspose.pdf.ai/runresponse/completedat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'exécution a été complétée. |
| [CreatedAt](../../aspose.pdf.ai/runresponse/createdat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'exécution a été créée. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations sur l'erreur. |
| [ExpiresAt](../../aspose.pdf.ai/runresponse/expiresat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'exécution expirera. |
| [FailedAt](../../aspose.pdf.ai/runresponse/failedat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'exécution a échoué. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/runresponse/id/) { get; set; } | Obtient ou définit l'identifiant, qui peut être référencé dans les points de terminaison de l'API. |
| [IncompleteDetails](../../aspose.pdf.ai/runresponse/incompletedetails/) { get; set; } | Obtient ou définit les détails sur pourquoi l'exécution est incomplète. Sera nul si l'exécution n'est pas incomplète. |
| [Instructions](../../aspose.pdf.ai/runresponse/instructions/) { get; set; } | Obtient ou définit les instructions que l'assistant a utilisées pour cette exécution. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [LastError](../../aspose.pdf.ai/runresponse/lasterror/) { get; set; } | Obtient ou définit la dernière erreur associée à cette exécution. Sera nul s'il n'y a pas d'erreurs. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runresponse/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximum de tokens de complétion spécifiés comme ayant été utilisés au cours de l'exécution. |
| [MaxPromptTokens](../../aspose.pdf.ai/runresponse/maxprompttokens/) { get; set; } | Obtient ou définit le nombre maximum de tokens d'invite spécifiés comme ayant été utilisés au cours de l'exécution. |
| [Metadata](../../aspose.pdf.ai/runresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur qui peuvent être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent avoir une longueur maximale de 64 caractères et les valeurs peuvent avoir une longueur maximale de 512 caractères. |
| [Model](../../aspose.pdf.ai/runresponse/model/) { get; set; } | Obtient ou définit le modèle que l'assistant a utilisé pour cette exécution. |
| [Object](../../aspose.pdf.ai/runresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours thread.run. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison de l'erreur. |
| [RequiredAction](../../aspose.pdf.ai/runresponse/requiredaction/) { get; set; } | Obtient ou définit les détails sur l'action requise pour continuer l'exécution. Sera nul si aucune action n'est requise. |
| [ResponseFormat](../../aspose.pdf.ai/runresponse/responseformat/) { get; set; } | Obtient ou définit le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo, et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Définir sur { "type": "json_object" } active le mode JSON, ce qui garantit que le message généré par le modèle est un JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également demander au modèle de produire du JSON vous-même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux interminable d'espaces blancs jusqu'à ce que la génération atteigne la limite de tokens, entraînant une demande de longue durée et apparemment "bloquée". Notez également que le contenu du message peut être partiellement coupé si finish_reason="length", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte. |
| [StartedAt](../../aspose.pdf.ai/runresponse/startedat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'exécution a été démarrée. |
| [Status](../../aspose.pdf.ai/runresponse/status/) { get; set; } | Obtient ou définit le statut de l'exécution, qui peut être soit en attente, en cours, nécessite une action, annulation, annulée, échouée, complétée, incomplète, ou expirée. |
| [Temperature](../../aspose.pdf.ai/runresponse/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage utilisée pour cette exécution. Si non définie, par défaut à 1. |
| [ThreadId](../../aspose.pdf.ai/runresponse/threadid/) { get; set; } | Obtient ou définit l'ID du thread qui a été exécuté dans le cadre de cette exécution. |
| [ToolChoice](../../aspose.pdf.ai/runresponse/toolchoice/) { get; set; } | Obtient ou définit quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto est la valeur par défaut et signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils avant de répondre à l'utilisateur. Spécifier un outil particulier comme {"type": "file_search"} ou {"type": "function", "function": {"name": "my_function"}} force le modèle à appeler cet outil. |
| [Tools](../../aspose.pdf.ai/runresponse/tools/) { get; set; } | Obtient ou définit la liste des outils que l'assistant a utilisés pour cette exécution. |
| [TopP](../../aspose.pdf.ai/runresponse/topp/) { get; set; } | Obtient ou définit la valeur d'échantillonnage du noyau utilisée pour cette exécution. Si non définie, par défaut à 1. |
| [TruncationStrategy](../../aspose.pdf.ai/runresponse/truncationstrategy/) { get; set; } | Obtient ou définit la stratégie de troncature qui contrôle comment un thread sera tronqué avant l'exécution. Utilisez ceci pour contrôler la fenêtre de contexte initiale de l'exécution. |
| [Usage](../../aspose.pdf.ai/runresponse/usage/) { get; set; } | Obtient ou définit les statistiques d'utilisation liées à l'exécution. Cette valeur sera nulle si l'exécution n'est pas dans un état terminal (c'est-à-dire en cours, en attente, etc.). |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* interface [IStatus](../istatus/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)