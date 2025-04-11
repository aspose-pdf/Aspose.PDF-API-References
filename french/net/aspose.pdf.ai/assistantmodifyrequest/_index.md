---
title: Class AssistantModifyRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.AssistantModifyRequest. Objet de demande pour modifier un assistant
type: docs
weight: 130
url: /fr/net/aspose.pdf.ai/assistantmodifyrequest/
---
## Classe AssistantModifyRequest

Objet de demande pour modifier un assistant.

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AssistantModifyRequest](assistantmodifyrequest/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Obtient ou définit la description de l'assistant. La longueur maximale est de 512 caractères. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Obtient ou définit les instructions système que l'assistant utilise. La longueur maximale est de 256 000 caractères. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur qui peuvent être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent avoir une longueur maximale de 64 caractères et les valeurs peuvent avoir une longueur maximale de 512 caractères. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Obtient ou définit l'ID du modèle à utiliser. Vous pouvez utiliser l'API de liste des modèles pour voir tous vos modèles disponibles, ou consulter notre aperçu des modèles pour des descriptions de ceux-ci. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Obtient ou définit le nom de l'assistant. La longueur maximale est de 256 caractères. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Obtient ou définit le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo, et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Définir sur { "type": "json_object" } active le mode JSON, ce qui garantit que le message généré par le modèle est un JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également demander au modèle de produire du JSON vous-même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux interminable d'espaces blancs jusqu'à ce que la génération atteigne la limite de jetons, ce qui entraîne une demande de longue durée et apparemment "bloquée". Notez également que le contenu du message peut être partiellement coupé si finish_reason="length", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage à utiliser, entre 0 et 2. Des valeurs plus élevées comme 0.8 rendront la sortie plus aléatoire, tandis que des valeurs plus basses comme 0.2 la rendront plus ciblée et déterministe. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Obtient ou définit les ressources utilisées par les outils de l'assistant. Les ressources sont spécifiques au type d'outil. Par exemple, l'outil code_interpreter nécessite une liste d'ID de fichiers, tandis que l'outil file_search nécessite une liste d'ID de magasin de vecteurs. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Obtient ou définit une liste d'outils activés sur l'assistant. Il peut y avoir un maximum de 128 outils par assistant. Les outils peuvent être de types code_interpreter, file_search ou function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Obtient ou définit une alternative à l'échantillonnage avec température, appelée échantillonnage par noyau, où le modèle considère les résultats des jetons avec une masse de probabilité top_p. Donc 0.1 signifie que seuls les jetons composant les 10 % supérieurs de la masse de probabilité sont considérés. Nous recommandons généralement de modifier cela ou la température mais pas les deux. |

### Voir aussi

* classe [AssistantCreateRequest](../assistantcreaterequest/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)