---
title: Interface IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IOpenAIClient arayüzü. OpenAI API'si ile etkileşimde bulunmak için bir istemci arayüzünü temsil eder ve temel AI istemci işlevselliklerini genişletir.
type: docs
weight: 540
url: /tr/net/aspose.pdf.ai/iopenaiclient/
---
## IOpenAIClient arayüzü

OpenAI API'si ile etkileşimde bulunmak için bir istemci arayüzünü temsil eder, temel AI istemci işlevselliklerini genişletir.

```csharp
public interface IOpenAIClient
```

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | Bir iş parçacığı içinde mevcut bir çalışmayı asenkron olarak iptal eder. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Belirli bir vektör depolama dosyası grubunu asenkron olarak iptal eder. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Yeni bir asistanı asenkron olarak oluşturur. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Yeni bir tamamlamayı asenkron olarak oluşturur. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Belirtilen bir iş parçacığı içinde bir çalışmayı asenkron olarak oluşturur. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Bir iş parçacığı ve içinde bir çalışmayı asenkron olarak oluşturur. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Yeni bir iş parçacığını asenkron olarak oluşturur. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Bir iş parçacığı içinde yeni bir mesajı asenkron olarak oluşturur. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Yeni bir vektör deposu oluşturur ve tamamlanmasını asenkron olarak bekler. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Yeni bir vektör deposunu asenkron olarak oluşturur. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Yeni bir vektör depolama dosyasını asenkron olarak oluşturur. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Yeni bir vektör depolama dosyası grubunu asenkron olarak oluşturur. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | Mevcut bir asistanı asenkron olarak siler. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | Belirli bir dosyayı asenkron olarak siler. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | Mevcut bir iş parçacığını asenkron olarak siler. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Bir iş parçacığı içinde bir mesajı asenkron olarak siler. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Bir vektör deposunu asenkron olarak siler. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Bir vektör deposu içinde bir dosyayı asenkron olarak siler. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | Belirli bir asistanın ayrıntılarını asenkron olarak alır. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Asistanların listesini asenkron olarak alır. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | Belirli bir dosyanın ayrıntılarını asenkron olarak alır. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | Belirtilen amaca dayalı olarak dosyaların listesini asenkron olarak alır. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | Bir iş parçacığı içinde belirli bir çalışmanın ayrıntılarını asenkron olarak alır. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Belirtilen bir iş parçacığı için çalışmalardan oluşan bir listeyi asenkron olarak alır. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Bir çalışmadaki belirli bir adımın ayrıntılarını asenkron olarak alır. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Bir iş parçacığı içindeki belirli bir çalışma için adımların listesini asenkron olarak alır. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | Belirli bir iş parçacığının ayrıntılarını asenkron olarak alır. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string) | Bir iş parçacığı içindeki belirli bir mesajın ayrıntılarını asenkron olarak alır. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Belirli bir iş parçacığı için mesajların listesini asenkron olarak alır. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | Belirli bir vektör deposunun ayrıntılarını asenkron olarak alır. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Bir vektör deposu içindeki belirli bir dosyanın ayrıntılarını asenkron olarak alır. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Belirli bir vektör depolama dosyası grubunun ayrıntılarını asenkron olarak alır. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Belirli bir vektör depolama dosyası grubundaki dosyaların listesini asenkron olarak alır. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Belirli bir vektör deposundaki dosyaların listesini asenkron olarak alır. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Vektör depolarının listesini asenkron olarak alır. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Mevcut bir asistanı asenkron olarak değiştirir. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Bir iş parçacığı içindeki mevcut bir çalışmayı asenkron olarak değiştirir. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Mevcut bir iş parçacığını asenkron olarak değiştirir. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Bir iş parçacığı içindeki mevcut bir mesajı asenkron olarak değiştirir. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Mevcut bir vektör deposunu asenkron olarak değiştirir. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Belirtilen threadId ve runCreateRequest ile asistanı çalıştırır ve asenkron olarak asistan yanıtını alır. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Bir dosyayı asenkron olarak OpenAI sunucusuna yükler. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Bir iş parçacığı içinde asistanın ilk mesajını asenkron olarak bekler. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Bir iş parçacığı içinde bir çalışmanın tamamlanmasını asenkron olarak bekler. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Belirli bir iş parçacığı mesajının tamamlanmasını asenkron olarak bekler. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Belirli bir vektör depolama dosyasının tamamlanmasını asenkron olarak bekler. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Belirli bir vektör deposunun tamamlanmasını asenkron olarak bekler. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)