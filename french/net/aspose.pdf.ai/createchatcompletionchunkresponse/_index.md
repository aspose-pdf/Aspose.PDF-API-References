---
title: Class CreateChatCompletionChunkResponse
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Représente un morceau diffusé d'une réponse de complétion de chat renvoyée par le modèle basé sur l'entrée fournie
type: docs
weight: 250
url: /fr/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## Classe CreateChatCompletionChunkResponse

Représente un morceau diffusé d'une réponse de complétion de chat renvoyée par le modèle, basé sur l'entrée fournie.

```csharp
public class CreateChatCompletionChunkResponse
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CreateChatCompletionChunkResponse](createchatcompletionchunkresponse/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Obtient ou définit une liste de choix de complétion de chat. Peut contenir plus d'un élément si n est supérieur à 1. Peut également être vide pour le dernier morceau si vous définissez stream_options: {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Obtient ou définit le timestamp Unix (en secondes) de la création de la complétion de chat. Chaque morceau a le même timestamp. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Obtient ou définit un identifiant unique pour la complétion de chat. Chaque morceau a le même ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Obtient ou définit le modèle pour générer la complétion. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Obtient ou définit l'empreinte qui représente la configuration du backend avec laquelle le modèle fonctionne. Peut être utilisé en conjonction avec le paramètre de requête seed pour comprendre quand des modifications de backend ont été apportées qui pourraient affecter le déterminisme. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Obtient ou définit un champ optionnel qui ne sera présent que lorsque vous définissez stream_options: {"include_usage": true} dans votre requête. Lorsqu'il est présent, il contient une valeur nulle sauf pour le dernier morceau qui contient les statistiques d'utilisation des tokens pour l'ensemble de la requête. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)