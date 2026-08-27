---
title: "클래스 OpenAIChatCopilotOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.OpenAIChatCopilotOptions 클래스. OpenAICopilot을 구성하기 위한 옵션을 나타냅니다."
type: docs
weight: 890
url: /ko/net/aspose.pdf.ai/openaichatcopilotoptions/
---
## OpenAIChatCopilotOptions class

OpenAICopilot을 구성하기 위한 옵션을 나타냅니다.

```csharp
public class OpenAIChatCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IChatCopilotOptions<OpenAIChatCopilotOptions>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/assistantname/) { get; set; } | 어시스턴트의 이름을 가져오거나 설정합니다. |
| [ContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/contextbackupjsonpath/) { get; set; } | 컨텍스트 백업 JSON의 파일 경로를 가져오거나 설정합니다. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 처리할 문서 컬렉션을 가져오거나 설정합니다. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 실행 중에 사용될 수 있는 최대 완성 토큰 수를 가져오거나 설정합니다. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/maxprompttokens/) { get; set; } | 실행 동안 사용할 수 있는 프롬프트 토큰의 최대 수를 가져오거나 설정합니다. |
| [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | 도우미에 사용할 모델을 가져오거나 설정합니다. |
| [RestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/restorecontextfrombackup/) { get; set; } | 백업에서 컨텍스트를 복원할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | 도우미 시스템 지침이 포함된 텍스트 파일의 파일 경로를 가져오거나 설정합니다. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | 모델에 사용할 샘플링 온도를 가져오거나 설정합니다. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 핵심 샘플링을 위한 top-p 값을 가져오거나 설정합니다. |
| [TruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/truncationstrategy/) { get; set; } | 스레드에 대한 잘라내기 전략을 가져오거나 설정합니다. |
| [VectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/vectorstoreexpiredays/) { get; set; } | 벡터 저장소가 만료되기까지의 일수를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create)() | 새 `OpenAIChatCopilotOptions` 인스턴스를 생성합니다. |
| static [Create](../../aspose.pdf.ai/openaichatcopilotoptions/create/#create_1)(Action&lt;OpenAIChatCopilotOptions&gt;) | 제공된 대리자를 사용하여 `OpenAIChatCopilotOptions` 인스턴스를 생성하고 구성합니다. |
| [GetOptions](../../aspose.pdf.ai/openaichatcopilotoptions/getoptions/)() | 현재 `OpenAIChatCopilotOptions`를 가져옵니다. |
| [WithAssistantName](../../aspose.pdf.ai/openaichatcopilotoptions/withassistantname/)(string) | 채팅 코파일럿 옵션의 어시스턴트 이름을 설정합니다. |
| [WithContextBackupJsonPath](../../aspose.pdf.ai/openaichatcopilotoptions/withcontextbackupjsonpath/)(string) | 채팅 코파일럿 옵션에서 컨텍스트 백업 JSON의 파일 경로를 설정합니다. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument)(PdfDocument) | 채팅 코파일럿 옵션의 문서 컬렉션에 PDF 문서를 추가합니다. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_2)(string) | 채팅 코파일럿 옵션의 문서 컬렉션에 문서 경로를 추가합니다. |
| [WithDocument](../../aspose.pdf.ai/openaichatcopilotoptions/withdocument/#withdocument_1)(TextDocument) | 채팅 코파일럿 옵션의 문서 컬렉션에 텍스트 문서를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 채팅 코파일럿 옵션의 문서 컬렉션을 설정합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 채팅 코파일럿 옵션의 문서 컬렉션에 여러 PDF 문서를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 채팅 코파일럿 옵션의 문서 컬렉션에 여러 문서 경로를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaichatcopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 채팅 코파일럿 옵션의 문서 컬렉션에 여러 텍스트 문서를 추가합니다. |
| [WithInstructions](../../aspose.pdf.ai/openaichatcopilotoptions/withinstructions/)(string) | 채팅 코파일럿 옵션의 지침을 설정합니다. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxcompletiontokens/)(int?) | 채팅 코파일럿 옵션의 최대 완료 토큰을 설정합니다. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaichatcopilotoptions/withmaxprompttokens/)(int?) | 채팅 코파일럿 옵션의 최대 프롬프트 토큰을 설정합니다. |
| [WithModel](../../aspose.pdf.ai/openaichatcopilotoptions/withmodel/)(string) | 채팅 코파일럿 옵션의 모델을 설정합니다. |
| [WithRestoreContextFromBackup](../../aspose.pdf.ai/openaichatcopilotoptions/withrestorecontextfrombackup/)(bool) | 채팅 코파일럿 옵션에서 백업으로부터 컨텍스트를 복원할지 여부를 설정합니다. |
| [WithTemperature](../../aspose.pdf.ai/openaichatcopilotoptions/withtemperature/)(double?) | 채팅 코파일럿 옵션의 온도를 설정합니다. |
| [WithTopP](../../aspose.pdf.ai/openaichatcopilotoptions/withtopp/)(double?) | 채팅 코파일럿 옵션의 top P 값을 설정합니다. |
| [WithTruncationStrategy](../../aspose.pdf.ai/openaichatcopilotoptions/withtruncationstrategy/)(TruncationStrategy) | 채팅 코파일럿 옵션의 잘림 전략을 설정합니다. |
| [WithVectorStoreExpireDays](../../aspose.pdf.ai/openaichatcopilotoptions/withvectorstoreexpiredays/)(int) | 채팅 코파일럿 옵션에서 벡터 저장소 만료 일수를 설정합니다. |

### 또 보기

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IChatCopilotOptions&lt;TOptions&gt;](../ichatcopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


