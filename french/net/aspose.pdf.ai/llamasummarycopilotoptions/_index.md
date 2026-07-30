---
title: "Classe LlamaSummaryCopilotOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.LlamaSummaryCopilotOptions. Représente les options pour configurer le OpenAICopilot"
type: docs
weight: 800
url: /fr/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions class

Représente les options pour configurer l'OpenAICopilot.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | Obtient ou définit la collection de documents à traiter. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | Obtient ou définit le nombre maximal de jetons de complétion pouvant être utilisés au cours de l'exécution. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | Obtient ou définit le modèle à utiliser pour l'assistant. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | Obtient ou définit l'invite pour instruire le modèle à fournir un résumé de document. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | Obtient ou définit le chemin du fichier texte contenant les instructions système de l'assistant. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | Obtient ou définit la température d'échantillonnage à utiliser pour le modèle. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | Obtient ou définit la valeur top-p pour l'échantillonnage par noyau. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | Crée une nouvelle instance de `LlamaSummaryCopilotOptions`. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | Crée une instance de `LlamaSummaryCopilotOptions` et la configure à l'aide du délégué fourni. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | Obtient le `LlamaSummaryCopilotOptions` actuel. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | Ajoute un document PDF à la collection de documents pour les options du copilote de résumé. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | Ajoute un chemin de document à la collection de documents pour les options du copilote de résumé. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | Ajoute un document texte à la collection de documents pour les options du copilote de résumé. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | Définit la collection de documents pour les options du copilote de résumé. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | Ajoute plusieurs documents PDF à la collection de documents pour les options du copilote de résumé. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | Ajoute plusieurs chemins de documents à la collection de documents pour les options du copilote de résumé. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | Ajoute plusieurs documents texte à la collection de documents pour les options du copilote de résumé. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | Définit les instructions pour les options du copilote de résumé. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | Définit le nombre maximal de jetons de complétion pour les options du copilote de résumé. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | Définit le modèle pour les options du copilote de résumé. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | Définit l'invite de résumé pour les options du copilote de résumé. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | Définit la température pour les options du copilote de résumé. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | Définit la valeur top P pour les options du copilote de résumé. |

### Voir aussi

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


