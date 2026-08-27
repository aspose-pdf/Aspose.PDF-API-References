---
title: "Classe RunThreadCreateRequest"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.RunThreadCreateRequest. Représente une requête pour créer un fil et l'exécuter en une seule requête"
type: docs
weight: 1150
url: /fr/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest class

Représente une requête pour créer un thread et l'exécuter en une seule requête.

```csharp
public class RunThreadCreateRequest
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Obtient ou définit l'ID de l'assistant à utiliser pour exécuter cette exécution. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Obtient ou définit les instructions qui remplacent les instructions de l'assistant. Cela est utile pour modifier le comportement pour chaque exécution. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons de complétion pouvant être utilisés au cours de l'exécution. L'exécution fera de son mieux pour n'utiliser que le nombre de jetons de complétion spécifié, sur plusieurs tours. Si l'exécution dépasse le nombre de jetons de complétion spécifié, elle se terminera avec le statut incomplet. Voir incomplete_details pour plus d'informations. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons d'invite pouvant être utilisés au cours de l'exécution. L'exécution fera de son mieux pour n'utiliser que le nombre de jetons d'invite spécifié, sur plusieurs tours. Si l'exécution dépasse le nombre de jetons d'invite spécifié, elle se terminera avec le statut incomplet. Voir incomplete_details pour plus d'informations. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Obtient ou définit un ensemble de 16 paires clé-valeur pouvant être attachées à un objet. Cela peut être utile pour stocker des informations supplémentaires sur l'objet dans un format structuré. Les clés peuvent contenir au maximum 64 caractères et les valeurs au maximum 512 caractères. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Obtient ou définit l'ID du Modèle à utiliser pour exécuter cette exécution. Si une valeur est fournie ici, elle remplacera le modèle associé à l'assistant. Sinon, le modèle associé à l'assistant sera utilisé. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Obtient ou définit le format que le modèle doit produire. Compatible avec GPT-4o, GPT-4 Turbo et tous les modèles GPT-3.5 Turbo depuis gpt-3.5-turbo-1106. Le définir sur { \"type\": \"json_object\" } active le mode JSON, qui garantit que le message généré par le modèle est du JSON valide. Important : lors de l'utilisation du mode JSON, vous devez également demander au modèle de produire du JSON vous‑même via un message système ou utilisateur. Sans cela, le modèle peut générer un flux infini d'espaces blancs jusqu'à ce que la génération atteigne la limite de jetons, entraînant une requête longue et apparemment « bloquée ». Notez également que le contenu du message peut être partiellement tronqué si finish_reason=\"length\", ce qui indique que la génération a dépassé max_tokens ou que la conversation a dépassé la longueur maximale du contexte. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Obtient ou définit si le streaming doit être utilisé. Si vrai, renvoie un flux d'événements qui se produisent pendant l'exécution sous forme d'événements serveur, se terminant lorsque l'exécution atteint un état terminal avec un message data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage à utiliser, entre 0 et 2. Des valeurs plus élevées comme 0,8 rendront la sortie plus aléatoire, tandis que des valeurs plus faibles comme 0,2 la rendront plus ciblée et déterministe. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Obtient ou définit une requête pour créer un fil. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Obtient ou définit quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto est la valeur par défaut et signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils avant de répondre à l'utilisateur. Spécifier un outil particulier comme {\"type\": \"file_search\"} ou {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} oblige le modèle à appeler cet outil. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Obtient ou définit un ensemble de ressources utilisées par les outils de l'assistant. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Obtient ou définit les outils qui remplacent les outils que l'assistant peut utiliser pour cette exécution. Cela est utile pour modifier le comportement pour chaque exécution. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Obtient ou définit une valeur alternative à l'échantillonnage avec température, appelée échantillonnage par noyau, où le modèle considère les résultats des jetons avec une masse de probabilité top_p. Ainsi, 0,1 signifie que seuls les jetons représentant les 10 % supérieurs de la masse de probabilité sont pris en compte. Nous recommandons généralement de modifier soit cela, soit la température, mais pas les deux. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Obtient ou définit la stratégie de troncature qui contrôle la façon dont un fil sera tronqué avant l'exécution. Utilisez-la pour contrôler la fenêtre de contexte initiale de l'exécution. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


