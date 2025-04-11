---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIClient klass. Tillhandahåller metoder för att interagera med OpenAI API för att hantera batchar av vektorbutiksfiler
type: docs
weight: 840
url: /sv/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient klass

Tillhandahåller metoder för att interagera med OpenAI API för att hantera batchar av vektorbutiksfiler.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera vektorbutiksfiler.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera vektorbutiker.

Representerar en klient för att interagera med OpenAI API, som utökar grundläggande AI-klientfunktioner.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera körsteg inom trådar.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera filer.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera trådmeddelanden.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera trådar.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera assistenter.

Tillhandahåller en metod för att interagera med OpenAI API för att skapa fullföljanden.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera körningar inom trådar.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Hämtar eller ställer in backoff-fördröjningen i sekunder. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Hämtar eller ställer in det maximala antalet HTTP-förfrågningsåterförsök. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Hämtar eller ställer in pollingintervallet i sekunder. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Hämtar eller ställer in pollingtimeouten i sekunder. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Avbryter en befintlig körning inom en tråd asynkront. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Avbryter en specifik batch av vektorbutiksfiler asynkront. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Skapar en ny assistent asynkront. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Skapar en ny fullföljd asynkront. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Skapar en körning inom en angiven tråd asynkront. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Skapar en tråd och en körning inom den asynkront. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Skapar en ny tråd asynkront. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Skapar ett nytt meddelande inom en tråd asynkront. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Skapar en ny vektorbutik och väntar på att den ska slutföras asynkront. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Skapar en ny vektorbutik asynkront. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Skapar en ny vektorbutiksfil asynkront. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Skapar en ny batch av vektorbutiksfiler asynkront. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Tar bort en befintlig assistent asynkront. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Tar bort en specifik fil asynkront. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Tar bort en befintlig tråd asynkront. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Tar bort ett meddelande inom en tråd asynkront. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Tar bort en vektorbutik asynkront. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | Tar bort en fil inom en vektorbutik asynkront. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Frigör de resurser som används av [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Hämtar detaljer om en specifik assistent asynkront. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Hämtar en lista över assistenter asynkront. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Hämtar en instans av [`IChatCopilot`](../ichatcopilot/) med de angivna alternativen. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Hämtar detaljer om en specifik fil asynkront. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Hämtar en lista över filer asynkront baserat på det angivna syftet. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Hämtar en instans av [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) med de angivna alternativen. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Hämtar detaljer om en specifik körning inom en tråd asynkront. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Hämtar en lista över körningar för en angiven tråd asynkront. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Hämtar detaljer om ett specifikt steg inom en körning asynkront. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Hämtar en lista över steg för en specifik körning inom en tråd asynkront. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Hämtar en instans av [`ISummaryCopilot`](../isummarycopilot/) med de angivna alternativen. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Hämtar detaljer om en specifik tråd asynkront. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Hämtar detaljer om ett specifikt meddelande inom en tråd asynkront. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Hämtar en lista över meddelanden för en specifik tråd asynkront. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Hämtar detaljer om en specifik vektorbutik asynkront. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | Hämtar detaljer om en specifik fil inom en vektorbutik asynkront. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Hämtar detaljer om en specifik batch av vektorbutiksfiler asynkront. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Hämtar en lista över filer inom en specifik batch av vektorbutiksfiler asynkront. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Hämtar en lista över filer inom en specifik vektorbutik asynkront. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Hämtar en lista över vektorbutiker asynkront. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifierar en befintlig assistent asynkront. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifierar en befintlig körning inom en tråd asynkront. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest) | Modifierar en befintlig tråd asynkront. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest) | Modifierar ett befintligt meddelande inom en tråd asynkront. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifierar en befintlig vektorbutik asynkront. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Kör assistenten med den angivna threadId och runCreateRequest, och hämtar asynkront assistentens svar. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Laddar upp en fil asynkront till OpenAI-servern. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Väntar på det första meddelandet från assistenten inom en tråd asynkront. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Väntar på att en körning ska slutföras inom en tråd asynkront. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Väntar på att ett specifikt trådmeddelande ska slutföras asynkront. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Väntar på att en specifik vektorbutiksfil ska slutföras asynkront. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Väntar på att en specifik vektorbutik ska slutföras asynkront. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Skapar en ny instans av [`Builder`](../openaiclient.builder/) med den angivna API-nyckeln. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| klass [Builder](../../aspose.pdf.ai/openaiclient.builder) | Builder-klass för att skapa en instans av `OpenAIClient`. |

### Se även

* klass [AIClientBase](../aiclientbase/)
* gränssnitt [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* klass [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* gränssnitt [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* klass [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* gränssnitt [IOpenAIClient](../iopenaiclient/)
* gränssnitt [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* klass [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namnrymd [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)