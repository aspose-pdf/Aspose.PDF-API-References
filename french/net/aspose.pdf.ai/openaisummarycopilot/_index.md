---
title: "Classe OpenAISummaryCopilot"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.AI.OpenAISummaryCopilot classe. Fournit des fonctionnalités pour obtenir des résumés de documents en utilisant des modèles d'IA. Exemple d'utilisation pour créer un client OpenAI en configurant les options et en utilisant le copilote de résumé"
type: docs
weight: 1000
url: /fr/net/aspose.pdf.ai/openaisummarycopilot/
---
## OpenAISummaryCopilot class

Fournit des fonctionnalités pour obtenir des résumés de documents à l'aide de modèles d'IA. Exemple d'utilisation de la création d'un client OpenAI, de la configuration des options et de l'utilisation du summary copilot.

```csharp
// Créer un client IA.
var openAiClient = OpenAIClient
    .CreateWithApiKey(ApiKey) // Create OpenAI client with the API key.
    .WithProject("proj_RoywW1DLqDC89GoAW5ngoVN8") // Configure optional parameters.
    .Build();

// Créer des options de copilote.
var options = OpenAISummaryCopilotOptions
    .Create() // Create options like this, or...
    //.Create(options => { options.Model = OpenAIModels.Gpt35Turbo; }) // ...crée en utilisant un délégué.
    .WithTemperature(0.5) // Configure other optional parameters.
    .WithDocument("DocumentInputPath") // .WithDocument methods allows to add text, pdf and paths to documents.
    .WithDocuments(new List<TextDocument>()); // .WithDocuments methods allows to add text, pdf and path collections.

// Créer le copilote de résumé.
var summaryCopilot = AICopilotFactory.CreateSummaryCopilot(openAiClient, options);

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
public class OpenAISummaryCopilot : ISummaryCopilot
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OpenAISummaryCopilot](openaisummarycopilot/)(IOpenAIClient, ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Initialise une nouvelle instance de la classe `OpenAISummaryCopilot`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [HasContext](../../aspose.pdf.ai/openaisummarycopilot/hascontext/) { get; } |  |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummaryasync/)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync_1)(CancellationToken?) |  |
| [GetSummaryDocumentAsync](../../aspose.pdf.ai/openaisummarycopilot/getsummarydocumentasync/#getsummarydocumentasync)(PageInfo, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync_1)(string, CancellationToken?) |  |
| [SaveSummaryAsync](../../aspose.pdf.ai/openaisummarycopilot/savesummaryasync/#savesummaryasync)(string, SaveFormat, CancellationToken?) |  |

### Voir aussi

* interface [ISummaryCopilot](../isummarycopilot/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


