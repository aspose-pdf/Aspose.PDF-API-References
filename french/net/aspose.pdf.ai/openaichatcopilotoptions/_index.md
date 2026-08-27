---
title: "Classe OpenAIChatCopilotOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.OpenAIChatCopilotOptions. Représente les options de configuration du OpenAICopilot"
type: docs
weight: 890
url: /fr/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions class

Représente les options pour configurer l'OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | Obtient ou définit le nom de l'assistant. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | Obtient ou définit le chemin du fichier JSON de sauvegarde du contexte. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtient ou définit la collection de documents à traiter. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons de complétion pouvant être utilisés au cours de l'exécution. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/maxprompttokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons d'invite pouvant être utilisés au cours de l'exécution. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Obtient ou définit le modèle à utiliser pour l'assistant. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut restaurer le contexte à partir de la sauvegarde. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtient ou définit le chemin du fichier texte contenant les instructions système de l'assistant. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage à utiliser pour le modèle. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtient ou définit la valeur top-p pour l'échantillonnage par noyau. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | Obtient ou définit la stratégie de troncature pour le fil. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | Obtient ou définit le nombre de jours avant l'expiration du magasin de vecteurs. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | Crée une nouvelle instance de `OpenAIChatCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | Crée une instance de `OpenAIChatCopilotOptions` et la configure à l'aide du délégué fourni. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | Obtient le `OpenAIChatCopilotOptions` actuel. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | Définit le nom de l'assistant pour les options du copilot de chat. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | Définit le chemin du fichier JSON de sauvegarde du contexte dans les options du copilot de chat. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | Ajoute un document PDF à la collection de Document pour les options du copilot de chat. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | Ajoute un chemin de Document à la collection de Document pour les options du copilot de chat. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | Ajoute un document texte à la collection de Document pour les options du copilot de chat. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Définit la collection de Document pour les options du copilot de chat. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Ajoute plusieurs documents PDF à la collection de Document pour les options du copilot de chat. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Ajoute plusieurs chemins de Document à la collection de Document pour les options du copilot de chat. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Ajoute plusieurs documents texte à la collection de Document pour les options du copilot de chat. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | Définit les instructions pour les options du copilot de chat. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | Définit le nombre maximal de jetons de complétion pour les options du copilot de chat. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | Définit le nombre maximal de jetons d'invite pour les options du copilot de chat. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | Définit le modèle pour les options du copilote de chat. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | Définit s'il faut restaurer le contexte à partir de la sauvegarde dans les options du copilote de chat. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | Définit la température pour les options du copilote de chat. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | Définit la valeur top P pour les options du copilote de chat. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | Définit la stratégie de troncature pour les options du copilote de chat. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | Définit le nombre de jours avant l'expiration du magasin de vecteurs dans les options du copilote de chat. |

### Voir aussi

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


