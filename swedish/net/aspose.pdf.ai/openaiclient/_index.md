---
title: "Klassen OpenAIClient"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.OpenAIClient-klass. Tillhandahåller metoder för att interagera med OpenAI API för att hantera vektorlagringsfilbatchar"
type: docs
weight: 900
url: /sv/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

Tillhandahåller metoder för att interagera med OpenAI API för att hantera vektorlagringsfilbatcher.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera vektorlagringsfiler.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera vektorlager.

Representerar en klient för att interagera med OpenAI API, som utökar grundläggande AI-klientfunktioner.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera körsteg inom trådar.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera filer.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera trådbudskap.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera trådar.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera assistenter.

Tillhandahåller en metod för att interagera med OpenAI API för att skapa slutföranden.

Tillhandahåller metoder för att interagera med OpenAI API för att hantera körningar inom trådar.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, 
    IOcrClient<OpenAIOcrCopilotOptions>, IOpenAIClient, ISummaryClient<OpenAISummaryCopilotOptions>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Hämtar eller anger backoff-fördröjning i sekunder. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Hämtar eller anger maximalt antal HTTP-förfrågningsförsök. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Hämtar eller anger pollingintervall i sekunder. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Hämtar eller anger polling-timeout i sekunder. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Avbryter en befintlig körning inom en tråd asynkront. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Avbryter en specifik vektorlagringsfilbatch asynkront. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Skapar en ny assistent asynkront. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Skapar en ny slutförande asynkront. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Skapar en körning inom en specificerad tråd asynkront. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Skapar en tråd och en körning i den asynkront. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Skapar en ny tråd asynkront. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Skapar ett nytt meddelande i en tråd asynkront. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Skapar en ny vektorlager och väntar på att den ska slutföras asynkront. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Skapar en ny vektorlager asynkront. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Skapar en ny vektorlagerfil asynkront. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Skapar en ny batch av vektorlagerfiler asynkront. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Raderar en befintlig assistent asynkront. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Raderar en specifik fil asynkront. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Raderar en befintlig tråd asynkront. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Raderar ett meddelande i en tråd asynkront. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Raderar ett vektorlager asynkront. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Raderar en fil i ett vektorlager asynkront. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Avslutar resurserna som används av [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Hämtar detaljer för en specifik assistent asynkront. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Hämtar en lista över assistenter asynkront. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Hämtar en instans av [`IChatCopilot`](../ichatcopilot/) med de angivna alternativen. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Hämtar detaljer för en specifik fil asynkront. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Hämtar en lista över filer asynkront baserat på det angivna syftet. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Hämtar en instans av [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) med de angivna alternativen. |
| [GetOcrCopilot](../../aspose.pdf.ai/openaiclient/getocrcopilot/)(IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Hämtar en instans av [`IOcrCopilot`](../iocrcopilot/) med de angivna alternativen. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Hämtar detaljer för en specifik körning i en tråd asynkront. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Hämtar en lista över körningar för en specificerad tråd asynkront. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Hämtar detaljer för ett specifikt steg inom en körning asynkront. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Hämtar en lista med steg för en specifik körning inom en tråd asynkront. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Hämtar en instans av [`ISummaryCopilot`](../isummarycopilot/) med de angivna alternativen. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Hämtar detaljer för en specifik tråd asynkront. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Hämtar detaljer för ett specifikt meddelande inom en tråd asynkront. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Hämtar en lista med meddelanden för en specifik tråd asynkront. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Hämtar detaljer för ett specifikt vektorlager asynkront. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Hämtar detaljer för en specifik fil inom ett vektorlager asynkront. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Hämtar detaljer för en specifik vektorlagerfilbatch asynkront. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Hämtar en lista med filer inom en specifik vektorlagerfilbatch asynkront. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Hämtar en lista med filer inom ett specifikt vektorlager asynkront. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Hämtar en lista med vektorlager asynkront. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifierar en befintlig assistent asynkront. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifierar en befintlig körning inom en tråd asynkront. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifierar en befintlig tråd asynkront. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifierar ett befintligt meddelande inom en tråd asynkront. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifierar ett befintligt vektorlager asynkront. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Kör assistenten med det angivna threadId och runCreateRequest, och hämtar asynkront assistentens svar. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Laddar upp en fil asynkront till OpenAI-servern. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Väntar asynkront på det första meddelandet från assistenten inom en tråd. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Väntar asynkront på att en körning ska slutföras inom en tråd. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Väntar asynkront på att ett specifikt trådmeddelande ska slutföras. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Väntar asynkront på att en specifik vektorlagerfil ska slutföras. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Väntar asynkront på att ett specifikt vektorlager ska slutföras. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Skapar en ny instans av [`Builder`](../openaiclient.builder/) med den angivna API-nyckeln. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Builder-klass för att skapa en instans av `OpenAIClient`. |

### Se även

* class [AIClientBase](../aiclientbase/)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* interface [IOcrClient&lt;TOptions&gt;](../iocrclient-1/)
* class [OpenAIOcrCopilotOptions](../openaiocrcopilotoptions/)
* interface [IOpenAIClient](../iopenaiclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


