---
title: "Classe CompletionCreateRequest"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.CompletionCreateRequest classe. Représente une requête pour le point de terminaison Create Chat Completion"
type: docs
weight: 230
url: /fr/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

Représente une requête pour le point de terminaison Create Chat Completion.

```csharp
public class CompletionCreateRequest
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Obtient ou définit un nombre entre -2,0 et 2,0. Les valeurs positives pénalisent les nouveaux jetons en fonction de leur fréquence existante dans le texte jusqu'à présent, diminuant la probabilité que le modèle répète la même ligne mot pour mot. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Obtient ou définit la probabilité que des jetons spécifiés apparaissent dans la complétion. Accepte un objet JSON qui associe des jetons (spécifiés par leur ID de jeton dans le tokenizer) à une valeur de biais comprise entre -100 et 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Obtient ou définit s'il faut renvoyer les probabilités logarithmiques des jetons de sortie ou non. Si vrai, renvoie les probabilités logarithmiques de chaque jeton de sortie retourné dans le contenu du message. |
| [MaxCompletionTokens](../../aspose.pdf.ai/completioncreaterequest/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons à générer dans la complétion. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Obtient ou définit une liste de messages composant la conversation jusqu'à présent. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Obtient ou définit l'ID du modèle à utiliser. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Obtient ou définit le nombre de choix de complétion de chat à générer pour chaque message d'entrée. Notez que vous serez facturé en fonction du nombre de jetons générés pour l'ensemble des choix. Gardez n à 1 pour minimiser les coûts. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Obtient ou définit un nombre compris entre -2.0 et 2.0. Les valeurs positives pénalisent les nouveaux jetons en fonction de leur apparition dans le texte actuel, augmentant la probabilité que le modèle parle de nouveaux sujets. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Obtient ou définit un objet spécifiant le format que le modèle doit produire. Compatible avec GPT-4 Turbo et tous les modèles GPT-3.5 Turbo plus récents que gpt-3.5-turbo-1106. Le définir à { \"type\": \"json_object\" } active le mode JSON, qui garantit que le message généré par le modèle est un JSON valide. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Obtient ou définit la valeur Seed. Cette fonctionnalité est en version bêta. Si spécifiée, notre système fera de son mieux pour échantillonner de manière déterministe, de sorte que des requêtes répétées avec le même seed et les mêmes paramètres devraient renvoyer le même résultat. Le déterminisme n'est pas garanti, et vous devez vous référer au paramètre de réponse system_fingerprint pour surveiller les changements côté serveur. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Obtient ou définit jusqu'à 4 séquences où l'API cessera de générer d'autres jetons. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Obtient ou définit si le streaming doit être utilisé. Si défini, les deltas de messages partiels seront envoyés, comme dans ChatGPT. Les jetons seront envoyés sous forme d'événements serveur uniquement contenant des données dès qu'ils seront disponibles, le flux étant terminé par un message data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage à utiliser, entre 0 et 2. Des valeurs plus élevées comme 0,8 rendront la sortie plus aléatoire, tandis que des valeurs plus faibles comme 0,2 la rendront plus ciblée et déterministe. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Obtient ou définit un objet qui contrôle quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils. Spécifier un outil particulier via {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} force le modèle à appeler cet outil. none est la valeur par défaut lorsqu'aucun outil n'est présent. auto est la valeur par défaut si des outils sont présents. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Obtient ou définit une liste d'outils que le modèle peut appeler. Actuellement, seules les fonctions sont prises en charge comme outil. Utilisez ceci pour fournir une liste de fonctions pour lesquelles le modèle peut générer des entrées JSON. Un maximum de 128 fonctions est pris en charge. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Obtient ou définit une alternative à l'échantillonnage avec température, appelée échantillonnage par noyau, où le modèle considère les résultats des jetons avec une masse de probabilité top_p. Ainsi, 0,1 signifie que seuls les jetons représentant les 10 % supérieurs de la masse de probabilité sont pris en compte. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Obtient ou définit un identifiant unique représentant votre utilisateur final, ce qui peut aider OpenAI à surveiller et détecter les abus. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


