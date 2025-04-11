---
title: Interface IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Interfaz Aspose.Pdf.AI.IOpenAIClient. Representa una interfaz de cliente para interactuar con la API de OpenAI, extendiendo las funcionalidades básicas del cliente de IA.
type: docs
weight: 540
url: /es/net/aspose.pdf.ai/iopenaiclient/
---
## Interfaz IOpenAIClient

Representa una interfaz de cliente para interactuar con la API de OpenAI, extendiendo las funcionalidades básicas del cliente de IA.

```csharp
public interface IOpenAIClient
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | Cancela una ejecución existente dentro de un hilo de forma asíncrona. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Cancela un lote de archivos de almacenamiento vectorial específico de forma asíncrona. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Crea un nuevo asistente de forma asíncrona. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Crea una nueva finalización de forma asíncrona. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Crea una ejecución dentro de un hilo especificado de forma asíncrona. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Crea un hilo y una ejecución dentro de él de forma asíncrona. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Crea un nuevo hilo de forma asíncrona. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Crea un nuevo mensaje dentro de un hilo de forma asíncrona. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Crea un nuevo almacenamiento vectorial y espera a que se complete de forma asíncrona. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Crea un nuevo almacenamiento vectorial de forma asíncrona. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Crea un nuevo archivo de almacenamiento vectorial de forma asíncrona. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Crea un nuevo lote de archivos de almacenamiento vectorial de forma asíncrona. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | Elimina un asistente existente de forma asíncrona. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | Elimina un archivo específico de forma asíncrona. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | Elimina un hilo existente de forma asíncrona. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Elimina un mensaje dentro de un hilo de forma asíncrona. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Elimina un almacenamiento vectorial de forma asíncrona. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Elimina un archivo dentro de un almacenamiento vectorial de forma asíncrona. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | Recupera detalles de un asistente específico de forma asíncrona. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Recupera una lista de asistentes de forma asíncrona. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | Recupera detalles de un archivo específico de forma asíncrona. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | Recupera una lista de archivos de forma asíncrona según el propósito especificado. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | Recupera detalles de una ejecución específica dentro de un hilo de forma asíncrona. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Recupera una lista de ejecuciones para un hilo especificado de forma asíncrona. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Recupera detalles de un paso específico dentro de una ejecución de forma asíncrona. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Recupera una lista de pasos para una ejecución específica dentro de un hilo de forma asíncrona. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | Recupera detalles de un hilo específico de forma asíncrona. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string) | Recupera detalles de un mensaje específico dentro de un hilo de forma asíncrona. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Recupera una lista de mensajes para un hilo específico de forma asíncrona. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | Recupera detalles de un almacenamiento vectorial específico de forma asíncrona. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Recupera detalles de un archivo específico dentro de un almacenamiento vectorial de forma asíncrona. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Recupera detalles de un lote de archivos de almacenamiento vectorial específico de forma asíncrona. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Recupera una lista de archivos dentro de un lote de archivos de almacenamiento vectorial específico de forma asíncrona. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Recupera una lista de archivos dentro de un almacenamiento vectorial específico de forma asíncrona. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Recupera una lista de almacenes vectoriales de forma asíncrona. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifica un asistente existente de forma asíncrona. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifica una ejecución existente dentro de un hilo de forma asíncrona. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifica un hilo existente de forma asíncrona. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest) | Modifica un mensaje existente dentro de un hilo de forma asíncrona. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifica un almacenamiento vectorial existente de forma asíncrona. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Ejecuta el asistente con el threadId especificado y runCreateRequest, y obtiene la respuesta del asistente de forma asíncrona. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Sube un archivo de forma asíncrona al servidor de OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Espera el primer mensaje del asistente dentro de un hilo de forma asíncrona. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Espera a que una ejecución se complete dentro de un hilo de forma asíncrona. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Espera a que un mensaje específico del hilo se complete de forma asíncrona. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Espera a que un archivo específico de almacenamiento vectorial se complete de forma asíncrona. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Espera a que un almacenamiento vectorial específico se complete de forma asíncrona. |

### Ver También

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)