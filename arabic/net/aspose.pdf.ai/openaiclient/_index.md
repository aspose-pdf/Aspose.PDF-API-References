---
title: "الفئة OpenAIClient"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.AI.OpenAIClient. توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة دفعات ملفات مخزن المتجهات"
type: docs
weight: 900
url: /ar/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

يوفر طرقًا للتفاعل مع OpenAI API لإدارة دفعات ملفات مخزن المتجهات.

توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة ملفات مخزن المتجهات.

توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة مخازن المتجهات.

يمثل عميلًا للتفاعل مع واجهة برمجة تطبيقات OpenAI، مع توسيع وظائف العميل الأساسي للذكاء الاصطناعي.

توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة خطوات التشغيل داخل الخيوط.

توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة الملفات.

توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة رسائل الخيط.

توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة الخيوط.

توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة المساعدين.

توفر طريقة للتفاعل مع واجهة برمجة تطبيقات OpenAI لإنشاء الإكمالات.

توفر طرقًا للتفاعل مع واجهة برمجة تطبيقات OpenAI لإدارة عمليات التشغيل داخل الخيوط.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, 
    IOcrClient<OpenAIOcrCopilotOptions>, IOpenAIClient, ISummaryClient<OpenAISummaryCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | يحصل أو يعيّن تأخير التراجع بالثواني. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد محاولات إعادة طلب HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | يحصل أو يعيّن فترة الاستطلاع بالثواني. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | يحصل أو يعيّن مهلة الاستطلاع بالثواني. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | يلغي تشغيلًا موجودًا داخل خيط بشكل غير متزامن. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | يلغي دفعة ملف مخزن المتجهات المحددة بشكل غير متزامن. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | ينشئ مساعدًا جديدًا بشكل غير متزامن. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | ينشئ إكمالًا جديدًا بشكل غير متزامن. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | ينشئ تشغيلًا داخل خيط محدد بشكل غير متزامن. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | ينشئ خيطًا وتشغيلًا داخله بشكل غير متزامن. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | ينشئ خيطًا جديدًا بشكل غير متزامن. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | ينشئ رسالة جديدة داخل خيط بشكل غير متزامن. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | ينشئ مخزنًا متجهًا جديدًا وينتظر إكماله بشكل غير متزامن. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | ينشئ مخزنًا متجهًا جديدًا بشكل غير متزامن. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | ينشئ ملف مخزن متجه جديد بشكل غير متزامن. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | ينشئ دفعة ملفات مخزن متجه جديد بشكل غير متزامن. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | يحذف مساعدًا موجودًا بشكل غير متزامن. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | يحذف ملفًا محددًا بشكل غير متزامن. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | يحذف خيطًا موجودًا بشكل غير متزامن. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | يحذف رسالة داخل خيط بشكل غير متزامن. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | يحذف مخزنًا متجهًا بشكل غير متزامن. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | يحذف ملفًا داخل مخزن متجه بشكل غير متزامن. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | يتخلص من الموارد المستخدمة بواسطة [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | يسترجع تفاصيل مساعد محدد بشكل غير متزامن. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | يسترجع قائمة بالمساعدين بشكل غير متزامن. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | يحصل على نسخة من [`IChatCopilot`](../ichatcopilot/) بالخيارات المحددة. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | يسترجع تفاصيل ملف محدد بشكل غير متزامن. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | يسترجع قائمة بالملفات بشكل غير متزامن بناءً على الغرض المحدد. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | يحصل على نسخة من [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) بالخيارات المحددة. |
| [GetOcrCopilot](../../aspose.pdf.ai/openaiclient/getocrcopilot/)(IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | يحصل على نسخة من [`IOcrCopilot`](../iocrcopilot/) بالخيارات المحددة. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | يسترجع تفاصيل تشغيل محدد داخل خيط بشكل غير متزامن. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | يسترجع قائمة بالتشغيلات لخيط محدد بشكل غير متزامن. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | يسترجع تفاصيل خطوة محددة داخل تشغيل بشكل غير متزامن. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | يسترجع قائمة بالخطوات لتشغيل محدد داخل خيط بشكل غير متزامن. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | يحصل على نسخة من [`ISummaryCopilot`](../isummarycopilot/) مع الخيارات المحددة. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | يسترجع تفاصيل خيط محدد بشكل غير متزامن. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | يسترجع تفاصيل رسالة محددة داخل خيط بشكل غير متزامن. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | يسترجع قائمة بالرسائل لخيط محدد بشكل غير متزامن. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | يسترجع تفاصيل مخزن متجه محدد بشكل غير متزامن. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | يسترجع تفاصيل ملف محدد داخل مخزن متجه بشكل غير متزامن. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | يسترجع تفاصيل دفعة ملفات مخزن المتجه المحددة بشكل غير متزامن. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | يسترجع قائمة بالملفات داخل دفعة ملفات مخزن المتجه المحددة بشكل غير متزامن. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | يسترجع قائمة بالملفات داخل مخزن متجه محدد بشكل غير متزامن. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | يسترجع قائمة بمخازن المتجهات بشكل غير متزامن. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | يعدل مساعدًا موجودًا بشكل غير متزامن. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | يعدل تشغيلًا موجودًا داخل خيط بشكل غير متزامن. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | يعدل خيطًا موجودًا بشكل غير متزامن. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | يعدل رسالة موجودة داخل خيط بشكل غير متزامن. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | يعدل مخزن متجه موجود بشكل غير متزامن. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | يشغّل المساعد باستخدام معرف الخيط المحدد وطلب إنشاء التشغيل، ويحصل بشكل غير متزامن على استجابة المساعد. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | يرفع ملفًا بشكل غير متزامن إلى خادم OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | ينتظر الرسالة الأولى من المساعد داخل خيط بشكل غير متزامن. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | ينتظر إكمال تشغيل داخل خيط بشكل غير متزامن. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | ينتظر إكمال رسالة خيط محددة بشكل غير متزامن. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | ينتظر إكمال ملف مخزن متجه محدد بشكل غير متزامن. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | ينتظر إكمال مخزن متجه محدد بشكل غير متزامن. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | ينشئ نسخة جديدة من [`Builder`](../openaiclient.builder/) باستخدام مفتاح API المقدم. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | فئة الباني لإنشاء نسخة من `OpenAIClient`. |

### انظر أيضًا

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


