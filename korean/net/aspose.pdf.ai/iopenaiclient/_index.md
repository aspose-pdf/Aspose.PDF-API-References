---
title: Interface IOpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.IOpenAIClient 인터페이스. OpenAI API와 상호작용하기 위한 클라이언트 인터페이스로 기본 AI 클라이언트 기능을 확장합니다.
type: docs
weight: 540
url: /ko/net/aspose.pdf.ai/iopenaiclient/
---
## IOpenAIClient 인터페이스

OpenAI API와 상호작용하기 위한 클라이언트 인터페이스로, 기본 AI 클라이언트 기능을 확장합니다.

```csharp
public interface IOpenAIClient
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/iopenaiclient/cancelrunasync/)(string, string, CancellationToken?) | 스레드 내에서 기존 실행을 비동기적으로 취소합니다. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | 특정 벡터 저장소 파일 배치를 비동기적으로 취소합니다. |
| [CreateAssistantAsync](../../aspose.pdf.ai/iopenaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | 새로운 어시스턴트를 비동기적으로 생성합니다. |
| [CreateCompletionAsync](../../aspose.pdf.ai/iopenaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | 새로운 완료를 비동기적으로 생성합니다. |
| [CreateRunAsync](../../aspose.pdf.ai/iopenaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | 지정된 스레드 내에서 실행을 비동기적으로 생성합니다. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/iopenaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | 스레드와 그 안에서 실행을 비동기적으로 생성합니다. |
| [CreateThreadAsync](../../aspose.pdf.ai/iopenaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | 새로운 스레드를 비동기적으로 생성합니다. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | 스레드 내에서 새로운 메시지를 비동기적으로 생성합니다. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | 새로운 벡터 저장소를 생성하고 비동기적으로 완료될 때까지 기다립니다. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | 새로운 벡터 저장소를 비동기적으로 생성합니다. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | 새로운 벡터 저장소 파일을 비동기적으로 생성합니다. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | 새로운 벡터 저장소 파일 배치를 비동기적으로 생성합니다. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/iopenaiclient/deleteassistantasync/)(string, CancellationToken?) | 기존 어시스턴트를 비동기적으로 삭제합니다. |
| [DeleteFileAsync](../../aspose.pdf.ai/iopenaiclient/deletefileasync/)(string, CancellationToken?) | 특정 파일을 비동기적으로 삭제합니다. |
| [DeleteThreadAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadasync/)(string, CancellationToken?) | 기존 스레드를 비동기적으로 삭제합니다. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | 스레드 내에서 메시지를 비동기적으로 삭제합니다. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/)(string, CancellationToken?) | 벡터 저장소를 비동기적으로 삭제합니다. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | 벡터 저장소 내의 파일을 비동기적으로 삭제합니다. |
| [GetAssistantAsync](../../aspose.pdf.ai/iopenaiclient/getassistantasync/)(string, CancellationToken?) | 특정 어시스턴트의 세부 정보를 비동기적으로 검색합니다. |
| [GetAssistantsAsync](../../aspose.pdf.ai/iopenaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | 어시스턴트 목록을 비동기적으로 검색합니다. |
| [GetFileAsync](../../aspose.pdf.ai/iopenaiclient/getfileasync/)(string, CancellationToken?) | 특정 파일의 세부 정보를 비동기적으로 검색합니다. |
| [GetFilesAsync](../../aspose.pdf.ai/iopenaiclient/getfilesasync/)(string, CancellationToken?) | 지정된 목적에 따라 파일 목록을 비동기적으로 검색합니다. |
| [GetRunAsync](../../aspose.pdf.ai/iopenaiclient/getrunasync/)(string, string, CancellationToken?) | 스레드 내에서 특정 실행의 세부 정보를 비동기적으로 검색합니다. |
| [GetRunsAsync](../../aspose.pdf.ai/iopenaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | 지정된 스레드에 대한 실행 목록을 비동기적으로 검색합니다. |
| [GetRunStepAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | 실행 내에서 특정 단계의 세부 정보를 비동기적으로 검색합니다. |
| [GetRunStepsAsync](../../aspose.pdf.ai/iopenaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | 스레드 내에서 특정 실행에 대한 단계 목록을 비동기적으로 검색합니다. |
| [GetThreadAsync](../../aspose.pdf.ai/iopenaiclient/getthreadasync/)(string, CancellationToken?) | 특정 스레드의 세부 정보를 비동기적으로 검색합니다. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | 스레드 내에서 특정 메시지의 세부 정보를 비동기적으로 검색합니다. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 특정 스레드에 대한 메시지 목록을 비동기적으로 검색합니다. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoreasync/)(string, CancellationToken?) | 특정 벡터 저장소의 세부 정보를 비동기적으로 검색합니다. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | 벡터 저장소 내의 특정 파일의 세부 정보를 비동기적으로 검색합니다. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | 특정 벡터 저장소 파일 배치의 세부 정보를 비동기적으로 검색합니다. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | 특정 벡터 저장소 파일 배치 내의 파일 목록을 비동기적으로 검색합니다. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | 특정 벡터 저장소 내의 파일 목록을 비동기적으로 검색합니다. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/iopenaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | 벡터 저장소 목록을 비동기적으로 검색합니다. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/iopenaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | 기존 어시스턴트를 비동기적으로 수정합니다. |
| [ModifyRunAsync](../../aspose.pdf.ai/iopenaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | 스레드 내에서 기존 실행을 비동기적으로 수정합니다. |
| [ModifyThreadAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | 기존 스레드를 비동기적으로 수정합니다. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | 스레드 내에서 기존 메시지를 비동기적으로 수정합니다. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | 기존 벡터 저장소를 비동기적으로 수정합니다. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | 지정된 threadId와 runCreateRequest로 어시스턴트를 실행하고 비동기적으로 어시스턴트 응답을 가져옵니다. |
| [UploadFileAsync](../../aspose.pdf.ai/iopenaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | 파일을 OpenAI 서버에 비동기적으로 업로드합니다. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 스레드 내에서 어시스턴트의 첫 번째 메시지를 비동기적으로 기다립니다. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | 스레드 내에서 실행이 완료될 때까지 비동기적으로 기다립니다. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | 특정 스레드 메시지가 완료될 때까지 비동기적으로 기다립니다. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | 특정 벡터 저장소 파일이 완료될 때까지 비동기적으로 기다립니다. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/iopenaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | 특정 벡터 저장소가 완료될 때까지 비동기적으로 기다립니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)