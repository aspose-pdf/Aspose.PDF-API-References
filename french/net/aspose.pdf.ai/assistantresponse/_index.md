---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.AssistantResponse. Représente un assistant qui peut appeler le modèle et utiliser des outils
type: docs
weight: 140
url: /fr/net/aspose.pdf.ai/assistantresponse/
---
## Classe AssistantResponse

Représente un assistant qui peut appeler le modèle et utiliser des outils.

```csharp
public class AssistantResponse : BaseResponse
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) pour le moment où l'assistant a été créé. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Obtient ou définit la description de l'assistant. La longueur maximale est de 512 caractères. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Obtient ou définit le détail de la réponse. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Obtient ou définit l'erreur de réponse HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Obtient ou définit les informations d'erreur. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Obtient ou définit les en-têtes de réponse HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Obtient ou définit le code d'état HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Obtient ou définit l'identifiant, qui peut être référencé dans les points de terminaison de l'API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Obtient ou définit les instructions système que l'assistant utilise. La longueur maximale est de 256 000 caractères. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Indique si la réponse a été réussie. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur qui peuvent être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent avoir une longueur maximale de 64 caractères et les valeurs peuvent avoir une longueur maximale de 512 caractères. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Obtient ou définit l'ID du modèle à utiliser. Vous pouvez utiliser l'API Liste des modèles pour voir tous vos modèles disponibles, ou consulter notre aperçu des modèles pour des descriptions. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Obtient ou définit le nom de l'assistant. La longueur maximale est de 256 caractères. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours assistant. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Obtient la phrase de raison d'erreur. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Obtient ou définit le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Définir sur { "type": "json_object" } active le mode JSON, ce qui garantit que le message généré par le modèle est un JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également demander au modèle de produire du JSON vous-même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux interminable d'espaces jusqu'à ce que la génération atteigne la limite de jetons, entraînant une demande de longue durée et apparemment "bloquée". Notez également que le contenu du message peut être partiellement coupé si finish_reason="length", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Obtient ou définit quelle température d'échantillonnage utiliser, entre 0 et 2. Des valeurs plus élevées comme 0.8 rendront la sortie plus aléatoire, tandis que des valeurs plus basses comme 0.2 la rendront plus ciblée et déterministe. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Obtient ou définit un ensemble de ressources utilisées par les outils de l'assistant. Les ressources sont spécifiques au type d'outil. Par exemple, l'outil code_interpreter nécessite une liste d'ID de fichiers, tandis que l'outil file_search nécessite une liste d'ID de magasin de vecteurs. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Obtient ou définit une liste d'outils activés sur l'assistant. Il peut y avoir un maximum de 128 outils par assistant. Les outils peuvent être de types code_interpreter, file_search ou function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Obtient ou définit une alternative à l'échantillonnage avec température, appelée échantillonnage par noyau, où le modèle considère les résultats des jetons avec une masse de probabilité top_p. Ainsi, 0.1 signifie que seuls les jetons composant les 10 % supérieurs de la masse de probabilité sont considérés. Nous recommandons généralement de modifier cela ou la température, mais pas les deux. |

### Voir aussi

* classe [BaseResponse](../baseresponse/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)