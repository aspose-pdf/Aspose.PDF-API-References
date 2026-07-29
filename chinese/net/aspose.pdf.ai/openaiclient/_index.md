---
title: "类 OpenAIClient"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OpenAIClient 类。提供用于管理向量存储文件批次的 OpenAI API 交互方法。"
type: docs
weight: 900
url: /zh/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

提供用于与 OpenAI API 交互以管理向量存储文件批次的方法。

提供用于管理向量存储文件的 OpenAI API 交互方法。

提供用于管理向量存储的 OpenAI API 交互方法。

表示一个用于与 OpenAI API 交互的客户端，扩展了基本 AI 客户端功能。

提供用于管理线程内运行步骤的 OpenAI API 交互方法。

提供用于管理文件的 OpenAI API 交互方法。

提供用于管理线程消息的 OpenAI API 交互方法。

提供用于管理线程的 OpenAI API 交互方法。

提供用于管理助手的 OpenAI API 交互方法。

提供一种方法与 OpenAI API 交互以创建补全。

提供方法与 OpenAI API 交互，以管理线程中的 run。

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, 
    IOcrClient<OpenAIOcrCopilotOptions>, IOpenAIClient, ISummaryClient<OpenAISummaryCopilotOptions>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | 获取或设置以秒为单位的退避延迟。 |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | 获取或设置 HTTP 请求重试的最大次数。 |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | 获取或设置以秒为单位的轮询间隔。 |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | 获取或设置以秒为单位的轮询超时。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | 异步取消线程中现有的 run。 |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | 异步取消特定的向量存储文件批次。 |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | 异步创建新的助手。 |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | 异步创建新的补全。 |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | 异步在指定的线程中创建 run。 |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | 异步创建线程并在其中创建 run。 |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | 异步创建新线程。 |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | 异步在线程中创建新消息。 |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | 异步创建新的向量存储并等待其完成。 |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | 异步创建新的向量存储。 |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | 异步创建新的向量存储文件。 |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | 异步创建新的向量存储文件批次。 |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | 异步删除现有的助手。 |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | 异步删除特定文件。 |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | 异步删除现有线程。 |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | 异步删除线程中的消息。 |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | 异步删除向量存储。 |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | 异步删除向量存储中的文件。 |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | 释放由 [`AIClientBase`](../aiclientbase/) 使用的资源。 |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | 异步检索特定助手的详细信息。 |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | 异步检索助手列表。 |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | 获取具有指定选项的[`IChatCopilot`](../ichatcopilot/)实例。 |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | 异步检索特定文件的详细信息。 |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | 根据指定目的，异步检索文件列表。 |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | 获取具有指定选项的[`IImageDescriptionCopilot`](../iimagedescriptioncopilot/)实例。 |
| [GetOcrCopilot](../../aspose.pdf.ai/openaiclient/getocrcopilot/)(IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | 获取具有指定选项的[`IOcrCopilot`](../iocrcopilot/)实例。 |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | 异步检索线程中特定运行的详细信息。 |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | 异步检索指定线程的运行列表。 |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | 异步检索运行中特定步骤的详细信息。 |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | 异步检索线程中特定运行的步骤列表。 |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | 获取具有指定选项的[`ISummaryCopilot`](../isummarycopilot/)实例。 |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | 异步检索特定线程的详细信息。 |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | 异步检索线程中特定消息的详细信息。 |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 异步检索特定线程的消息列表。 |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | 异步检索特定向量存储的详细信息。 |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | 异步检索向量存储中具体文件的详细信息。 |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | 异步检索特定向量存储文件批次的详细信息。 |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | 异步检索特定向量存储文件批次中的文件列表。 |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | 异步检索特定向量存储中的文件列表。 |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | 异步检索向量存储列表。 |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | 异步修改现有助手。 |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | 异步修改线程中现有的运行。 |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | 异步修改现有线程。 |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | 异步修改线程中现有的消息。 |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | 异步修改现有向量存储。 |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | 使用指定的 threadId 和 runCreateRequest 运行助手，并异步获取助手响应。 |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | 异步将文件上传到 OpenAI 服务器。 |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 异步等待线程中来自助手的第一条消息。 |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | 异步等待线程中运行完成。 |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | 异步等待特定线程消息完成。 |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | 异步等待特定向量存储文件完成。 |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | 异步等待特定向量存储完成。 |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | 使用提供的 API 密钥创建一个新的 [`Builder`](../openaiclient.builder/) 实例。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | 用于创建 `OpenAIClient` 实例的 Builder 类。 |

### 另请参见

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


