---
title: "Classe OpenAIOcrCopilotOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.OpenAIOcrCopilotOptions classe. Représente les options pour configurer le OpenAIOcrCopilot"
type: docs
weight: 990
url: /fr/net/aspose.pdf.ai/openaiocrcopilotoptions/
---
## OpenAIOcrCopilotOptions class

Représente les options pour configurer le OpenAIOcrCopilot.

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IOcrCopilotOptions<OpenAIOcrCopilotOptions>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Detail](../../aspose.pdf.ai/openaiocrcopilotoptions/detail/) { get; set; } | Obtient ou définit le niveau de détail pour l'analyse d'image. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Obtient ou définit la collection de documents à traiter. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons de complétion pouvant être utilisés au cours de l'exécution. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Obtient ou définit le modèle à utiliser pour l'assistant. |
| [Resolution](../../aspose.pdf.ai/openaiocrcopilotoptions/resolution/) { get; set; } | Obtient ou définit la résolution utilisée pour convertir les pages PDF en images. La valeur par défaut est de 300 dpi. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Obtient ou définit le chemin du fichier texte contenant les instructions système de l'assistant. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage à utiliser pour le modèle. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Obtient ou définit la valeur top-p pour l'échantillonnage par noyau. |
| [UserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/userinstructions/) { get; set; } | Obtient ou définit l'invite de l'utilisateur. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create)() | Crée une nouvelle instance de `OpenAIOcrCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/openaiocrcopilotoptions/create/#create_1)(Action&lt;OpenAIOcrCopilotOptions&gt;) | Crée une instance de `OpenAIOcrCopilotOptions` et la configure en utilisant le délégué fourni. |
| [GetOptions](../../aspose.pdf.ai/openaiocrcopilotoptions/getoptions/)() | Obtient le `OpenAIOcrCopilotOptions` actuel. |
| [WithDetail](../../aspose.pdf.ai/openaiocrcopilotoptions/withdetail/)(Detail) | Définit le niveau de détail pour l'analyse d'image. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument)(PdfDocument) | Ajoute un document PDF à la collection de documents. |
| [WithDocument](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocument/#withdocument_1)(string) | Ajoute un chemin de document à la collection de documents. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Définit la collection de documents. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Ajoute plusieurs documents PDF à la collection de documents. |
| [WithDocuments](../../aspose.pdf.ai/openaiocrcopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | Ajoute plusieurs chemins de documents à la collection de documents. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiocrcopilotoptions/withmaxcompletiontokens/)(int?) | Définit le nombre maximal de jetons de complétion. |
| [WithModel](../../aspose.pdf.ai/openaiocrcopilotoptions/withmodel/)(string) | Définit le modèle. |
| [WithResolution](../../aspose.pdf.ai/openaiocrcopilotoptions/withresolution/)(int) | Définit la résolution utilisée pour convertir les pages PDF en images. La valeur par défaut est de 300 dpi. |
| [WithSystemInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withsysteminstructions/)(string) | Définit les instructions pour les options du copilot OCR. |
| [WithTemperature](../../aspose.pdf.ai/openaiocrcopilotoptions/withtemperature/)(double?) | Définit la température. |
| [WithTopP](../../aspose.pdf.ai/openaiocrcopilotoptions/withtopp/)(double?) | Définit la valeur top P. |
| [WithUserInstructions](../../aspose.pdf.ai/openaiocrcopilotoptions/withuserinstructions/)(string) | Définit l'invite de l'utilisateur. |

### Voir aussi

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IOcrCopilotOptions&lt;TOptions&gt;](../iocrcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


