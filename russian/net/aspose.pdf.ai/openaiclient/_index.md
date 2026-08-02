---
title: "Класс OpenAIClient"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.AI.OpenAIClient. Предоставляет методы для взаимодействия с OpenAI API для управления пакетами файлов векторного хранилища"
type: docs
weight: 900
url: /ru/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

Предоставляет методы для взаимодействия с OpenAI API для управления пакетами файлов векторного хранилища.

Предоставляет методы для взаимодействия с OpenAI API для управления файлами векторного хранилища.

Предоставляет методы для взаимодействия с OpenAI API для управления векторными хранилищами.

Представляет клиент для взаимодействия с OpenAI API, расширяющий базовые функции AI‑клиента.

Предоставляет методы для взаимодействия с OpenAI API для управления шагами выполнения внутри потоков.

Предоставляет методы для взаимодействия с OpenAI API для управления файлами.

Предоставляет методы для взаимодействия с OpenAI API для управления сообщениями потоков.

Предоставляет методы для взаимодействия с OpenAI API для управления потоками.

Предоставляет методы для взаимодействия с OpenAI API для управления помощниками.

Предоставляет метод для взаимодействия с OpenAI API для создания завершений.

Предоставляет методы для взаимодействия с OpenAI API для управления выполнениями внутри потоков.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, 
    IOcrClient<OpenAIOcrCopilotOptions>, IOpenAIClient, ISummaryClient<OpenAISummaryCopilotOptions>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Получает или задает задержку отката в секундах. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Получает или задает максимальное количество повторных попыток HTTP‑запросов. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Получает или задает интервал опроса в секундах. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Получает или задает тайм‑аут опроса в секундах. |

## Методы

| Имя | Описание |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Асинхронно отменяет существующее выполнение внутри потока. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Асинхронно отменяет конкретный пакет файлов векторного хранилища. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Асинхронно создает нового помощника. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Создает новое завершение асинхронно. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Создает запуск в указанном потоке асинхронно. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Создает поток и запуск в нем асинхронно. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Создает новый поток асинхронно. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Создает новое сообщение в потоке асинхронно. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Создает новое хранилище векторов и ожидает его завершения асинхронно. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Создает новое хранилище векторов асинхронно. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Создает новый файл хранилища векторов асинхронно. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Создает новую партию файлов хранилища векторов асинхронно. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Удаляет существующего помощника асинхронно. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Удаляет конкретный файл асинхронно. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Удаляет существующий поток асинхронно. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Удаляет сообщение в потоке асинхронно. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Удаляет хранилище векторов асинхронно. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Удаляет файл в хранилище векторов асинхронно. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Освобождает ресурсы, используемые [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Получает детали конкретного помощника асинхронно. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Получает список помощников асинхронно. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Получает экземпляр [`IChatCopilot`](../ichatcopilot/) с указанными параметрами. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Получает детали конкретного файла асинхронно. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Получает список файлов асинхронно на основе указанной цели. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Получает экземпляр [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) с указанными параметрами. |
| [GetOcrCopilot](../../aspose.pdf.ai/openaiclient/getocrcopilot/)(IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Получает экземпляр [`IOcrCopilot`](../iocrcopilot/) с указанными параметрами. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Получает детали конкретного запуска в потоке асинхронно. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Получает список запусков для указанного потока асинхронно. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Получает детали конкретного шага в запуске асинхронно. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Получает список шагов для конкретного запуска в потоке асинхронно. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Получает экземпляр [`ISummaryCopilot`](../isummarycopilot/) с указанными параметрами. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Получает детали конкретного потока асинхронно. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Получает детали конкретного сообщения в потоке асинхронно. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Получает список сообщений для конкретного потока асинхронно. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Получает детали конкретного векторного хранилища асинхронно. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Получает детали конкретного файла в векторном хранилище асинхронно. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Получает детали конкретной партии файлов векторного хранилища асинхронно. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Получает список файлов в конкретной партии файлов векторного хранилища асинхронно. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Получает список файлов в конкретном векторном хранилище асинхронно. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Получает список векторных хранилищ асинхронно. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Изменяет существующего помощника асинхронно. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Изменяет существующий запуск в потоке асинхронно. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Изменяет существующий поток асинхронно. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Изменяет существующее сообщение в потоке асинхронно. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Изменяет существующее векторное хранилище асинхронно. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Запускает помощника с указанным threadId и runCreateRequest и асинхронно получает ответ помощника. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Асинхронно загружает файл на сервер OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Ожидает первое сообщение от помощника в потоке асинхронно. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Ожидает завершения запуска в потоке асинхронно. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Ожидает завершения конкретного сообщения потока асинхронно. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Ожидает завершения конкретного файла векторного хранилища асинхронно. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Ожидает завершения конкретного векторного хранилища асинхронно. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Создаёт новый экземпляр [`Builder`](../openaiclient.builder/) с предоставленным API‑ключом. |

## Другие члены

| Имя | Описание |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Класс‑строитель для создания экземпляра `OpenAIClient`. |

### См. также

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


