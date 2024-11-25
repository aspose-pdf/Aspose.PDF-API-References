---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIClient class. Provides methods to interact with the OpenAI API for managing vector store file batches
type: docs
weight: 840
url: /net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

Provides methods to interact with the OpenAI API for managing vector store file batches.

Provides methods to interact with the OpenAI API for managing vector store files.

Provides methods to interact with the OpenAI API for managing vector stores.

Represents a client for interacting with the OpenAI API, extending basic AI client functionalities.

Provides methods to interact with the OpenAI API for managing run steps within threads.

Provides methods to interact with the OpenAI API for managing files.

Provides methods to interact with the OpenAI API for managing thread messages.

Provides methods to interact with the OpenAI API for managing threads.

Provides methods to interact with the OpenAI API for managing assistants.

Provides a method to interact with the OpenAI API for creating completions.

Provides methods to interact with the OpenAI API for managing runs within threads.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Gets or sets the backoff delay in seconds. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Gets or sets the maximum number of HTTP request retries. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Gets or sets the polling interval in seconds. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Gets or sets the polling timeout in seconds. |

## Methods

| Name | Description |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Cancels an existing run within a thread asynchronously. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Cancels a specific vector store file batch asynchronously. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Creates a new assistant asynchronously. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Creates a new completion asynchronously. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Creates a run within a specified thread asynchronously. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Creates a thread and a run within it asynchronously. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Creates a new thread asynchronously. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Creates a new message within a thread asynchronously. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Creates a new vector store and waits for it to complete asynchronously. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Creates a new vector store asynchronously. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Creates a new vector store file asynchronously. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Creates a new vector store file batch asynchronously. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Deletes an existing assistant asynchronously. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Deletes a specific file asynchronously. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Deletes an existing thread asynchronously. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Deletes a message within a thread asynchronously. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Deletes a vector store asynchronously. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Deletes a file within a vector store asynchronously. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Disposes of the resources used by the [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Retrieves details of a specific assistant asynchronously. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Retrieves a list of assistants asynchronously. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Gets an instance of [`IChatCopilot`](../ichatcopilot/) with the specified options. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Retrieves details of a specific file asynchronously. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Retrieves a list of files asynchronously based on the specified purpose. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Gets an instance of [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) with the specified options. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Retrieves details of a specific run within a thread asynchronously. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Retrieves a list of runs for a specified thread asynchronously. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Retrieves details of a specific step within a run asynchronously. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Retrieves a list of steps for a specific run within a thread asynchronously. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Gets an instance of [`ISummaryCopilot`](../isummarycopilot/) with the specified options. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Retrieves details of a specific thread asynchronously. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Retrieves details of a specific message within a thread asynchronously. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Retrieves a list of messages for a specific thread asynchronously. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Retrieves details of a specific vector store asynchronously. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Retrieves details of a specific file within a vector store asynchronously. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Retrieves details of a specific vector store file batch asynchronously. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Retrieves a list of files within a specific vector store file batch asynchronously. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Retrieves a list of files within a specific vector store asynchronously. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Retrieves a list of vector stores asynchronously. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifies an existing assistant asynchronously. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifies an existing run within a thread asynchronously. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifies an existing thread asynchronously. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifies an existing message within a thread asynchronously. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifies an existing vector store asynchronously. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Runs the assistant with the specified threadId and runCreateRequest, and asynchronously gets the assistant response. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Uploads a file asynchronously to the OpenAI server. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Waits for the first message from the assistant within a thread asynchronously. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Waits for a run to complete within a thread asynchronously. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Waits for a specific thread message to complete asynchronously. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Waits for a specific vector store file to complete asynchronously. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Waits for a specific vector store to complete asynchronously. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Creates a new instance of [`Builder`](../openaiclient.builder/) with the provided API key. |

## Other Members

| Name | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Builder class for creating an instance of `OpenAIClient`. |

### See Also

* class [AIClientBase](../aiclientbase/)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* interface [IOpenAIClient](../iopenaiclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


