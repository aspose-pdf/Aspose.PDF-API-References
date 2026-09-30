---
title: "IOpenAIClient Interface"
linktitle: "IOpenAIClient"
articleTitle: "IOpenAIClient"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.IOpenAIClient interface. Represents a client interface for interacting with the OpenAI API, extending basic AI client functionalities."
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
| [CancelRunAsync](./cancelrunasync/)(string, string, CancellationToken?) | Cancels an existing run within a thread asynchronously. |
| [CancelVectorStoreFileBatchAsync](./cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Cancels a specific vector store file batch asynchronously. |
| [CreateAssistantAsync](./createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Creates a new assistant asynchronously. |
| [CreateCompletionAsync](./createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Creates a new completion asynchronously. |
| [CreateRunAsync](./createrunasync/)(string, RunCreateRequest, CancellationToken?) | Creates a run within a specified thread asynchronously. |
| [CreateThreadAndRunAsync](./createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Creates a thread and a run within it asynchronously. |
| [CreateThreadAsync](./createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Creates a new thread asynchronously. |
| [CreateThreadMessageAsync](./createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Creates a new message within a thread asynchronously. |
| [CreateVectorStoreAndWaitToCompleteAsync](./createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Creates a new vector store and waits for it to complete asynchronously. |
| [CreateVectorStoreAsync](./createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Creates a new vector store asynchronously. |
| [CreateVectorStoreFileAsync](./createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Creates a new vector store file asynchronously. |
| [CreateVectorStoreFileBatchAsync](./createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Creates a new vector store file batch asynchronously. |
| [DeleteAssistantAsync](./deleteassistantasync/)(string, CancellationToken?) | Deletes an existing assistant asynchronously. |
| [DeleteFileAsync](./deletefileasync/)(string, CancellationToken?) | Deletes a specific file asynchronously. |
| [DeleteThreadAsync](./deletethreadasync/)(string, CancellationToken?) | Deletes an existing thread asynchronously. |
| [DeleteThreadMessageAsync](./deletethreadmessageasync/)(string, string, CancellationToken?) | Deletes a message within a thread asynchronously. |
| [DeleteVectorStoreAsync](./deletevectorstoreasync/)(string, CancellationToken?) | Deletes a vector store asynchronously. |
| [DeleteVectorStoreFileAsync](./deletevectorstorefileasync/)(string, string, CancellationToken?) | Deletes a file within a vector store asynchronously. |
| [GetAssistantAsync](./getassistantasync/)(string, CancellationToken?) | Retrieves details of a specific assistant asynchronously. |
| [GetAssistantsAsync](./getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Retrieves a list of assistants asynchronously. |
| [GetFileAsync](./getfileasync/)(string, CancellationToken?) | Retrieves details of a specific file asynchronously. |
| [GetFilesAsync](./getfilesasync/)(string, CancellationToken?) | Retrieves a list of files asynchronously based on the specified purpose. |
| [GetRunAsync](./getrunasync/)(string, string, CancellationToken?) | Retrieves details of a specific run within a thread asynchronously. |
| [GetRunStepAsync](./getrunstepasync/)(string, string, string, CancellationToken?) | Retrieves details of a specific step within a run asynchronously. |
| [GetRunStepsAsync](./getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Retrieves a list of steps for a specific run within a thread asynchronously. |
| [GetRunsAsync](./getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Retrieves a list of runs for a specified thread asynchronously. |
| [GetThreadAsync](./getthreadasync/)(string, CancellationToken?) | Retrieves details of a specific thread asynchronously. |
| [GetThreadMessageAsync](./getthreadmessageasync/)(string, string, CancellationToken?) | Retrieves details of a specific message within a thread asynchronously. |
| [GetThreadMessagesAsync](./getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Retrieves a list of messages for a specific thread asynchronously. |
| [GetVectorStoreAsync](./getvectorstoreasync/)(string, CancellationToken?) | Retrieves details of a specific vector store asynchronously. |
| [GetVectorStoreFileAsync](./getvectorstorefileasync/)(string, string, CancellationToken?) | Retrieves details of a specific file within a vector store asynchronously. |
| [GetVectorStoreFileBatchAsync](./getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Retrieves details of a specific vector store file batch asynchronously. |
| [GetVectorStoreFileBatchFilesAsync](./getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Retrieves a list of files within a specific vector store file batch asynchronously. |
| [GetVectorStoreFilesAsync](./getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Retrieves a list of files within a specific vector store asynchronously. |
| [GetVectorStoresAsync](./getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Retrieves a list of vector stores asynchronously. |
| [ModifyAssistantAsync](./modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifies an existing assistant asynchronously. |
| [ModifyRunAsync](./modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifies an existing run within a thread asynchronously. |
| [ModifyThreadAsync](./modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifies an existing thread asynchronously. |
| [ModifyThreadMessageAsync](./modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifies an existing message within a thread asynchronously. |
| [ModifyVectorStoreAsync](./modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifies an existing vector store asynchronously. |
| [RunAndGetAssistantResponseAsync](./runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Runs the assistant with the specified threadId and runCreateRequest, and asynchronously gets the assistant response. |
| [UploadFileAsync](./uploadfileasync/)(string, string, byte[], CancellationToken?) | Uploads a file asynchronously to the OpenAI server. |
| [WaitForAssistantMessageAsync](./waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Waits for the first message from the assistant within a thread asynchronously. |
| [WaitForRunToCompleteAsync](./waitforruntocompleteasync/)(string, string, CancellationToken?) | Waits for a run to complete within a thread asynchronously. |
| [WaitForThreadMessageToCompleteAsync](./waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Waits for a specific thread message to complete asynchronously. |
| [WaitForVectorStoreFileToCompleteAsync](./waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Waits for a specific vector store file to complete asynchronously. |
| [WaitForVectorStoreToCompleteAsync](./waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Waits for a specific vector store to complete asynchronously. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

