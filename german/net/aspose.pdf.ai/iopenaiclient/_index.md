---
title: Interface IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IOpenAIClient-Schnittstelle. Stellt eine Client-Schnittstelle für die Interaktion mit der OpenAI-API dar, die grundlegende AI-Client-Funktionalitäten erweitert
type: docs
weight: 540
url: /de/net/aspose.pdf.ai/iopenaiclient/
---
## IOpenAIClient-Schnittstelle

Stellt eine Client-Schnittstelle für die Interaktion mit der OpenAI-API dar, die grundlegende AI-Client-Funktionalitäten erweitert.

```csharp
public interface IOpenAIClient
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | Kündigt einen bestehenden Lauf innerhalb eines Threads asynchron. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Kündigt einen bestimmten Vektorspeicher-Dateibatch asynchron. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Erstellt einen neuen Assistenten asynchron. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Erstellt eine neue Vervollständigung asynchron. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Erstellt einen Lauf innerhalb eines bestimmten Threads asynchron. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Erstellt einen Thread und einen Lauf darin asynchron. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Erstellt einen neuen Thread asynchron. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Erstellt eine neue Nachricht innerhalb eines Threads asynchron. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Erstellt einen neuen Vektorspeicher und wartet asynchron auf dessen Abschluss. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Erstellt einen neuen Vektorspeicher asynchron. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Erstellt eine neue Vektorspeicher-Datei asynchron. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Erstellt einen neuen Vektorspeicher-Dateibatch asynchron. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | Löscht einen bestehenden Assistenten asynchron. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | Löscht eine bestimmte Datei asynchron. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | Löscht einen bestehenden Thread asynchron. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Löscht eine Nachricht innerhalb eines Threads asynchron. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Löscht einen Vektorspeicher asynchron. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Löscht eine Datei innerhalb eines Vektorspeichers asynchron. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | Ruft Details eines bestimmten Assistenten asynchron ab. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Ruft eine Liste von Assistenten asynchron ab. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | Ruft Details einer bestimmten Datei asynchron ab. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | Ruft eine Liste von Dateien asynchron basierend auf dem angegebenen Zweck ab. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | Ruft Details eines bestimmten Laufs innerhalb eines Threads asynchron ab. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Ruft eine Liste von Läufen für einen bestimmten Thread asynchron ab. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Ruft Details eines bestimmten Schrittes innerhalb eines Laufs asynchron ab. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Ruft eine Liste von Schritten für einen bestimmten Lauf innerhalb eines Threads asynchron ab. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | Ruft Details eines bestimmten Threads asynchron ab. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Ruft Details einer bestimmten Nachricht innerhalb eines Threads asynchron ab. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Ruft eine Liste von Nachrichten für einen bestimmten Thread asynchron ab. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | Ruft Details eines bestimmten Vektorspeichers asynchron ab. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Ruft Details einer bestimmten Datei innerhalb eines Vektorspeichers asynchron ab. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Ruft Details eines bestimmten Vektorspeicher-Dateibatches asynchron ab. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Ruft eine Liste von Dateien innerhalb eines bestimmten Vektorspeicher-Dateibatches asynchron ab. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Ruft eine Liste von Dateien innerhalb eines bestimmten Vektorspeichers asynchron ab. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Ruft eine Liste von Vektorspeichern asynchron ab. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Ändert einen bestehenden Assistenten asynchron. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Ändert einen bestehenden Lauf innerhalb eines Threads asynchron. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Ändert einen bestehenden Thread asynchron. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Ändert eine bestehende Nachricht innerhalb eines Threads asynchron. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Ändert einen bestehenden Vektorspeicher asynchron. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Führt den Assistenten mit der angegebenen threadId und runCreateRequest aus und erhält asynchron die Antwort des Assistenten. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Lädt eine Datei asynchron auf den OpenAI-Server hoch. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Wartet asynchron auf die erste Nachricht des Assistenten innerhalb eines Threads. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Wartet asynchron auf den Abschluss eines Laufs innerhalb eines Threads. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Wartet asynchron auf den Abschluss einer bestimmten Thread-Nachricht. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Wartet asynchron auf den Abschluss einer bestimmten Vektorspeicher-Datei. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Wartet asynchron auf den Abschluss eines bestimmten Vektorspeichers. |

### Siehe auch

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)