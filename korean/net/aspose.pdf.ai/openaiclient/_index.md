---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIClient 클래스. 벡터 저장소 파일 배치를 관리하기 위해 OpenAI API와 상호작용하는 메서드를 제공합니다.
type: docs
weight: 840
url: /ko/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient 클래스

OpenAI API와 상호작용하여 벡터 저장소 파일 배치를 관리하는 메서드를 제공합니다.

OpenAI API와 상호작용하여 벡터 저장소 파일을 관리하는 메서드를 제공합니다.

OpenAI API와 상호작용하여 벡터 저장소를 관리하는 메서드를 제공합니다.

OpenAI API와 상호작용하기 위한 클라이언트를 나타내며, 기본 AI 클라이언트 기능을 확장합니다.

스레드 내에서 실행 단계를 관리하기 위해 OpenAI API와 상호작용하는 메서드를 제공합니다.

파일을 관리하기 위해 OpenAI API와 상호작용하는 메서드를 제공합니다.

스레드 메시지를 관리하기 위해 OpenAI API와 상호작용하는 메서드를 제공합니다.

스레드를 관리하기 위해 OpenAI API와 상호작용하는 메서드를 제공합니다.

어시스턴트를 관리하기 위해 OpenAI API와 상호작용하는 메서드를 제공합니다.

완성을 생성하기 위해 OpenAI API와 상호작용하는 메서드를 제공합니다.

스레드 내에서 실행을 관리하기 위해 OpenAI API와 상호작용하는 메서드를 제공합니다.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | 백오프 지연 시간을 초 단위로 가져오거나 설정합니다. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | 최대 HTTP 요청 재시도 횟수를 가져오거나 설정합니다. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | 폴링 간격을 초 단위로 가져오거나 설정합니다. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | 폴링 타임아웃을 초 단위로 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | 스레드 내에서 기존 실행을 비동기적으로 취소합니다. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | 특정 벡터 저장소 파일 배치를 비동기적으로 취소합니다. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | 새로운 어시스턴트를 비동기적으로 생성합니다. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | 새로운 완성을 비동기적으로 생성합니다. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | 지정된 스레드 내에서 실행을 비동기적으로 생성합니다. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | 스레드와 그 안에서 실행을 비동기적으로 생성합니다. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | 새로운 스레드를 비동기적으로 생성합니다. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | 스레드 내에서 새로운 메시지를 비동기적으로 생성합니다. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | 새로운 벡터 저장소를 생성하고 비동기적으로 완료될 때까지 기다립니다. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | 새로운 벡터 저장소를 비동기적으로 생성합니다. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | 새로운 벡터 저장소 파일을 비동기적으로 생성합니다. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | 새로운 벡터 저장소 파일 배치를 비동기적으로 생성합니다. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | 기존 어시스턴트를 비동기적으로 삭제합니다. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | 특정 파일을 비동기적으로 삭제합니다. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | 기존 스레드를 비동기적으로 삭제합니다. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | 스레드 내에서 메시지를 비동기적으로 삭제합니다. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | 벡터 저장소를 비동기적으로 삭제합니다. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | 벡터 저장소 내의 파일을 비동기적으로 삭제합니다. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | [`AIClientBase`](../aiclientbase/)에서 사용하는 리소스를 해제합니다. |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | 특정 어시스턴트의 세부 정보를 비동기적으로 검색합니다. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | 어시스턴트 목록을 비동기적으로 검색합니다. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | 지정된 옵션으로 [`IChatCopilot`](../ichatcopilot/)의 인스턴스를 가져옵니다. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | 특정 파일의 세부 정보를 비동기적으로 검색합니다. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | 지정된 목적에 따라 파일 목록을 비동기적으로 검색합니다. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | 지정된 옵션으로 [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/)의 인스턴스를 가져옵니다. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | 스레드 내에서 특정 실행의 세부 정보를 비동기적으로 검색합니다. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | 지정된 스레드에 대한 실행 목록을 비동기적으로 검색합니다. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | 실행 내에서 특정 단계의 세부 정보를 비동기적으로 검색합니다. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | 스레드 내에서 특정 실행에 대한 단계 목록을 비동기적으로 검색합니다. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | 지정된 옵션으로 [`ISummaryCopilot`](../isummarycopilot/)의 인스턴스를 가져옵니다. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | 특정 스레드의 세부 정보를 비동기적으로 검색합니다. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | 스레드 내에서 특정 메시지의 세부 정보를 비동기적으로 검색합니다. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 특정 스레드에 대한 메시지 목록을 비동기적으로 검색합니다. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | 특정 벡터 저장소의 세부 정보를 비동기적으로 검색합니다. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | 벡터 저장소 내의 특정 파일의 세부 정보를 비동기적으로 검색합니다. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string) | 특정 벡터 저장소 파일 배치의 세부 정보를 비동기적으로 검색합니다. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | 특정 벡터 저장소 파일 배치 내의 파일 목록을 비동기적으로 검색합니다. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | 특정 벡터 저장소 내의 파일 목록을 비동기적으로 검색합니다. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | 벡터 저장소 목록을 비동기적으로 검색합니다. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | 기존 어시스턴트를 비동기적으로 수정합니다. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | 스레드 내에서 기존 실행을 비동기적으로 수정합니다. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | 기존 스레드를 비동기적으로 수정합니다. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | 스레드 내에서 기존 메시지를 비동기적으로 수정합니다. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | 기존 벡터 저장소를 비동기적으로 수정합니다. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | 지정된 threadId와 runCreateRequest로 어시스턴트를 실행하고 비동기적으로 어시스턴트 응답을 가져옵니다. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | 파일을 OpenAI 서버에 비동기적으로 업로드합니다. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | 스레드 내에서 어시스턴트의 첫 번째 메시지를 비동기적으로 기다립니다. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | 스레드 내에서 실행이 완료될 때까지 비동기적으로 기다립니다. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | 특정 스레드 메시지가 완료될 때까지 비동기적으로 기다립니다. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | 특정 벡터 저장소 파일이 완료될 때까지 비동기적으로 기다립니다. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | 특정 벡터 저장소가 완료될 때까지 비동기적으로 기다립니다. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | 제공된 API 키로 [`Builder`](../openaiclient.builder/)의 새 인스턴스를 생성합니다. |

## 기타 구성원

| 이름 | 설명 |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | `OpenAIClient`의 인스턴스를 생성하기 위한 빌더 클래스입니다. |

### 참조

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