---
title: Class OpenAISummaryCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAISummaryCopilotOptions 클래스. OpenAICopilot을 구성하기 위한 옵션을 나타냅니다.
type: docs
weight: 930
url: /ko/net/aspose.pdf.ai/openaisummarycopilotoptions/
---
## OpenAISummaryCopilotOptions 클래스

OpenAICopilot을 구성하기 위한 옵션을 나타냅니다.

```csharp
public class OpenAISummaryCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    ISummaryCopilotOptions<OpenAISummaryCopilotOptions>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/assistantname/) { get; set; } | 어시스턴트의 이름을 가져오거나 설정합니다. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 처리할 문서의 컬렉션을 가져오거나 설정합니다. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 실행 중 사용할 수 있는 최대 완료 토큰 수를 가져오거나 설정합니다. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | 실행 중 사용할 수 있는 최대 프롬프트 토큰 수를 가져오거나 설정합니다. |
| virtual [Model](../../aspose.pdf.ai/openaicopilotoptionsbase/model/) { get; set; } | 어시스턴트에 사용할 모델을 가져오거나 설정합니다. |
| [SummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/summaryprompt/) { get; set; } | 모델에게 문서 요약을 제공하도록 지시하는 프롬프트를 가져오거나 설정합니다. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | 어시스턴트 시스템 지침이 포함된 텍스트 파일의 파일 경로를 가져오거나 설정합니다. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | 모델에 사용할 샘플링 온도를 가져오거나 설정합니다. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 핵심 샘플링을 위한 top-p 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create)() | `OpenAISummaryCopilotOptions`의 새 인스턴스를 생성합니다. |
| static [Create](../../aspose.pdf.ai/openaisummarycopilotoptions/create/#create_1)(Action&lt;OpenAISummaryCopilotOptions&gt;) | `OpenAISummaryCopilotOptions`의 인스턴스를 생성하고 제공된 델리게이트를 사용하여 구성합니다. |
| [GetOptions](../../aspose.pdf.ai/openaisummarycopilotoptions/getoptions/)() | 현재 `OpenAISummaryCopilotOptions`를 가져옵니다. |
| [WithAssistantName](../../aspose.pdf.ai/openaisummarycopilotoptions/withassistantname/)(string) | 요약 코파일럿 옵션의 어시스턴트 이름을 설정합니다. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | 요약 코파일럿 옵션의 문서 컬렉션에 PDF 문서를 추가합니다. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_2)(string) | 요약 코파일럿 옵션의 문서 컬렉션에 문서 경로를 추가합니다. |
| [WithDocument](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | 요약 코파일럿 옵션의 문서 컬렉션에 텍스트 문서를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 요약 코파일럿 옵션의 문서 컬렉션을 설정합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 요약 코파일럿 옵션의 문서 컬렉션에 여러 PDF 문서를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 요약 코파일럿 옵션의 문서 컬렉션에 여러 문서 경로를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaisummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 요약 코파일럿 옵션의 문서 컬렉션에 여러 텍스트 문서를 추가합니다. |
| [WithInstructions](../../aspose.pdf.ai/openaisummarycopilotoptions/withinstructions/)(string) | 요약 코파일럿 옵션의 지침을 설정합니다. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxcompletiontokens/)(int?) | 요약 코파일럿 옵션의 최대 완료 토큰을 설정합니다. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaisummarycopilotoptions/withmaxprompttokens/)(int?) | 요약 코파일럿 옵션의 최대 프롬프트 토큰을 설정합니다. |
| [WithModel](../../aspose.pdf.ai/openaisummarycopilotoptions/withmodel/)(string) | 요약 코파일럿 옵션의 모델을 설정합니다. |
| [WithSummaryPrompt](../../aspose.pdf.ai/openaisummarycopilotoptions/withsummaryprompt/)(string) | 요약 코파일럿 옵션의 요약 프롬프트를 설정합니다. |
| [WithTemperature](../../aspose.pdf.ai/openaisummarycopilotoptions/withtemperature/)(double?) | 요약 코파일럿 옵션의 온도를 설정합니다. |
| [WithTopP](../../aspose.pdf.ai/openaisummarycopilotoptions/withtopp/)(double?) | 요약 코파일럿 옵션의 top P 값을 설정합니다. |

### 참조

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)