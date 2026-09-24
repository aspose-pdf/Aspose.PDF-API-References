---
title: "IOpenAIClient Interface"
linktitle: "IOpenAIClient"
articleTitle: "IOpenAIClient"
second_title: "Aspose.PDF for .NET"
description: "Represents a client interface for interacting with the OpenAI API, extending basic AI client functionalities."
type: docs
weight: 590
url: "/net/aspose.pdf.ai/iopenaiclient/"
product_version: "26.9.0"
---
## IOpenAIClient interface

Represents a client interface for interacting with the OpenAI API, extending basic AI client functionalities.

```csharp
public interface IOpenAIClient
```

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
| [DeleteAssistantAsync](./deleteassistantasync/)(*string, Nullable<CancellationToken>*) | Deletes an existing assistant asynchronously. |
| [DeleteFileAsync](./deletefileasync/)(*string, Nullable<CancellationToken>*) | Deletes a specific file asynchronously. |
| [DeleteThreadAsync](./deletethreadasync/)(*string, Nullable<CancellationToken>*) | Deletes an existing thread asynchronously. |
| [DeleteThreadMessageAsync](./deletethreadmessageasync/)(*string, string, Nullable<CancellationToken>*) | Deletes a message within a thread asynchronously. |
| [DeleteVectorStoreAsync](./deletevectorstoreasync/)(*string, Nullable<CancellationToken>*) | Deletes a vector store asynchronously. |
| [DeleteVectorStoreFileAsync](./deletevectorstorefileasync/)(*string, string, Nullable<CancellationToken>*) | Deletes a file within a vector store asynchronously. |
| [GetAssistantAsync](./getassistantasync/)(*string, Nullable<CancellationToken>*) | Retrieves details of a specific assistant asynchronously. |
| [GetAssistantsAsync](./getassistantsasync/)(*AssistantListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of assistants asynchronously. |
| [GetFileAsync](./getfileasync/)(*string, Nullable<CancellationToken>*) | Retrieves details of a specific file asynchronously. |
| [GetFilesAsync](./getfilesasync/)(*string, Nullable<CancellationToken>*) | Retrieves a list of files asynchronously based on the specified purpose. |
| [GetRunAsync](./getrunasync/)(*string, string, Nullable<CancellationToken>*) | Retrieves details of a specific run within a thread asynchronously. |
| [GetRunStepAsync](./getrunstepasync/)(*string, string, string, Nullable<CancellationToken>*) | Retrieves details of a specific step within a run asynchronously. |
| [GetRunStepsAsync](./getrunstepsasync/)(*string, string, RunStepListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of steps for a specific run within a thread asynchronously. |
| [GetRunsAsync](./getrunsasync/)(*string, RunListQueryParameters, Nullable<CancellationToken>*) | Retrieves a list of runs for a specified thread asynchronously. |
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

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

