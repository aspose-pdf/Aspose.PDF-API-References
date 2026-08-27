---
title: "Gränssnitt IOpenAIClient"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.AI.IOpenAIClient‑gränssnitt. Representerar ett klientgränssnitt för att interagera med OpenAI‑API:t och utökar grundläggande AI‑klientfunktioner."
type: docs
weight: 590
url: /sv/net/aspose.pdf.ai/iopenaiclient/
---
## IOpenAIClient interface

Representerar ett klientgränssnitt för att interagera med OpenAI API, som utökar grundläggande AI-klientfunktioner.

```csharp
public interface IOpenAIClient
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | Avbryter en befintlig körning inom en tråd asynkront. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Avbryter en specifik vektorlagringsfilbatch asynkront. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Skapar en ny assistent asynkront. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Skapar en ny slutförande asynkront. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Skapar en körning inom en specificerad tråd asynkront. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Skapar en tråd och en körning i den asynkront. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Skapar en ny tråd asynkront. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Skapar ett nytt meddelande i en tråd asynkront. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Skapar en ny vektorlager och väntar på att den ska slutföras asynkront. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Skapar en ny vektorlager asynkront. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Skapar en ny vektorlagerfil asynkront. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Skapar en ny batch av vektorlagerfiler asynkront. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | Raderar en befintlig assistent asynkront. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | Raderar en specifik fil asynkront. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | Raderar en befintlig tråd asynkront. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Raderar ett meddelande i en tråd asynkront. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Raderar ett vektorlager asynkront. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Raderar en fil i ett vektorlager asynkront. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | Hämtar detaljer för en specifik assistent asynkront. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Hämtar en lista över assistenter asynkront. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | Hämtar detaljer för en specifik fil asynkront. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | Hämtar en lista över filer asynkront baserat på det angivna syftet. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | Hämtar detaljer för en specifik körning i en tråd asynkront. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Hämtar en lista över körningar för en specificerad tråd asynkront. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Hämtar detaljer för ett specifikt steg inom en körning asynkront. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Hämtar en lista med steg för en specifik körning inom en tråd asynkront. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | Hämtar detaljer för en specifik tråd asynkront. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Hämtar detaljer för ett specifikt meddelande inom en tråd asynkront. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Hämtar en lista med meddelanden för en specifik tråd asynkront. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | Hämtar detaljer för ett specifikt vektorlager asynkront. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Hämtar detaljer för en specifik fil inom ett vektorlager asynkront. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Hämtar detaljer för en specifik vektorlagerfilbatch asynkront. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Hämtar en lista med filer inom en specifik vektorlagerfilbatch asynkront. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Hämtar en lista med filer inom ett specifikt vektorlager asynkront. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Hämtar en lista med vektorlager asynkront. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifierar en befintlig assistent asynkront. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifierar en befintlig körning inom en tråd asynkront. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifierar en befintlig tråd asynkront. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifierar ett befintligt meddelande inom en tråd asynkront. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifierar ett befintligt vektorlager asynkront. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Kör assistenten med det angivna threadId och runCreateRequest, och hämtar asynkront assistentens svar. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Laddar upp en fil asynkront till OpenAI-servern. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Väntar asynkront på det första meddelandet från assistenten inom en tråd. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Väntar asynkront på att en körning ska slutföras inom en tråd. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Väntar asynkront på att ett specifikt trådmeddelande ska slutföras. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Väntar asynkront på att en specifik vektorlagerfil ska slutföras. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Väntar asynkront på att ett specifikt vektorlager ska slutföras. |

### Se även

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


