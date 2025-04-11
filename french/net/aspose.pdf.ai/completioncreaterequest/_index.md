---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CompletionCreateRequest. Représente une demande pour le point de terminaison Create Chat Completion
type: docs
weight: 220
url: /fr/net/aspose.pdf.ai/completioncreaterequest/
---
## Classe CompletionCreateRequest

Représente une demande pour le point de terminaison Create Chat Completion.

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
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Obtient ou définit un nombre entre -2.0 et 2.0. Les valeurs positives pénalisent les nouveaux tokens en fonction de leur fréquence existante dans le texte jusqu'à présent, diminuant la probabilité que le modèle répète la même ligne textuellement. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Obtient ou définit la probabilité que des tokens spécifiés apparaissent dans la complétion. Accepte un objet JSON qui associe des tokens (spécifiés par leur ID de token dans le tokenizer) à une valeur de biais associée de -100 à 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Obtient ou définit si les probabilités logarithmiques des tokens de sortie doivent être retournées ou non. Si vrai, retourne les probabilités logarithmiques de chaque token de sortie retourné dans le contenu du message. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | Obtient ou définit le nombre maximum de tokens à générer dans la complétion. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Obtient ou définit une liste de messages comprenant la conversation jusqu'à présent. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Obtient ou définit l'ID du modèle à utiliser. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Obtient ou définit combien de choix de complétion de chat générer pour chaque message d'entrée. Notez que vous serez facturé en fonction du nombre de tokens générés dans tous les choix. Gardez n à 1 pour minimiser les coûts. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Obtient ou définit un nombre entre -2.0 et 2.0. Les valeurs positives pénalisent les nouveaux tokens en fonction de leur apparition dans le texte jusqu'à présent, augmentant la probabilité que le modèle parle de nouveaux sujets. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Obtient ou définit un objet spécifiant le format que le modèle doit produire. Compatible avec GPT-4 Turbo et tous les modèles GPT-3.5 Turbo plus récents que gpt-3.5-turbo-1106. Définir sur { "type": "json_object" } active le mode JSON, ce qui garantit que le message généré par le modèle est un JSON valide. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Obtient ou définit la valeur Seed. Cette fonctionnalité est en Beta. Si spécifié, notre système fera de son mieux pour échantillonner de manière déterministe, de sorte que des demandes répétées avec la même seed et les mêmes paramètres devraient retourner le même résultat. La déterminisme n'est pas garanti, et vous devriez vous référer au paramètre de réponse system_fingerprint pour surveiller les changements dans le backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Obtient ou définit jusqu'à 4 séquences où l'API cessera de générer d'autres tokens. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Obtient ou définit si l'on doit utiliser le streaming. Si défini, des deltas de message partiels seront envoyés, comme dans ChatGPT. Les tokens seront envoyés en tant qu'événements envoyés par le serveur uniquement en données au fur et à mesure qu'ils deviennent disponibles, le flux étant terminé par un message data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Obtient ou définit quelle température d'échantillonnage utiliser, entre 0 et 2. Des valeurs plus élevées comme 0.8 rendront la sortie plus aléatoire, tandis que des valeurs plus basses comme 0.2 la rendront plus ciblée et déterministe. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Obtient ou définit un objet qui contrôle quel (le cas échéant) outil est appelé par le modèle. none signifie que le modèle n'appellera aucun outil et générera plutôt un message. auto signifie que le modèle peut choisir entre générer un message ou appeler un ou plusieurs outils. required signifie que le modèle doit appeler un ou plusieurs outils. Spécifier un outil particulier via {"type": "function", "function": {"name": "my_function"}} force le modèle à appeler cet outil. none est la valeur par défaut lorsque aucun outil n'est présent. auto est la valeur par défaut si des outils sont présents. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Obtient ou définit une liste d'outils que le modèle peut appeler. Actuellement, seules les fonctions sont prises en charge en tant qu'outil. Utilisez ceci pour fournir une liste de fonctions pour lesquelles le modèle peut générer des entrées JSON. Un maximum de 128 fonctions est pris en charge. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Obtient ou définit une alternative à l'échantillonnage avec température, appelée échantillonnage par noyau, où le modèle considère les résultats des tokens avec une masse de probabilité top_p. Donc 0.1 signifie que seuls les tokens composant les 10% supérieurs de la masse de probabilité sont considérés. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Obtient ou définit un identifiant unique représentant votre utilisateur final, ce qui peut aider OpenAI à surveiller et détecter les abus. |

### Voir aussi

* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)