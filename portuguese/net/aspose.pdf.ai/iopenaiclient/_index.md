---
title: Interface IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Interface Aspose.Pdf.AI.IOpenAIClient. Representa uma interface de cliente para interagir com a API OpenAI, estendendo as funcionalidades básicas do cliente de IA
type: docs
weight: 540
url: /pt/net/aspose.pdf.ai/iopenaiclient/
---
## Interface IOpenAIClient

Representa uma interface de cliente para interagir com a API OpenAI, estendendo as funcionalidades básicas do cliente de IA.

```csharp
public interface IOpenAIClient
```

## Métodos

| Nome | Descrição |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | Cancela uma execução existente dentro de uma thread de forma assíncrona. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Cancela um lote específico de arquivos de armazenamento vetorial de forma assíncrona. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Cria um novo assistente de forma assíncrona. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Cria uma nova conclusão de forma assíncrona. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Cria uma execução dentro de uma thread especificada de forma assíncrona. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Cria uma thread e uma execução dentro dela de forma assíncrona. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Cria uma nova thread de forma assíncrona. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Cria uma nova mensagem dentro de uma thread de forma assíncrona. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Cria um novo armazenamento vetorial e aguarda sua conclusão de forma assíncrona. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Cria um novo armazenamento vetorial de forma assíncrona. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Cria um novo arquivo de armazenamento vetorial de forma assíncrona. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Cria um novo lote de arquivos de armazenamento vetorial de forma assíncrona. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | Exclui um assistente existente de forma assíncrona. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | Exclui um arquivo específico de forma assíncrona. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | Exclui uma thread existente de forma assíncrona. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Exclui uma mensagem dentro de uma thread de forma assíncrona. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Exclui um armazenamento vetorial de forma assíncrona. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Exclui um arquivo dentro de um armazenamento vetorial de forma assíncrona. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | Recupera detalhes de um assistente específico de forma assíncrona. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Recupera uma lista de assistentes de forma assíncrona. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | Recupera detalhes de um arquivo específico de forma assíncrona. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | Recupera uma lista de arquivos de forma assíncrona com base no propósito especificado. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | Recupera detalhes de uma execução específica dentro de uma thread de forma assíncrona. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Recupera uma lista de execuções para uma thread especificada de forma assíncrona. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Recupera detalhes de um passo específico dentro de uma execução de forma assíncrona. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Recupera uma lista de passos para uma execução específica dentro de uma thread de forma assíncrona. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | Recupera detalhes de uma thread específica de forma assíncrona. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string) | Recupera detalhes de uma mensagem específica dentro de uma thread de forma assíncrona. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Recupera uma lista de mensagens para uma thread específica de forma assíncrona. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | Recupera detalhes de um armazenamento vetorial específico de forma assíncrona. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Recupera detalhes de um arquivo específico dentro de um armazenamento vetorial de forma assíncrona. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Recupera detalhes de um lote específico de arquivos de armazenamento vetorial de forma assíncrona. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Recupera uma lista de arquivos dentro de um lote específico de arquivos de armazenamento vetorial de forma assíncrona. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Recupera uma lista de arquivos dentro de um armazenamento vetorial específico de forma assíncrona. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Recupera uma lista de armazenamentos vetoriais de forma assíncrona. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifica um assistente existente de forma assíncrona. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifica uma execução existente dentro de uma thread de forma assíncrona. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Modifica uma thread existente de forma assíncrona. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Modifica uma mensagem existente dentro de uma thread de forma assíncrona. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifica um armazenamento vetorial existente de forma assíncrona. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Executa o assistente com o threadId especificado e runCreateRequest, e obtém a resposta do assistente de forma assíncrona. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Faz o upload de um arquivo de forma assíncrona para o servidor OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Aguarda a primeira mensagem do assistente dentro de uma thread de forma assíncrona. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Aguarda a conclusão de uma execução dentro de uma thread de forma assíncrona. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Aguarda a conclusão de uma mensagem específica de thread de forma assíncrona. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Aguarda a conclusão de um arquivo específico de armazenamento vetorial de forma assíncrona. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Aguarda a conclusão de um armazenamento vetorial específico de forma assíncrona. |

### Veja Também

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)