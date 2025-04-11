---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions. Représente les options pour configurer l'OpenAICopilot
type: docs
weight: 900
url: /fr/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## Classe OpenAIImageDescriptionCopilotOptions

Représente les options pour configurer l'OpenAICopilot.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | Obtient ou définit le nom de l'assistant. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtient ou définit la collection de documents à traiter. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | Obtient ou définit l'invite pour instruire le modèle à fournir une description d'image. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | Obtient ou définit le niveau de détail de l'image si spécifié par l'utilisateur. "low" utilise moins de jetons, vous pouvez opter pour une haute résolution en utilisant "high". Si non défini, par défaut c'est "auto". |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximum de jetons de complétion qui peuvent être utilisés au cours de l'exécution. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | Obtient ou définit le nombre maximum de jetons d'invite qui peuvent être utilisés au cours de l'exécution. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | Obtient ou définit le modèle de vision à utiliser pour l'assistant. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtient ou définit le chemin du fichier pour le fichier texte contenant les instructions système de l'assistant. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage à utiliser pour le modèle. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtient ou définit la valeur top-p pour l'échantillonnage par noyau. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | Crée une nouvelle instance de `OpenAIImageDescriptionCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Crée une instance de `OpenAIImageDescriptionCopilotOptions` et la configure en utilisant le délégué fourni. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | Obtient les `OpenAIImageDescriptionCopilotOptions` actuels. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | Définit le nom de l'assistant pour les options de copilot de description d'image. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | Ajoute un document PDF à la collection de documents pour les options de copilot de description d'image. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | Ajoute un chemin de document à la collection de documents pour les options de copilot de description d'image. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Définit la collection de documents pour les options de copilot de description d'image. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Ajoute plusieurs documents PDF à la collection de documents pour les options de copilot de description d'image. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Ajoute plusieurs chemins de documents à la collection de documents pour les options de copilot de description d'image. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | Définit l'invite pour les options de copilot de description d'image. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | Définit le niveau de détail de l'image. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | Définit les instructions pour les options de copilot de description d'image. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | Définit le nombre maximum de jetons de complétion pour les options de copilot de description d'image. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | Définit le nombre maximum de jetons d'invite pour les options de copilot de description d'image. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | Définit le modèle pour les options de copilot de description d'image. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | Définit la température pour les options de copilot de description d'image. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | Définit la valeur top P pour les options de copilot de description d'image. |

### Voir aussi

* classe [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* espace de noms [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)