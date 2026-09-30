---
title: "OpenAIChatCopilotOptions Class"
linktitle: "OpenAIChatCopilotOptions"
articleTitle: "OpenAIChatCopilotOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OpenAIChatCopilotOptions class. Represents the options for configuring the OpenAICopilot."
type: docs
weight: 890
url: "/net/aspose.pdf.ai/openaichatcopilotoptions/"
keywords: "OpenAIChatCopilotOptions, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OpenAIChatCopilotOptions class

Represents the options for configuring the OpenAICopilot.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [AssistantName](./assistantname/) { get; set; } | Gets or sets the name of the assistant. |
| [ContextBackupJsonPath](./contextbackupjsonpath/) { get; set; } | Gets or sets the file path for the context backup JSON. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Gets or sets the collection of documents to be processed. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. |
| [MaxPromptTokens](./maxprompttokens/) { get; set; } | Gets or sets the maximum number of prompt tokens that may be used over the course of the run. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Gets or sets the model to use for the assistant. |
| [RestoreContextFromBackup](./restorecontextfrombackup/) { get; set; } | Gets or sets a value indicating whether to restore the context from backup. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Gets or sets the file path for the text file containing assistant system instructions. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Gets or sets the sampling temperature to use for the model. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Gets or sets the top-p value for nucleus sampling. |
| [TruncationStrategy](./truncationstrategy/) { get; set; } | Gets or sets the truncation strategy for the thread. |
| [VectorStoreExpireDays](./vectorstoreexpiredays/) { get; set; } | Gets or sets the number of days before the vector store expires. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](./create/)() | Creates a new instance of [`OpenAIChatCopilotOptions`](../../aspose.pdf.ai/openaichatcopilotoptions/). |
| static [Create](./create/)(Action<OpenAIChatCopilotOptions>) | Creates an instance of [`OpenAIChatCopilotOptions`](../../aspose.pdf.ai/openaichatcopilotoptions/) and configures it using the provided delegate. |
| [GetOptions](./getoptions/)() | Gets the current [`OpenAIChatCopilotOptions`](../../aspose.pdf.ai/openaichatcopilotoptions/). |
| [WithAssistantName](./withassistantname/)(string) | Sets the assistant name for the chat copilot options. |
| [WithContextBackupJsonPath](./withcontextbackupjsonpath/)(string) | Sets the file path for the context backup JSON in the chat copilot options. |
| [WithDocument](./withdocument/)(PdfDocument) | Adds a PDF document to the document collection for the chat copilot options. |
| [WithDocument](./withdocument/)(string) | Adds a document path to the document collection for the chat copilot options. |
| [WithDocument](./withdocument/)(TextDocument) | Adds a text document to the document collection for the chat copilot options. |
| [WithDocuments](./withdocuments/)(DocumentCollection) | Sets the document collection for the chat copilot options. |
| [WithDocuments](./withdocuments/)(List<PdfDocument>) | Adds multiple PDF documents to the document collection for the chat copilot options. |
| [WithDocuments](./withdocuments/)(List<string>) | Adds multiple document paths to the document collection for the chat copilot options. |
| [WithDocuments](./withdocuments/)(List<TextDocument>) | Adds multiple text documents to the document collection for the chat copilot options. |
| [WithInstructions](./withinstructions/)(string) | Sets the instructions for the chat copilot options. |
| [WithMaxCompletionTokens](./withmaxcompletiontokens/)(int?) | Sets the max completion tokens for the chat copilot options. |
| [WithMaxPromptTokens](./withmaxprompttokens/)(int?) | Sets the max prompt tokens for the chat copilot options. |
| [WithModel](./withmodel/)(string) | Sets the model for the chat copilot options. |
| [WithRestoreContextFromBackup](./withrestorecontextfrombackup/)(bool) | Sets whether to restore the context from backup in the chat copilot options. |
| [WithTemperature](./withtemperature/)(double?) | Sets the temperature for the chat copilot options. |
| [WithTopP](./withtopp/)(double?) | Sets the top P value for the chat copilot options. |
| [WithTruncationStrategy](./withtruncationstrategy/)(TruncationStrategy) | Sets the truncation strategy for the chat copilot options. |
| [WithVectorStoreExpireDays](./withvectorstoreexpiredays/)(int) | Sets the number of days for vector store expiration in the chat copilot options. |

### See Also

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

