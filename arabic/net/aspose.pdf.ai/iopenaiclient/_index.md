---
title: Interface IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: واجهة Aspose.Pdf.AI.IOpenAIClient. تمثل واجهة عميل للتفاعل مع واجهة برمجة تطبيقات OpenAI وتوسيع وظائف عميل الذكاء الاصطناعي الأساسية
type: docs
weight: 540
url: /ar/net/aspose.pdf.ai/iopenaiclient/
---
## واجهة IOpenAIClient

تمثل واجهة عميل للتفاعل مع واجهة برمجة تطبيقات OpenAI، وتوسيع وظائف عميل الذكاء الاصطناعي الأساسية.

```csharp
public interface IOpenAIClient
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | يلغي عملية قائمة ضمن خيط بشكل غير متزامن. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | يلغي دفعة ملف مخزن المتجهات المحددة بشكل غير متزامن. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | ينشئ مساعدًا جديدًا بشكل غير متزامن. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | ينشئ إكمالًا جديدًا بشكل غير متزامن. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | ينشئ عملية ضمن خيط محدد بشكل غير متزامن. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | ينشئ خيطًا وعملية ضمنه بشكل غير متزامن. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | ينشئ خيطًا جديدًا بشكل غير متزامن. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | ينشئ رسالة جديدة ضمن خيط بشكل غير متزامن. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | ينشئ مخزن متجهات جديد وينتظر حتى يكتمل بشكل غير متزامن. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | ينشئ مخزن متجهات جديد بشكل غير متزامن. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | ينشئ ملف مخزن متجهات جديد بشكل غير متزامن. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | ينشئ دفعة ملف مخزن متجهات جديدة بشكل غير متزامن. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | يحذف مساعدًا موجودًا بشكل غير متزامن. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | يحذف ملفًا محددًا بشكل غير متزامن. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | يحذف خيطًا موجودًا بشكل غير متزامن. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | يحذف رسالة ضمن خيط بشكل غير متزامن. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | يحذف مخزن متجهات بشكل غير متزامن. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | يحذف ملفًا ضمن مخزن متجهات بشكل غير متزامن. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | يسترجع تفاصيل مساعد محدد بشكل غير متزامن. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | يسترجع قائمة بالمساعدين بشكل غير متزامن. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | يسترجع تفاصيل ملف محدد بشكل غير متزامن. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | يسترجع قائمة بالملفات بشكل غير متزامن بناءً على الغرض المحدد. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | يسترجع تفاصيل عملية محددة ضمن خيط بشكل غير متزامن. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | يسترجع قائمة بالعمليات لخيط محدد بشكل غير متزامن. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | يسترجع تفاصيل خطوة محددة ضمن عملية بشكل غير متزامن. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | يسترجع قائمة بالخطوات لعملية محددة ضمن خيط بشكل غير متزامن. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | يسترجع تفاصيل خيط محدد بشكل غير متزامن. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | يسترجع تفاصيل رسالة محددة ضمن خيط بشكل غير متزامن. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | يسترجع قائمة بالرسائل لخيط محدد بشكل غير متزامن. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | يسترجع تفاصيل مخزن متجهات محدد بشكل غير متزامن. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | يسترجع تفاصيل ملف محدد ضمن مخزن متجهات بشكل غير متزامن. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | يسترجع تفاصيل دفعة ملف مخزن متجهات محددة بشكل غير متزامن. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | يسترجع قائمة بالملفات ضمن دفعة ملف مخزن متجهات محددة بشكل غير متزامن. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | يسترجع قائمة بالملفات ضمن مخزن متجهات محدد بشكل غير متزامن. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | يسترجع قائمة بمخازن المتجهات بشكل غير متزامن. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | يعدل مساعدًا موجودًا بشكل غير متزامن. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | يعدل عملية موجودة ضمن خيط بشكل غير متزامن. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | يعدل خيطًا موجودًا بشكل غير متزامن. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | يعدل رسالة موجودة ضمن خيط بشكل غير متزامن. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | يعدل مخزن متجهات موجود بشكل غير متزامن. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | يشغل المساعد مع threadId المحدد وrunCreateRequest، ويحصل بشكل غير متزامن على استجابة المساعد. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | يرفع ملفًا بشكل غير متزامن إلى خادم OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | ينتظر أول رسالة من المساعد ضمن خيط بشكل غير متزامن. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | ينتظر حتى تكتمل عملية ضمن خيط بشكل غير متزامن. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string) | ينتظر حتى تكتمل رسالة خيط محددة بشكل غير متزامن. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | ينتظر حتى يكتمل ملف مخزن متجهات محدد بشكل غير متزامن. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | ينتظر حتى يكتمل مخزن متجهات محدد بشكل غير متزامن. |

### انظر أيضًا

* مساحة الاسم [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* التجميع [Aspose.PDF](../../)