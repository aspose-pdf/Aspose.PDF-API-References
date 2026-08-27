---
title: "Classe CreateChatCompletionChunkResponse"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.CreateChatCompletionChunkResponse. Représente un fragment diffusé d'une réponse de complétion de chat renvoyée par le modèle en fonction de l'entrée fournie."
type: docs
weight: 260
url: /fr/net/aspose.pdf.ai/createchatcompletionchunkresponse/
---
## CreateChatCompletionChunkResponse class

Représente un fragment diffusé d'une réponse de complétion de chat renvoyée par le modèle, basé sur l'entrée fournie.

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
| [Choices](../../aspose.pdf.ai/createchatcompletionchunkresponse/choices/) { get; set; } | Obtient ou définit une liste de choix de complétion de chat. Peut contenir plusieurs éléments si n est supérieur à 1. Peut également être vide pour le dernier fragment si vous définissez stream_options : {"include_usage": true}. |
| [Created](../../aspose.pdf.ai/createchatcompletionchunkresponse/created/) { get; set; } | Obtient ou définit l'horodatage Unix (en secondes) du moment où la complétion de chat a été créée. Chaque fragment a le même horodatage. |
| [Id](../../aspose.pdf.ai/createchatcompletionchunkresponse/id/) { get; set; } | Obtient ou définit un identifiant unique pour la complétion de chat. Chaque fragment a le même ID. |
| [Model](../../aspose.pdf.ai/createchatcompletionchunkresponse/model/) { get; set; } | Obtient ou définit le modèle pour générer la complétion. |
| [Object](../../aspose.pdf.ai/createchatcompletionchunkresponse/object/) { get; set; } | Obtient ou définit le type d'objet, qui est toujours chat.completion.chunk. |
| [SystemFingerprint](../../aspose.pdf.ai/createchatcompletionchunkresponse/systemfingerprint/) { get; set; } | Obtient ou définit l'empreinte qui représente la configuration du backend avec laquelle le modèle s'exécute. Peut être utilisé conjointement avec le paramètre de requête seed pour comprendre quand des changements du backend ont été effectués et pourraient affecter le déterminisme. |
| [Usage](../../aspose.pdf.ai/createchatcompletionchunkresponse/usage/) { get; set; } | Obtient ou définit un champ optionnel qui ne sera présent que lorsque vous définissez stream_options : {\"include_usage\": true} dans votre requête. Lorsqu'il est présent, il contient une valeur null sauf pour le dernier segment qui contient les statistiques d'utilisation des jetons pour l'ensemble de la requête. |

### Voir aussi

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


