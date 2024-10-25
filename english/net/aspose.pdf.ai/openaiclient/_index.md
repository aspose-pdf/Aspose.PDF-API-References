---
title: OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: 
type: docs
weight: 840
url: /net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds) { get; set; } |  |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries) { get; set; } |  |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds) { get; set; } |  |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds) { get; set; } |  |

## Methods

| Name | Description |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync)(string, string, CancellationToken?) |  |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync)(string, string, CancellationToken?) |  |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync)(AssistantCreateRequest, CancellationToken?) |  |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync)(CompletionCreateRequest, CancellationToken?) |  |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync)(string, RunCreateRequest, CancellationToken?) |  |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync)(RunThreadCreateRequest, CancellationToken?) |  |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync)(ThreadCreateRequest, CancellationToken?) |  |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync)(string, ThreadMessageCreateRequest, CancellationToken?) |  |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync)(VectorStoreCreateRequest, CancellationToken?) |  |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync)(VectorStoreCreateRequest, CancellationToken?) |  |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync)(string, VectorStoreFileCreateRequest, CancellationToken?) |  |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) |  |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync)(string, CancellationToken?) |  |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync)(string, CancellationToken?) |  |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync)(string, CancellationToken?) |  |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync)(string, string, CancellationToken?) |  |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync)(string, CancellationToken?) |  |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync)(string, string, CancellationToken?) |  |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose)() |  |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync)(string, CancellationToken?) |  |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync)(AssistantListQueryParameters, CancellationToken?) |  |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) |  |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync)(string, CancellationToken?) |  |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync)(string, CancellationToken?) |  |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) |  |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync)(string, string, CancellationToken?) |  |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync)(string, RunListQueryParameters, CancellationToken?) |  |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync)(string, string, string, CancellationToken?) |  |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync)(string, string, RunStepListQueryParameters, CancellationToken?) |  |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) |  |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync)(string, CancellationToken?) |  |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync)(string, string, CancellationToken?) |  |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync)(string, ThreadMessageListQueryParameters, CancellationToken?) |  |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync)(string, CancellationToken?) |  |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync)(string, string, CancellationToken?) |  |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync)(string, string, CancellationToken?) |  |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) |  |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync)(string, VectorStoreFileListQueryParameters, CancellationToken?) |  |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync)(VectorStoreListQueryParameters, CancellationToken?) |  |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync)(string, AssistantModifyRequest, CancellationToken?) |  |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync)(string, string, RunModifyRequest, CancellationToken?) |  |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync)(string, ThreadModifyRequest, CancellationToken?) |  |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync)(string, string, ThreadMessageModifyRequest, CancellationToken?) |  |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync)(string, VectorStoreModifyRequest, CancellationToken?) |  |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync)(string, RunCreateRequest, CancellationToken?) |  |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync)(string, string, byte[], CancellationToken?) |  |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync)(string, ThreadMessageListQueryParameters, CancellationToken?) |  |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync)(string, string, CancellationToken?) |  |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync)(string, string, CancellationToken?) |  |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync)(string, string, CancellationToken?) |  |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync)(string, CancellationToken?) |  |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey)(string) |  |

## Other Members

| Name | Description |
| --- | --- |
| class [Builder](openaiclient.builder) |  |

### See Also

* class [AIClientBase](../aiclientbase)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions)
* interface [IOpenAIClient](../iopenaiclient)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
