---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CreateEmbeddingRequest. Représente une requête pour le point de terminaison Create Embeddings
type: docs
weight: 260
url: /fr/net/aspose.pdf.ai/createembeddingrequest/
---
## Classe CreateEmbeddingRequest

Représente une requête pour le point de terminaison Create Embeddings.

```csharp
public class CreateEmbeddingRequest
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Obtient ou définit le nombre de dimensions que les embeddings de sortie résultants doivent avoir. Prise en charge uniquement dans les modèles text-embedding-3 et ultérieurs. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Obtient ou définit le format dans lequel retourner les embeddings. Peut être soit float soit base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Obtient ou définit le texte d'entrée à intégrer, encodé sous forme de chaîne ou de tableau de tokens. Pour intégrer plusieurs entrées dans une seule requête, passez un tableau de chaînes ou un tableau de tableaux de tokens. L'entrée ne doit pas dépasser le nombre maximal de tokens d'entrée pour le modèle (8192 tokens pour text-embedding-ada-002), ne peut pas être une chaîne vide, et tout tableau doit avoir 2048 dimensions ou moins. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Obtient ou définit le modèle pour générer l'embedding. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Obtient ou définit un identifiant unique représentant votre utilisateur final, ce qui peut aider OpenAI à surveiller et détecter les abus. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)