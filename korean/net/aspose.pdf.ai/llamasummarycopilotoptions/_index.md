---
title: "클래스 LlamaSummaryCopilotOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.AI.LlamaSummaryCopilotOptions 클래스. OpenAICopilot을 구성하기 위한 옵션을 나타냅니다."
type: docs
weight: 800
url: /ko/net/aspose.pdf.ai/llamasummarycopilotoptions/
---
## LlamaSummaryCopilotOptions class

OpenAICopilot을 구성하기 위한 옵션을 나타냅니다.

```csharp
public class LlamaSummaryCopilotOptions : LlamaCopilotOptionsBase, 
    ISummaryCopilotOptions<LlamaSummaryCopilotOptions>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [DocumentCollection](../../aspose.pdf.ai/llamacopilotoptionsbase/documentcollection/) { get; set; } | 처리할 문서 컬렉션을 가져오거나 설정합니다. |
| [MaxCompletionTokens](../../aspose.pdf.ai/llamacopilotoptionsbase/maxcompletiontokens/) { get; set; } | 실행 중에 사용될 수 있는 최대 완성 토큰 수를 가져오거나 설정합니다. |
| virtual [Model](../../aspose.pdf.ai/llamacopilotoptionsbase/model/) { get; set; } | 도우미에 사용할 모델을 가져오거나 설정합니다. |
| [SummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/summaryprompt/) { get; set; } | 모델에게 문서 요약을 제공하도록 지시하는 프롬프트를 가져오거나 설정합니다. |
| [SystemInstructions](../../aspose.pdf.ai/llamacopilotoptionsbase/systeminstructions/) { get; set; } | 도우미 시스템 지침이 포함된 텍스트 파일의 파일 경로를 가져오거나 설정합니다. |
| [Temperature](../../aspose.pdf.ai/llamacopilotoptionsbase/temperature/) { get; set; } | 모델에 사용할 샘플링 온도를 가져오거나 설정합니다. |
| [TopP](../../aspose.pdf.ai/llamacopilotoptionsbase/topp/) { get; set; } | 핵심 샘플링을 위한 top-p 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create)() | 새 `LlamaSummaryCopilotOptions` 인스턴스를 생성합니다. |
| static [Create](../../aspose.pdf.ai/llamasummarycopilotoptions/create/#create_1)(Action&lt;LlamaSummaryCopilotOptions&gt;) | `LlamaSummaryCopilotOptions` 인스턴스를 생성하고 제공된 delegate를 사용하여 구성합니다. |
| [GetOptions](../../aspose.pdf.ai/llamasummarycopilotoptions/getoptions/)() | 현재 `LlamaSummaryCopilotOptions`를 가져옵니다. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument)(PdfDocument) | 요약 코파일럿 옵션을 위한 문서 컬렉션에 PDF 문서를 추가합니다. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_2)(string) | 요약 코파일럿 옵션을 위한 문서 컬렉션에 문서 경로를 추가합니다. |
| [WithDocument](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocument/#withdocument_1)(TextDocument) | 요약 코파일럿 옵션을 위한 문서 컬렉션에 텍스트 문서를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 요약 코파일럿 옵션의 문서 컬렉션을 설정합니다. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 요약 코파일럿 옵션을 위한 문서 컬렉션에 여러 PDF 문서를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_3)(List&lt;string&gt;) | 요약 코파일럿 옵션을 위한 문서 컬렉션에 여러 문서 경로를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/llamasummarycopilotoptions/withdocuments/#withdocuments_2)(List&lt;TextDocument&gt;) | 요약 코파일럿 옵션을 위한 문서 컬렉션에 여러 텍스트 문서를 추가합니다. |
| [WithInstructions](../../aspose.pdf.ai/llamasummarycopilotoptions/withinstructions/)(string) | 요약 코파일럿 옵션의 지침을 설정합니다. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/llamasummarycopilotoptions/withmaxcompletiontokens/)(int?) | 요약 코파일럿 옵션의 최대 완료 토큰을 설정합니다. |
| [WithModel](../../aspose.pdf.ai/llamasummarycopilotoptions/withmodel/)(string) | 요약 코파일럿 옵션의 모델을 설정합니다. |
| [WithSummaryPrompt](../../aspose.pdf.ai/llamasummarycopilotoptions/withsummaryprompt/)(string) | 요약 코파일럿 옵션의 요약 프롬프트를 설정합니다. |
| [WithTemperature](../../aspose.pdf.ai/llamasummarycopilotoptions/withtemperature/)(double?) | 요약 코파일럿 옵션의 온도를 설정합니다. |
| [WithTopP](../../aspose.pdf.ai/llamasummarycopilotoptions/withtopp/)(double?) | 요약 코파일럿 옵션의 top P 값을 설정합니다. |

### 또 보기

* class [LlamaCopilotOptionsBase](../llamacopilotoptionsbase/)
* interface [ISummaryCopilotOptions&lt;TOptions&gt;](../isummarycopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


