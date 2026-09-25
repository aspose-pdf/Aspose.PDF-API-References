---
title: "OpenAIClient Class"
linktitle: "OpenAIClient"
articleTitle: "OpenAIClient"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OpenAIClient class. Provides methods to interact with the OpenAI API for managing vector store file batches."
type: docs
weight: 900
url: "/net/aspose.pdf.ai/openaiclient/"
keywords: "OpenAIClient, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OpenAIClient class

Provides methods to interact with the OpenAI API for managing vector store file batches.

```csharp
public class OpenAIClient : AIClientBase, IOpenAIClient, IAIClient
```

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Gets or sets the backoff delay in seconds. *(Inherited from AIClientBase)* |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Gets or sets the maximum number of HTTP request retries. *(Inherited from AIClientBase)* |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Gets or sets the polling interval in seconds. *(Inherited from AIClientBase)* |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Gets or sets the polling timeout in seconds. *(Inherited from AIClientBase)* |

## Methods

| Name | Description |
| --- | --- |
| [CancelRunAsync](./cancelrunasync/)(*string, string, Nullable<CancellationToken>*) | Cancels an existing run within a thread asynchronously. |
| [CancelVectorStoreFileBatchAsync](./cancelvectorstorefilebatchasync/)(*string, string, Nullable<CancellationToken>*) | Cancels a specific vector store file batch asynchronously. |
| [CreateAssistantAsync](./createassistantasync/)(*AssistantCreateRequest, Nullable<CancellationToken>*) | Creates a new assistant asynchronously. |
| [CreateCompletionAsync](./createcompletionasync/)(*CompletionCreateRequest, Nullable<CancellationToken>*) | Creates a new completion asynchronously. |
| [CreateRunAsync](./createrunasync/)(*string, RunCreateRequest, Nullable<CancellationToken>*) | Creates a run within a specified thread asynchronously. |
| [CreateThreadAndRunAsync](./createthreadandrunasync/)(*RunThreadCreateRequest, Nullable<CancellationToken>*) | Creates a thread and a run within it asynchronously. |
| [CreateThreadAsync](./createthreadasync/)(*ThreadCreateRequest, Nullable<CancellationToken>*) | Creates a new thread asynchronously. |
| [CreateThreadMessageAsync](./createthreadmessageasync/)(*string, ThreadMessageCreateRequest, Nullable<CancellationToken>*) | Creates a new message within a thread asynchronously. |
| [CreateVectorStoreAndWaitToCompleteAsync](./createvectorstoreandwaittocompleteasync/)(*VectorStoreCreateRequest, Nullable<CancellationToken>*) | Creates a new vector store and waits for it to complete asynchronously. |
| [CreateVectorStoreAsync](./createvectorstoreasync/)(*VectorStoreCreateRequest, Nullable<CancellationToken>*) | Creates a new vector store asynchronously. |
| [CreateVectorStoreFileAsync](./createvectorstorefileasync/)(*string, VectorStoreFileCreateRequest, Nullable<CancellationToken>*) | Creates a new vector store file asynchronously. |
| [CreateVectorStoreFileBatchAsync](./createvectorstorefilebatchasync/)(*string, VectorStoreFileBatchCreateRequest, Nullable<CancellationToken>*) | Creates a new vector store file batch asynchronously. |
| [CreateWithApiKey](./createwithapikey/)(*string*) | Creates a new instance of `Builder` with the provided API key. |
| [DeleteAssistantAsync](./deleteassistantasync/)(*string, Nullable<CancellationToken>*) | Deletes an existing assistant asynchronously. |
| [DeleteFileAsync](./deletefileasync/)(*string, Nullable<CancellationToken>*) | Deletes a specific file asynchronously. |
| [DeleteThreadAsync](./deletethreadasync/)(*string, Nullable<CancellationToken>*) | Deletes an existing thread asynchronously. |
| [DeleteThreadMessageAsync](./deletethreadmessageasync/)(*string, string, Nullable<CancellationToken>*) | Deletes a message within a thread asynchronously. |
| [DeleteVectorStoreAsync](./deletevectorstoreasync/)(*string, Nullable<CancellationToken>*) | Deletes a vector store asynchronously. |
| [DeleteVectorStoreFileAsync](./deletevectorstorefileasync/)(*string, string, Nullable<CancellationToken>*) | Deletes a file within a vector store asynchronously. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/) | Disposes of the resources used by the [`AIClientBase`](../../aspose.pdf.ai/aiclientbase/). *(Inherited from AIClientBase)* |
| [GetAssistantAsync](./getassistantasync/)(*string, Nullable<CancellationToken>*) | Retrieves details of a specific assistant asynchronously. |
| [GetAssistantsAsync](./getassistantsasync/)(*AssistantListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of assistants asynchronously. |
| [GetChatCopilot](./getchatcopilot/)(*IChatCopilotOptions<OpenAIChatCopilotOptions>*) | Gets an instance of [`IChatCopilot`](../../aspose.pdf.ai/ichatcopilot/) with the specified options. |
| [GetFileAsync](./getfileasync/)(*string, Nullable<CancellationToken>*) | Retrieves details of a specific file asynchronously. |
| [GetFilesAsync](./getfilesasync/)(*string, Nullable<CancellationToken>*) | Retrieves a list of files asynchronously based on the specified purpose. |
| [GetImageDescriptionCopilot](./getimagedescriptioncopilot/)(*IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>*) | Gets an instance of [`IImageDescriptionCopilot`](../../aspose.pdf.ai/iimagedescriptioncopilot/) with the specified options. |
| [GetOcrCopilot](./getocrcopilot/)(*IOcrCopilotOptions<OpenAIOcrCopilotOptions>*) | Gets an instance of [`IOcrCopilot`](../../aspose.pdf.ai/iocrcopilot/) with the specified options. |
| [GetRunAsync](./getrunasync/)(*string, string, Nullable<CancellationToken>*) | Retrieves details of a specific run within a thread asynchronously. |
| [GetRunStepAsync](./getrunstepasync/)(*string, string, string, Nullable<CancellationToken>*) | Retrieves details of a specific step within a run asynchronously. |
| [GetRunStepsAsync](./getrunstepsasync/)(*string, string, RunStepListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of steps for a specific run within a thread asynchronously. |
| [GetRunsAsync](./getrunsasync/)(*string, RunListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of runs for a specified thread asynchronously. |
| [GetSummaryCopilot](./getsummarycopilot/)(*ISummaryCopilotOptions<OpenAISummaryCopilotOptions>*) | Gets an instance of [`ISummaryCopilot`](../../aspose.pdf.ai/isummarycopilot/) with the specified options. |
| [GetThreadAsync](./getthreadasync/)(*string, Nullable<CancellationToken>*) | Retrieves details of a specific thread asynchronously. |
| [GetThreadMessageAsync](./getthreadmessageasync/)(*string, string, Nullable<CancellationToken>*) | Retrieves details of a specific message within a thread asynchronously. |
| [GetThreadMessagesAsync](./getthreadmessagesasync/)(*string, ThreadMessageListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of messages for a specific thread asynchronously. |
| [GetVectorStoreAsync](./getvectorstoreasync/)(*string, Nullable<CancellationToken>*) | Retrieves details of a specific vector store asynchronously. |
| [GetVectorStoreFileAsync](./getvectorstorefileasync/)(*string, string, Nullable<CancellationToken>*) | Retrieves details of a specific file within a vector store asynchronously. |
| [GetVectorStoreFileBatchAsync](./getvectorstorefilebatchasync/)(*string, string, Nullable<CancellationToken>*) | Retrieves details of a specific vector store file batch asynchronously. |
| [GetVectorStoreFileBatchFilesAsync](./getvectorstorefilebatchfilesasync/)(*string, string, VectorStoreFileBatchFileListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of files within a specific vector store file batch asynchronously. |
| [GetVectorStoreFilesAsync](./getvectorstorefilesasync/)(*string, VectorStoreFileListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of files within a specific vector store asynchronously. |
| [GetVectorStoresAsync](./getvectorstoresasync/)(*VectorStoreListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of vector stores asynchronously. |
| [ModifyAssistantAsync](./modifyassistantasync/)(*string, AssistantModifyRequest, Nullable<CancellationToken>*) | Modifies an existing assistant asynchronously. |
| [ModifyRunAsync](./modifyrunasync/)(*string, string, RunModifyRequest, Nullable<CancellationToken>*) | Modifies an existing run within a thread asynchronously. |
| [ModifyThreadAsync](./modifythreadasync/)(*string, ThreadModifyRequest, Nullable<CancellationToken>*) | Modifies an existing thread asynchronously. |
| [ModifyThreadMessageAsync](./modifythreadmessageasync/)(*string, string, ThreadMessageModifyRequest, Nullable<CancellationToken>*) | Modifies an existing message within a thread asynchronously. |
| [ModifyVectorStoreAsync](./modifyvectorstoreasync/)(*string, VectorStoreModifyRequest, Nullable<CancellationToken>*) | Modifies an existing vector store asynchronously. |
| [RunAndGetAssistantResponseAsync](./runandgetassistantresponseasync/)(*string, RunCreateRequest, Nullable<CancellationToken>*) | Runs the assistant with the specified threadId and runCreateRequest, and asynchronously gets the assistant response. |
| [UploadFileAsync](./uploadfileasync/)(*string, string, byte[], Nullable<CancellationToken>*) | Uploads a file asynchronously to the OpenAI server. |
| [WaitForAssistantMessageAsync](./waitforassistantmessageasync/)(*string, ThreadMessageListQueryParameters, Nullable<CancellationToken>*) | Waits for the first message from the assistant within a thread asynchronously. |
| [WaitForRunToCompleteAsync](./waitforruntocompleteasync/)(*string, string, Nullable<CancellationToken>*) | Waits for a run to complete within a thread asynchronously. |
| [WaitForThreadMessageToCompleteAsync](./waitforthreadmessagetocompleteasync/)(*string, string, Nullable<CancellationToken>*) | Waits for a specific thread message to complete asynchronously. |
| [WaitForVectorStoreFileToCompleteAsync](./waitforvectorstorefiletocompleteasync/)(*string, string, Nullable<CancellationToken>*) | Waits for a specific vector store file to complete asynchronously. |
| [WaitForVectorStoreToCompleteAsync](./waitforvectorstoretocompleteasync/)(*string, Nullable<CancellationToken>*) | Waits for a specific vector store to complete asynchronously. |

### See Also

* class [AIClientBase](../aiclientbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

