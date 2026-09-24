---
title: "OpenAIOcrCopilotOptions Class"
linktitle: "OpenAIOcrCopilotOptions"
articleTitle: "OpenAIOcrCopilotOptions"
second_title: "Aspose.PDF for .NET"
description: "Represents the options for configuring the OpenAIOcrCopilot."
type: docs
weight: 990
url: "/net/aspose.pdf.ai/openaiocrcopilotoptions/"
keywords: "OpenAIOcrCopilotOptions, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OpenAIOcrCopilotOptions class

Represents the options for configuring the [OpenAIOcrCopilot](../openaiocrcopilot/).

```csharp
public class OpenAIOcrCopilotOptions : OpenAIAssistantCopilotOptionsBase
```

## Properties

| Name | Description |
| --- | --- |
| [Detail](./detail/) { get; set; } | Gets or sets the level of detail for image analysis. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | Gets or sets the collection of documents to be processed. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | Gets or sets the maximum number of completion tokens that may be used over the course of the run. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | Gets or sets the model to use for the assistant. *(Inherited from OpenAICopilotOptionsBase)* |
| [Resolution](./resolution/) { get; set; } | Gets or sets the resolution used to convert PDF pages into images. The default value is 300 dpi. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | Gets or sets the file path for the text file containing assistant system instructions. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | Gets or sets the sampling temperature to use for the model. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | Gets or sets the top-p value for nucleus sampling. *(Inherited from OpenAIAssistantCopilotOptionsBase)* |
| [UserInstructions](./userinstructions/) { get; set; } | Gets or sets the user prompt. |

## Methods

| Name | Description |
| --- | --- |
| [Create](./create/) | Creates a new instance of [`OpenAIOcrCopilotOptions`](../../aspose.pdf.ai/openaiocrcopilotoptions/). |
| [Create](./create/)(*Action<OpenAIOcrCopilotOptions>*) | Creates an instance of [`OpenAIOcrCopilotOptions`](../../aspose.pdf.ai/openaiocrcopilotoptions/) and configures it using the provided delegate. |
| [GetOptions](./getoptions/) | Gets the current [`OpenAIOcrCopilotOptions`](../../aspose.pdf.ai/openaiocrcopilotoptions/). |
| [WithDetail](./withdetail/)(*Detail*) | Sets the level of detail for image analysis. |
| [WithDocument](./withdocument/)(*PdfDocument*) | Adds a PDF document to the document collection. |
| [WithDocument](./withdocument/)(*string*) | Adds a document path to the document collection. |
| [WithDocuments](./withdocuments/)(*DocumentCollection*) | Sets the document collection. |
| [WithDocuments](./withdocuments/)(*List<PdfDocument>*) | Adds multiple PDF documents to the document collection. |
| [WithDocuments](./withdocuments/)(*List<string>*) | Adds multiple document paths to the document collection. |
| [WithMaxCompletionTokens](./withmaxcompletiontokens/)(*Nullable<int>*) | Sets the max completion tokens. |
| [WithModel](./withmodel/)(*string*) | Sets the model. |
| [WithResolution](./withresolution/)(*int*) | Sets the resolution used to convert PDF pages into images. The default value is 300 dpi. |
| [WithSystemInstructions](./withsysteminstructions/)(*string*) | Sets the instructions for the ocr copilot options. |
| [WithTemperature](./withtemperature/)(*Nullable<double>*) | Sets the temperature. |
| [WithTopP](./withtopp/)(*Nullable<double>*) | Sets the top P value. |
| [WithUserInstructions](./withuserinstructions/)(*string*) | Sets the user prompt. |

### See Also

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

