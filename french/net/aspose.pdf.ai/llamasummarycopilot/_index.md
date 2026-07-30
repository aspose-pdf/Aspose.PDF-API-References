---
title: "Classe LlamaSummaryCopilot"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.AI.LlamaSummaryCopilot. Fournit des fonctionnalités pour obtenir des résumés de documents à l'aide de modèles d'IA. Exemple d'utilisation pour créer un client Llama, configurer les options et utiliser le copilote de résumé. Remarque : ce copilote utilise l'API de complétion, de sorte que la quantité totale de texte pouvant être envoyée est limitée par la fenêtre de contexte du modèle."
type: docs
weight: 790
url: /fr/net/aspose.pdf.ai/llamasummarycopilot/
---
## LlamaSummaryCopilot class

Fournit des fonctionnalités pour obtenir des résumés de documents en utilisant des modèles d'IA. Exemple d'utilisation pour créer un client Llama, configurer les options et utiliser le copilote de résumé. Remarque : ce copilote utilise l'API de complétion, donc la quantité totale de texte pouvant être envoyée est limitée par la fenêtre de contexte du modèle.

```csharp
// Créer un client IA.
var llamaClient = LlamaClient
   .CreateWithApiKey(ApiKey) // Create Llama client with the API key.
   .Build();

// Créer des options de copilote.
var options = LlamaSummaryCopilotOptions
   .Create() // Create options like this, or...
   //.Create(options => { options.Model = LlamaModels.Llama13BChat; }) // ...créer en utilisant un délégué.
   .WithTemperature(0.5) // Configure other optional parameters.
   .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
   .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Créer le copilote de résumé.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(llamaClient, options);

// Obtenir le texte du résumé.
string summaryText = await summaryCopilot.GetSummaryAsync();

// Obtenir le document de résumé.
Document summaryDocument = await summaryCopilot.GetSummaryDocumentAsync();

// Obtenir le document de résumé avec les informations de page.
Document summaryDocumentWithPageInfo = await summaryCopilot.GetSummaryDocumentAsync(new PageInfo());

// Enregistrer le résumé en tant que document PDF.
await summaryCopilot.SaveSummaryAsync("outputPath");

// Enregistrer le résumé avec le format spécifié.
await summaryCopilot.SaveSummaryAsync("outputPath", SaveFormat.DocX);
```

```csharp
public class LlamaSummaryCopilot : ISummaryCopilot
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LlamaSummaryCopilot](llamasummarycopilot/)(ILlamaClient, ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Initialise une nouvelle instance de la classe `LlamaSummaryCopilot`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/llamasummarycopilot/hascontext/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/llamasummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/llamasummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Voir aussi

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


