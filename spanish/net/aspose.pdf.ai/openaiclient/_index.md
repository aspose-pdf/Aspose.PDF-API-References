---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.AI.OpenAIClient. Proporciona métodos para interactuar con la API de OpenAI para gestionar lotes de archivos de almacenamiento vectorial
type: docs
weight: 840
url: /es/net/aspose.pdf.ai/openaiclient/
---
## Clase OpenAIClient

Proporciona métodos para interactuar con la API de OpenAI para gestionar lotes de archivos de almacenamiento vectorial.

Proporciona métodos para interactuar con la API de OpenAI para gestionar archivos de almacenamiento vectorial.

Proporciona métodos para interactuar con la API de OpenAI para gestionar almacenes vectoriales.

Representa un cliente para interactuar con la API de OpenAI, extendiendo las funcionalidades básicas del cliente de IA.

Proporciona métodos para interactuar con la API de OpenAI para gestionar pasos de ejecución dentro de hilos.

Proporciona métodos para interactuar con la API de OpenAI para gestionar archivos.

Proporciona métodos para interactuar con la API de OpenAI para gestionar mensajes de hilo.

Proporciona métodos para interactuar con la API de OpenAI para gestionar hilos.

Proporciona métodos para interactuar con la API de OpenAI para gestionar asistentes.

Proporciona un método para interactuar con la API de OpenAI para crear completaciones.

Proporciona métodos para interactuar con la API de OpenAI para gestionar ejecuciones dentro de hilos.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Obtiene o establece el retraso de retroceso en segundos. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Obtiene o establece el número máximo de reintentos de solicitudes HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Obtiene o establece el intervalo de sondeo en segundos. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Obtiene o establece el tiempo de espera de sondeo en segundos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Cancela una ejecución existente dentro de un hilo de forma asíncrona. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Cancela un lote de archivos de almacenamiento vectorial específico de forma asíncrona. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Crea un nuevo asistente de forma asíncrona. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Crea una nueva completación de forma asíncrona. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Crea una ejecución dentro de un hilo especificado de forma asíncrona. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Crea un hilo y una ejecución dentro de él de forma asíncrona. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Crea un nuevo hilo de forma asíncrona. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Crea un nuevo mensaje dentro de un hilo de forma asíncrona. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Crea un nuevo almacén vectorial y espera a que se complete de forma asíncrona. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Crea un nuevo almacén vectorial de forma asíncrona. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Crea un nuevo archivo de almacenamiento vectorial de forma asíncrona. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Crea un nuevo lote de archivos de almacenamiento vectorial de forma asíncrona. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Elimina un asistente existente de forma asíncrona. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Elimina un archivo específico de forma asíncrona. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Elimina un hilo existente de forma asíncrona. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Elimina un mensaje dentro de un hilo de forma asíncrona. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Elimina un almacén vectorial de forma asíncrona. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | Elimina un archivo dentro de un almacén vectorial de forma asíncrona. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Libera los recursos utilizados por el [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Recupera detalles de un asistente específico de forma asíncrona. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Recupera una lista de asistentes de forma asíncrona. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Obtiene una instancia de [`IChatCopilot`](../ichatcopilot/) con las opciones especificadas. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Recupera detalles de un archivo específico de forma asíncrona. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Recupera una lista de archivos de forma asíncrona según el propósito especificado. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Obtiene una instancia de [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) con las opciones especificadas. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Recupera detalles de una ejecución específica dentro de un hilo de forma asíncrona. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Recupera una lista de ejecuciones para un hilo especificado de forma asíncrona. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Recupera detalles de un paso específico dentro de una ejecución de forma asíncrona. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Recupera una lista de pasos para una ejecución específica dentro de un hilo de forma asíncrona. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Obtiene una instancia de [`ISummaryCopilot`](../isummarycopilot/) con las opciones especificadas. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Recupera detalles de un hilo específico de forma asíncrona. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Recupera detalles de un mensaje específico dentro de un hilo de forma asíncrona. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Recupera una lista de mensajes para un hilo específico de forma asíncrona. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Recupera detalles de un almacén vectorial específico de forma asíncrona. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | Recupera detalles de un archivo específico dentro de un almacén vectorial de forma asíncrona. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Recupera detalles de un lote de archivos de almacenamiento vectorial específico de forma asíncrona. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Recupera una lista de archivos dentro de un lote de archivos de almacenamiento vectorial específico de forma asíncrona. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Recupera una lista de archivos dentro de un almacén vectorial específico de forma asíncrona. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Recupera una lista de almacenes vectoriales de forma asíncrona. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifica un asistente existente de forma asíncrona. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifica una ejecución existente dentro de un hilo de forma asíncrona. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest) | Modifica un hilo existente de forma asíncrona. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifica un mensaje existente dentro de un hilo de forma asíncrona. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifica un almacén vectorial existente de forma asíncrona. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Ejecuta el asistente con el threadId especificado y runCreateRequest, y obtiene de forma asíncrona la respuesta del asistente. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Sube un archivo de forma asíncrona al servidor de OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Espera el primer mensaje del asistente dentro de un hilo de forma asíncrona. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Espera a que una ejecución se complete dentro de un hilo de forma asíncrona. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Espera a que un mensaje específico de hilo se complete de forma asíncrona. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Espera a que un archivo específico de almacenamiento vectorial se complete de forma asíncrona. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Espera a que un almacén vectorial específico se complete de forma asíncrona. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Crea una nueva instancia de [`Builder`](../openaiclient.builder/) con la clave API proporcionada. |

## Otros Miembros

| Nombre | Descripción |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Clase Builder para crear una instancia de `OpenAIClient`. |

### Ver También

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