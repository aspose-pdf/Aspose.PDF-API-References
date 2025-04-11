---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIClient-Klasse. Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Vektor-Store-Dateibatches
type: docs
weight: 840
url: /de/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient-Klasse

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Vektor-Store-Dateibatches.

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Vektor-Store-Dateien.

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Vektor-Stores.

Stellt einen Client zur Interaktion mit der OpenAI-API dar, der die grundlegenden Funktionen des KI-Clients erweitert.

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Ausführungsschritten innerhalb von Threads.

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Dateien.

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Thread-Nachrichten.

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Threads.

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Assistenten.

Bietet eine Methode zur Interaktion mit der OpenAI-API zur Erstellung von Vervollständigungen.

Bietet Methoden zur Interaktion mit der OpenAI-API zur Verwaltung von Ausführungen innerhalb von Threads.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Ruft den Backoff-Verzögerungswert in Sekunden ab oder legt ihn fest. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Ruft die maximale Anzahl von HTTP-Anforderungswiederholungen ab oder legt sie fest. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Ruft das Polling-Intervall in Sekunden ab oder legt es fest. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Ruft das Polling-Timeout in Sekunden ab oder legt es fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Kündigt eine bestehende Ausführung innerhalb eines Threads asynchron. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Kündigt einen bestimmten Vektor-Store-Dateibatch asynchron. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Erstellt asynchron einen neuen Assistenten. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Erstellt asynchron eine neue Vervollständigung. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Erstellt asynchron eine Ausführung innerhalb eines bestimmten Threads. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Erstellt asynchron einen Thread und eine Ausführung darin. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Erstellt asynchron einen neuen Thread. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Erstellt asynchron eine neue Nachricht innerhalb eines Threads. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Erstellt asynchron einen neuen Vektor-Store und wartet auf dessen Abschluss. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Erstellt asynchron einen neuen Vektor-Store. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Erstellt asynchron eine neue Vektor-Store-Datei. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Erstellt asynchron einen neuen Vektor-Store-Dateibatch. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Löscht asynchron einen bestehenden Assistenten. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Löscht asynchron eine bestimmte Datei. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Löscht asynchron einen bestehenden Thread. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Löscht asynchron eine Nachricht innerhalb eines Threads. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Löscht asynchron einen Vektor-Store. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | Löscht asynchron eine Datei innerhalb eines Vektor-Stores. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Gibt die von [`AIClientBase`](../aiclientbase/) verwendeten Ressourcen frei. |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Ruft asynchron die Details eines bestimmten Assistenten ab. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Ruft asynchron eine Liste von Assistenten ab. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Ruft eine Instanz von [`IChatCopilot`](../ichatcopilot/) mit den angegebenen Optionen ab. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Ruft asynchron die Details einer bestimmten Datei ab. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Ruft asynchron eine Liste von Dateien basierend auf dem angegebenen Zweck ab. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Ruft eine Instanz von [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) mit den angegebenen Optionen ab. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Ruft asynchron die Details einer bestimmten Ausführung innerhalb eines Threads ab. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Ruft asynchron eine Liste von Ausführungen für einen bestimmten Thread ab. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Ruft asynchron die Details eines bestimmten Schrittes innerhalb einer Ausführung ab. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Ruft asynchron eine Liste von Schritten für eine bestimmte Ausführung innerhalb eines Threads ab. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Ruft eine Instanz von [`ISummaryCopilot`](../isummarycopilot/) mit den angegebenen Optionen ab. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Ruft asynchron die Details eines bestimmten Threads ab. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Ruft asynchron die Details einer bestimmten Nachricht innerhalb eines Threads ab. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Ruft asynchron eine Liste von Nachrichten für einen bestimmten Thread ab. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Ruft asynchron die Details eines bestimmten Vektor-Stores ab. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | Ruft asynchron die Details einer bestimmten Datei innerhalb eines Vektor-Stores ab. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Ruft asynchron die Details eines bestimmten Vektor-Store-Dateibatches ab. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Ruft asynchron eine Liste von Dateien innerhalb eines bestimmten Vektor-Store-Dateibatches ab. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Ruft asynchron eine Liste von Dateien innerhalb eines bestimmten Vektor-Stores ab. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Ruft asynchron eine Liste von Vektor-Stores ab. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Ändert asynchron einen bestehenden Assistenten. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Ändert asynchron eine bestehende Ausführung innerhalb eines Threads. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Ändert asynchron einen bestehenden Thread. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Ändert asynchron eine bestehende Nachricht innerhalb eines Threads. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Ändert asynchron einen bestehenden Vektor-Store. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Führt den Assistenten mit der angegebenen threadId und runCreateRequest aus und erhält asynchron die Antwort des Assistenten. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Lädt eine Datei asynchron auf den OpenAI-Server hoch. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Wartet asynchron auf die erste Nachricht des Assistenten innerhalb eines Threads. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Wartet asynchron auf den Abschluss einer Ausführung innerhalb eines Threads. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Wartet asynchron auf den Abschluss einer bestimmten Thread-Nachricht. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Wartet asynchron auf den Abschluss einer bestimmten Vektor-Store-Datei. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Wartet asynchron auf den Abschluss eines bestimmten Vektor-Stores. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Erstellt eine neue Instanz von [`Builder`](../openaiclient.builder/) mit dem angegebenen API-Schlüssel. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Builder-Klasse zur Erstellung einer Instanz von `OpenAIClient`. |

### Siehe auch

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