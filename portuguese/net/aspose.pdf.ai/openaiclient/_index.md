---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.AI.OpenAIClient. Fornece métodos para interagir com a API OpenAI para gerenciar lotes de arquivos de armazenamento vetorial
type: docs
weight: 840
url: /pt/net/aspose.pdf.ai/openaiclient/
---
## Classe OpenAIClient

Fornece métodos para interagir com a API OpenAI para gerenciar lotes de arquivos de armazenamento vetorial.

Fornece métodos para interagir com a API OpenAI para gerenciar arquivos de armazenamento vetorial.

Fornece métodos para interagir com a API OpenAI para gerenciar armazenamentos vetoriais.

Representa um cliente para interagir com a API OpenAI, estendendo as funcionalidades básicas do cliente de IA.

Fornece métodos para interagir com a API OpenAI para gerenciar etapas de execução dentro de threads.

Fornece métodos para interagir com a API OpenAI para gerenciar arquivos.

Fornece métodos para interagir com a API OpenAI para gerenciar mensagens de thread.

Fornece métodos para interagir com a API OpenAI para gerenciar threads.

Fornece métodos para interagir com a API OpenAI para gerenciar assistentes.

Fornece um método para interagir com a API OpenAI para criar conclusões.

Fornece métodos para interagir com a API OpenAI para gerenciar execuções dentro de threads.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Obtém ou define o atraso de retrocesso em segundos. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Obtém ou define o número máximo de tentativas de requisições HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Obtém ou define o intervalo de polling em segundos. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Obtém ou define o tempo limite de polling em segundos. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Cancela uma execução existente dentro de uma thread de forma assíncrona. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Cancela um lote específico de arquivos de armazenamento vetorial de forma assíncrona. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Cria um novo assistente de forma assíncrona. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Cria uma nova conclusão de forma assíncrona. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Cria uma execução dentro de uma thread especificada de forma assíncrona. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Cria uma thread e uma execução dentro dela de forma assíncrona. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Cria uma nova thread de forma assíncrona. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Cria uma nova mensagem dentro de uma thread de forma assíncrona. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Cria um novo armazenamento vetorial e aguarda sua conclusão de forma assíncrona. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Cria um novo armazenamento vetorial de forma assíncrona. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Cria um novo arquivo de armazenamento vetorial de forma assíncrona. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Cria um novo lote de arquivos de armazenamento vetorial de forma assíncrona. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Exclui um assistente existente de forma assíncrona. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Exclui um arquivo específico de forma assíncrona. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Exclui uma thread existente de forma assíncrona. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Exclui uma mensagem dentro de uma thread de forma assíncrona. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Exclui um armazenamento vetorial de forma assíncrona. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | Exclui um arquivo dentro de um armazenamento vetorial de forma assíncrona. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Libera os recursos usados pelo [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Recupera detalhes de um assistente específico de forma assíncrona. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Recupera uma lista de assistentes de forma assíncrona. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Obtém uma instância de [`IChatCopilot`](../ichatcopilot/) com as opções especificadas. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Recupera detalhes de um arquivo específico de forma assíncrona. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Recupera uma lista de arquivos de forma assíncrona com base no propósito especificado. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Obtém uma instância de [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) com as opções especificadas. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Recupera detalhes de uma execução específica dentro de uma thread de forma assíncrona. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Recupera uma lista de execuções para uma thread especificada de forma assíncrona. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Recupera detalhes de uma etapa específica dentro de uma execução de forma assíncrona. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Recupera uma lista de etapas para uma execução específica dentro de uma thread de forma assíncrona. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Obtém uma instância de [`ISummaryCopilot`](../isummarycopilot/) com as opções especificadas. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Recupera detalhes de uma thread específica de forma assíncrona. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Recupera detalhes de uma mensagem específica dentro de uma thread de forma assíncrona. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Recupera uma lista de mensagens para uma thread específica de forma assíncrona. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Recupera detalhes de um armazenamento vetorial específico de forma assíncrona. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | Recupera detalhes de um arquivo específico dentro de um armazenamento vetorial de forma assíncrona. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Recupera detalhes de um lote específico de arquivos de armazenamento vetorial de forma assíncrona. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Recupera uma lista de arquivos dentro de um lote específico de arquivos de armazenamento vetorial de forma assíncrona. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Recupera uma lista de arquivos dentro de um armazenamento vetorial específico de forma assíncrona. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Recupera uma lista de armazenamentos vetoriais de forma assíncrona. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Modifica um assistente existente de forma assíncrona. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Modifica uma execução existente dentro de uma thread de forma assíncrona. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest) | Modifica uma thread existente de forma assíncrona. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest) | Modifica uma mensagem existente dentro de uma thread de forma assíncrona. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Modifica um armazenamento vetorial existente de forma assíncrona. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Executa o assistente com o threadId e runCreateRequest especificados e obtém a resposta do assistente de forma assíncrona. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Faz o upload de um arquivo de forma assíncrona para o servidor OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Aguarda a primeira mensagem do assistente dentro de uma thread de forma assíncrona. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Aguarda a conclusão de uma execução dentro de uma thread de forma assíncrona. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Aguarda a conclusão de uma mensagem específica de thread de forma assíncrona. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Aguarda a conclusão de um arquivo específico de armazenamento vetorial de forma assíncrona. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Aguarda a conclusão de um armazenamento vetorial específico de forma assíncrona. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Cria uma nova instância de [`Builder`](../openaiclient.builder/) com a chave da API fornecida. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Classe Builder para criar uma instância de `OpenAIClient`. |

### Veja Também

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