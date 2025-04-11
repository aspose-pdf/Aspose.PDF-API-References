---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.AI.OpenAIClient. Предоставляет методы для взаимодействия с API OpenAI для управления пакетами файлов векторного хранилища
type: docs
weight: 840
url: /ru/net/aspose.pdf.ai/openaiclient/
---
## Класс OpenAIClient

Предоставляет методы для взаимодействия с API OpenAI для управления пакетами файлов векторного хранилища.

Предоставляет методы для взаимодействия с API OpenAI для управления файлами векторного хранилища.

Предоставляет методы для взаимодействия с API OpenAI для управления векторными хранилищами.

Представляет клиента для взаимодействия с API OpenAI, расширяющего основные функции AI клиента.

Предоставляет методы для взаимодействия с API OpenAI для управления шагами выполнения в потоках.

Предоставляет методы для взаимодействия с API OpenAI для управления файлами.

Предоставляет методы для взаимодействия с API OpenAI для управления сообщениями потоков.

Предоставляет методы для взаимодействия с API OpenAI для управления потоками.

Предоставляет методы для взаимодействия с API OpenAI для управления помощниками.

Предоставляет метод для взаимодействия с API OpenAI для создания завершений.

Предоставляет методы для взаимодействия с API OpenAI для управления выполнениями в потоках.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Получает или задает задержку отката в секундах. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Получает или задает максимальное количество повторных попыток HTTP-запросов. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Получает или задает интервал опроса в секундах. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Получает или задает тайм-аут опроса в секундах. |

## Методы

| Имя | Описание |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Асинхронно отменяет существующее выполнение в потоке. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Асинхронно отменяет конкретный пакет файлов векторного хранилища. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Асинхронно создает нового помощника. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Асинхронно создает новое завершение. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Асинхронно создает выполнение в указанном потоке. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Асинхронно создает поток и выполнение в нем. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Асинхронно создает новый поток. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Асинхронно создает новое сообщение в потоке. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Асинхронно создает новое векторное хранилище и ждет его завершения. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Асинхронно создает новое векторное хранилище. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Асинхронно создает новый файл векторного хранилища. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Асинхронно создает новый пакет файлов векторного хранилища. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Асинхронно удаляет существующего помощника. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Асинхронно удаляет конкретный файл. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Асинхронно удаляет существующий поток. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Асинхронно удаляет сообщение в потоке. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Асинхронно удаляет векторное хранилище. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | Асинхронно удаляет файл в векторном хранилище. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Освобождает ресурсы, используемые [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Асинхронно получает детали конкретного помощника. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Асинхронно получает список помощников. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Получает экземпляр [`IChatCopilot`](../ichatcopilot/) с указанными параметрами. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Асинхронно получает детали конкретного файла. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Асинхронно получает список файлов на основе указанной цели. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Получает экземпляр [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) с указанными параметрами. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Асинхронно получает детали конкретного выполнения в потоке. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Асинхронно получает список выполнений для указанного потока. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Асинхронно получает детали конкретного шага в выполнении. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Асинхронно получает список шагов для конкретного выполнения в потоке. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Получает экземпляр [`ISummaryCopilot`](../isummarycopilot/) с указанными параметрами. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Асинхронно получает детали конкретного потока. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Асинхронно получает детали конкретного сообщения в потоке. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Асинхронно получает список сообщений для конкретного потока. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Асинхронно получает детали конкретного векторного хранилища. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | Асинхронно получает детали конкретного файла в векторном хранилище. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Асинхронно получает детали конкретного пакета файлов векторного хранилища. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Асинхронно получает список файлов в конкретном пакете файлов векторного хранилища. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Асинхронно получает список файлов в конкретном векторном хранилище. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Асинхронно получает список векторных хранилищ. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Асинхронно изменяет существующего помощника. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Асинхронно изменяет существующее выполнение в потоке. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Асинхронно изменяет существующий поток. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Асинхронно изменяет существующее сообщение в потоке. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Асинхронно изменяет существующее векторное хранилище. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Запускает помощника с указанным threadId и runCreateRequest и асинхронно получает ответ помощника. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Асинхронно загружает файл на сервер OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Асинхронно ждет первого сообщения от помощника в потоке. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Асинхронно ждет завершения выполнения в потоке. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Асинхронно ждет завершения конкретного сообщения потока. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Асинхронно ждет завершения конкретного файла векторного хранилища. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Асинхронно ждет завершения конкретного векторного хранилища. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Создает новый экземпляр [`Builder`](../openaiclient.builder/) с предоставленным API ключом. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Класс Builder для создания экземпляра `OpenAIClient`. |

### См. также

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