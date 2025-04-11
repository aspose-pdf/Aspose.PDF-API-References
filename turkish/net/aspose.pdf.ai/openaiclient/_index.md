---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIClient sınıfı. Vektör depolama dosya gruplarını yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.
type: docs
weight: 840
url: /tr/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient sınıfı

Vektör depolama dosya gruplarını yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

Vektör depolama dosyalarını yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

Vektör depolama alanlarını yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

OpenAI API'si ile etkileşim kurmak için temel AI istemci işlevselliklerini genişleten bir istemciyi temsil eder.

İş parçaları içinde çalışma adımlarını yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

Dosyaları yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

İş parçaları mesajlarını yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

İş parçalarını yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

Asistanları yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

Tamamlamalar oluşturmak için OpenAI API'si ile etkileşim kurma yöntemi sağlar.

İş parçaları içinde çalışmaları yönetmek için OpenAI API'si ile etkileşim kurma yöntemleri sağlar.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Geri çekilme gecikmesini saniye cinsinden alır veya ayarlar. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | HTTP istekleri için maksimum yeniden deneme sayısını alır veya ayarlar. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Anketleme aralığını saniye cinsinden alır veya ayarlar. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Anketleme zaman aşımını saniye cinsinden alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Bir iş parçacığı içinde mevcut bir çalışmayı asenkron olarak iptal eder. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Belirli bir vektör depolama dosya grubunu asenkron olarak iptal eder. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Yeni bir asistanı asenkron olarak oluşturur. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Yeni bir tamamlamayı asenkron olarak oluşturur. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Belirtilen bir iş parçacığı içinde bir çalışmayı asenkron olarak oluşturur. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Bir iş parçacığı ve içinde bir çalışmayı asenkron olarak oluşturur. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Yeni bir iş parçacığını asenkron olarak oluşturur. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Bir iş parçacığı içinde yeni bir mesajı asenkron olarak oluşturur. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Yeni bir vektör depolama alanı oluşturur ve tamamlanmasını asenkron olarak bekler. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Yeni bir vektör depolama alanı asenkron olarak oluşturur. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Yeni bir vektör depolama dosyasını asenkron olarak oluşturur. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Yeni bir vektör depolama dosya grubunu asenkron olarak oluşturur. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Mevcut bir asistanı asenkron olarak siler. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Belirli bir dosyayı asenkron olarak siler. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Mevcut bir iş parçacığını asenkron olarak siler. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Bir iş parçacığı içinde bir mesajı asenkron olarak siler. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Bir vektör depolama alanını asenkron olarak siler. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | Bir vektör depolama alanı içinde bir dosyayı asenkron olarak siler. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | [`AIClientBase`](../aiclientbase/) tarafından kullanılan kaynakları serbest bırakır. |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Belirli bir asistanın ayrıntılarını asenkron olarak alır. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Asistanların listesini asenkron olarak alır. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Belirtilen seçeneklerle [`IChatCopilot`](../ichatcopilot/) örneğini alır. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Belirli bir dosyanın ayrıntılarını asenkron olarak alır. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Belirtilen amaca göre dosyaların listesini asenkron olarak alır. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Belirtilen seçeneklerle [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) örneğini alır. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Bir iş parçacığı içinde belirli bir çalışmanın ayrıntılarını asenkron olarak alır. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Belirtilen bir iş parçacığı için çalışmanın listesini asenkron olarak alır. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Bir çalışmadaki belirli bir adımın ayrıntılarını asenkron olarak alır. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Bir iş parçacığı içindeki belirli bir çalışmanın adımlarının listesini asenkron olarak alır. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Belirtilen seçeneklerle [`ISummaryCopilot`](../isummarycopilot/) örneğini alır. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Belirli bir iş parçacığının ayrıntılarını asenkron olarak alır. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Bir iş parçacığı içindeki belirli bir mesajın ayrıntılarını asenkron olarak alır. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Belirli bir iş parçacığı için mesajların listesini asenkron olarak alır. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Belirli bir vektör depolama alanının ayrıntılarını asenkron olarak alır. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | Bir vektör depolama alanı içindeki belirli bir dosyanın ayrıntılarını asenkron olarak alır. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Belirli bir vektör depolama dosya grubunun ayrıntılarını asenkron olarak alır. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Belirli bir vektör depolama dosya grubundaki dosyaların listesini asenkron olarak alır. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Belirli bir vektör depolama alanındaki dosyaların listesini asenkron olarak alır. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Vektör depolama alanlarının listesini asenkron olarak alır. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Mevcut bir asistanı asenkron olarak değiştirir. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Bir iş parçacığı içindeki mevcut bir çalışmayı asenkron olarak değiştirir. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Mevcut bir iş parçacığını asenkron olarak değiştirir. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest) | Bir iş parçacığı içindeki mevcut bir mesajı asenkron olarak değiştirir. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Mevcut bir vektör depolama alanını asenkron olarak değiştirir. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Belirtilen threadId ve runCreateRequest ile asistanı çalıştırır ve asenkron olarak asistan yanıtını alır. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Bir dosyayı asenkron olarak OpenAI sunucusuna yükler. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Bir iş parçacığı içinde asistanın ilk mesajını asenkron olarak bekler. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Bir iş parçacığındaki bir çalışmanın tamamlanmasını asenkron olarak bekler. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Belirli bir iş parçacığı mesajının tamamlanmasını asenkron olarak bekler. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Belirli bir vektör depolama dosyasının tamamlanmasını asenkron olarak bekler. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Belirli bir vektör depolama alanının tamamlanmasını asenkron olarak bekler. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Sağlanan API anahtarı ile yeni bir [`Builder`](../openaiclient.builder/) örneği oluşturur. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | `OpenAIClient` örneği oluşturmak için Builder sınıfı. |

### Ayrıca Bakınız

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