---
title: IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: 
type: docs
weight: 540
url: /net/aspose.pdf.ai/iopenaiclient/
---
## IOpenAIClient interface

```csharp
public interface IOpenAIClient
```

## Methods

| Name | Description |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync)(string, string, CancellationToken?) |  |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync)(string, string, CancellationToken?) |  |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync)(AssistantCreateRequest, CancellationToken?) |  |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync)(CompletionCreateRequest, CancellationToken?) |  |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync)(string, RunCreateRequest, CancellationToken?) |  |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync)(RunThreadCreateRequest, CancellationToken?) |  |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync)(ThreadCreateRequest, CancellationToken?) |  |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync)(string, ThreadMessageCreateRequest, CancellationToken?) |  |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync)(VectorStoreCreateRequest, CancellationToken?) |  |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync)(VectorStoreCreateRequest, CancellationToken?) |  |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync)(string, VectorStoreFileCreateRequest, CancellationToken?) |  |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) |  |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync)(string, CancellationToken?) |  |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync)(string, CancellationToken?) |  |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync)(string, CancellationToken?) |  |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync)(string, string, CancellationToken?) |  |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync)(string, CancellationToken?) |  |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync)(string, string, CancellationToken?) |  |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync)(string, CancellationToken?) |  |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync)(AssistantListQueryParameters, CancellationToken?) |  |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync)(string, CancellationToken?) |  |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync)(string, CancellationToken?) |  |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync)(string, string, CancellationToken?) |  |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync)(string, RunListQueryParameters, CancellationToken?) |  |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync)(string, string, string, CancellationToken?) |  |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync)(string, string, RunStepListQueryParameters, CancellationToken?) |  |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync)(string, CancellationToken?) |  |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync)(string, string, CancellationToken?) |  |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync)(string, ThreadMessageListQueryParameters, CancellationToken?) |  |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync)(string, CancellationToken?) |  |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync)(string, string, CancellationToken?) |  |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync)(string, string, CancellationToken?) |  |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) |  |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync)(string, VectorStoreFileListQueryParameters, CancellationToken?) |  |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync)(VectorStoreListQueryParameters, CancellationToken?) |  |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync)(string, AssistantModifyRequest, CancellationToken?) |  |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync)(string, string, RunModifyRequest, CancellationToken?) |  |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync)(string, ThreadModifyRequest, CancellationToken?) |  |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync)(string, string, ThreadMessageModifyRequest, CancellationToken?) |  |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync)(string, VectorStoreModifyRequest, CancellationToken?) |  |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync)(string, RunCreateRequest, CancellationToken?) |  |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync)(string, string, byte[], CancellationToken?) |  |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync)(string, ThreadMessageListQueryParameters, CancellationToken?) |  |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync)(string, string, CancellationToken?) |  |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync)(string, string, CancellationToken?) |  |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync)(string, string, CancellationToken?) |  |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync)(string, CancellationToken?) |  |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
