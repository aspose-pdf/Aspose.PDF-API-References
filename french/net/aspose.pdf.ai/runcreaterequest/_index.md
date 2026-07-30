---
title: "Classe RunCreateRequest"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.RunCreateRequest classe. Représente une requête pour créer une exécution"
type: docs
weight: 1060
url: /fr/net/aspose.pdf.ai/runcreaterequest/
---
## RunCreateRequest class

Représente une requête pour créer une exécution.

```csharp
public class RunCreateRequest
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RunCreateRequest](runcreaterequest/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AdditionalInstructions](../../aspose.pdf.ai/runcreaterequest/additionalinstructions/) { get; set; } | Obtient ou définit les instructions supplémentaires. Ajoute les instructions supplémentaires à la fin des instructions pour l'exécution. Ceci est utile pour modifier le comportement au niveau de chaque exécution sans remplacer les autres instructions. |
| [AdditionalMessages](../../aspose.pdf.ai/runcreaterequest/additionalmessages/) { get; set; } | Obtient ou définit les messages supplémentaires au fil avant de créer l'exécution. |
| [AssistantId](../../aspose.pdf.ai/runcreaterequest/assistantid/) { get; set; } | Obtient ou définit l'ID de l'assistant à utiliser pour exécuter cette exécution. |
| [Instructions](../../aspose.pdf.ai/runcreaterequest/instructions/) { get; set; } | Obtient ou définit les instructions qui remplacent les instructions de l'assistant. Cela est utile pour modifier le comportement pour chaque exécution. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runcreaterequest/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons de complétion pouvant être utilisés au cours de l'exécution. L'exécution fera de son mieux pour n'utiliser que le nombre de jetons de complétion spécifié, sur plusieurs tours. Si l'exécution dépasse le nombre de jetons de complétion spécifié, elle se terminera avec le statut incomplet. Voir incomplete_details pour plus d'informations. |
| [MaxPromptTokens](../../aspose.pdf.ai/runcreaterequest/maxprompttokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons d'invite pouvant être utilisés au cours de l'exécution. L'exécution fera de son mieux pour n'utiliser que le nombre de jetons d'invite spécifié, sur plusieurs tours. Si l'exécution dépasse le nombre de jetons d'invite spécifié, elle se terminera avec le statut incomplet. Voir incomplete_details pour plus d'informations. |
| [Metadata](../../aspose.pdf.ai/runcreaterequest/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur pouvant être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent contenir au maximum 64 caractères et les valeurs au maximum 512 caractères. |
| [Model](../../aspose.pdf.ai/runcreaterequest/model/) { get; set; } | Obtient ou définit l'ID du Modèle à utiliser pour exécuter cette exécution. Si une valeur est fournie ici, elle remplacera le modèle associé à l'assistant. Sinon, le modèle associé à l'assistant sera utilisé. |
| [ResponseFormat](../../aspose.pdf.ai/runcreaterequest/responseformat/) { get; set; } | Obtient ou définit le format de réponse. Spécifie le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Le définir sur { \"type\": \"json_object\" } active le mode JSON, qui garantit que le message généré par le modèle est du JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également demander au modèle de produire du JSON vous‑même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux infini d'espaces blancs jusqu'à ce que la génération atteigne la limite de jetons, entraînant une requête longue et apparemment « stuck ». Notez également que le contenu du message peut être partiellement tronqué si finish_reason=\"length\", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte. |
| [Stream](../../aspose.pdf.ai/runcreaterequest/stream/) { get; set; } | Obtient ou définit si le streaming doit être utilisé. Si vrai, renvoie un flux d'événements qui se produisent pendant l'exécution sous forme d'événements serveur, se terminant lorsque l'exécution atteint un état terminal avec un message data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runcreaterequest/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage à utiliser, entre 0 et 2. Des valeurs plus élevées comme 0,8 rendront la sortie plus aléatoire, tandis que des valeurs plus faibles comme 0,2 la rendront plus ciblée et déterministe. |
| [ToolChoice](../../aspose.pdf.ai/runcreaterequest/toolchoice/) { get; set; } | Obtient ou définit quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto est la valeur par défaut et signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils avant de répondre à l'utilisateur. Spécifier un outil particulier comme {\"type\": \"file_search\"} ou {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} oblige le modèle à appeler cet outil. |
| [Tools](../../aspose.pdf.ai/runcreaterequest/tools/) { get; set; } | Obtient ou définit les outils qui remplacent les outils que l'assistant peut utiliser pour cette exécution. Cela est utile pour modifier le comportement pour chaque exécution. |
| [TopP](../../aspose.pdf.ai/runcreaterequest/topp/) { get; set; } | Obtient ou définit une alternative à l'échantillonnage avec température, appelée échantillonnage nucleus, où le modèle considère les résultats des tokens avec une masse de probabilité top_p. Ainsi, 0,1 signifie que seuls les tokens représentant les 10 % supérieurs de la masse de probabilité sont pris en compte. Nous recommandons généralement de modifier soit cela, soit la température, mais pas les deux. |
| [TruncationStrategy](../../aspose.pdf.ai/runcreaterequest/truncationstrategy/) { get; set; } | Obtient ou définit la stratégie de troncature. Contrôle la façon dont un fil sera tronqué avant l'exécution. Utilisez ceci pour contrôler la fenêtre de contexte initiale de l'exécution. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


