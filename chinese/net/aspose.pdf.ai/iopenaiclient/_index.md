---
title: "接口 IOpenAIClient"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.IOpenAIClient 接口。表示用于与 OpenAI API 交互的客户端接口，扩展了基本 AI 客户端功能。"
type: docs
weight: 590
url: /zh/net/aspose.pdf.ai/iopenaiclient/
---
## IOpenAIClient interface

表示用于与 OpenAI API 交互的客户端接口，扩展了基本 AI 客户端功能。

```csharp
public interface IOpenAIClient
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | 异步取消线程中现有的 run。 |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | 异步取消特定的向量存储文件批次。 |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | 异步创建新的助手。 |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | 异步创建新的补全。 |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | 异步在指定的线程中创建 run。 |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | 异步创建线程并在其中创建 run。 |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | 异步创建新线程。 |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | 异步在线程中创建新消息。 |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | 异步创建新的向量存储并等待其完成。 |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | 异步创建新的向量存储。 |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | 异步创建新的向量存储文件。 |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | 异步创建新的向量存储文件批次。 |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | 异步删除现有的助手。 |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | 异步删除特定文件。 |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | 异步删除现有线程。 |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | 异步删除线程中的消息。 |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | 异步删除向量存储。 |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | 异步删除向量存储中的文件。 |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | 异步检索特定助手的详细信息。 |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | 异步检索助手列表。 |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | 异步检索特定文件的详细信息。 |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | 根据指定目的，异步检索文件列表。 |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | 异步检索线程中特定运行的详细信息。 |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | 异步检索指定线程的运行列表。 |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | 异步检索运行中特定步骤的详细信息。 |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | 异步检索线程中特定运行的步骤列表。 |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | 异步检索特定线程的详细信息。 |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | 异步检索线程中特定消息的详细信息。 |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 异步检索特定线程的消息列表。 |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | 异步检索特定向量存储的详细信息。 |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | 异步检索向量存储中具体文件的详细信息。 |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | 异步检索特定向量存储文件批次的详细信息。 |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | 异步检索特定向量存储文件批次中的文件列表。 |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | 异步检索特定向量存储中的文件列表。 |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | 异步检索向量存储列表。 |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | 异步修改现有助手。 |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | 异步修改线程中现有的运行。 |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | 异步修改现有线程。 |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | 异步修改线程中现有的消息。 |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | 异步修改现有向量存储。 |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | 使用指定的 threadId 和 runCreateRequest 运行助手，并异步获取助手响应。 |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | 异步将文件上传到 OpenAI 服务器。 |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 异步等待线程中来自助手的第一条消息。 |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | 异步等待线程中运行完成。 |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | 异步等待特定线程消息完成。 |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | 异步等待特定向量存储文件完成。 |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | 异步等待特定向量存储完成。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


