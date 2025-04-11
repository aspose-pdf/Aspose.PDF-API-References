---
title: Class OpenAIImageDescriptionCopilotOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OpenAIImageDescriptionCopilotOptions 클래스. OpenAICopilot을 구성하기 위한 옵션을 나타냅니다.
type: docs
weight: 900
url: /ko/net/aspose.pdf.ai/openaiimagedescriptioncopilotoptions/
---
## OpenAIImageDescriptionCopilotOptions 클래스

OpenAICopilot을 구성하기 위한 옵션을 나타냅니다.

```csharp
public class OpenAIImageDescriptionCopilotOptions : OpenAIAssistantCopilotOptionsBase, 
    IImageDescriptionCopilotOptions<OpenAIImageDescriptionCopilotOptions>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/assistantname/) { get; set; } | 어시스턴트의 이름을 가져오거나 설정합니다. |
| [DocumentCollection](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/documentcollection/) { get; set; } | 처리할 문서 컬렉션을 가져오거나 설정합니다. |
| [ImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedescriptionprompt/) { get; set; } | 모델에게 이미지 설명을 제공하도록 지시하는 프롬프트를 가져오거나 설정합니다. |
| [ImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/imagedetail/) { get; set; } | 사용자가 지정한 경우 이미지의 세부 수준을 가져오거나 설정합니다. "low"는 더 적은 토큰을 사용하며, "high"를 사용하여 고해상도로 선택할 수 있습니다. 설정하지 않으면 기본값은 "auto"입니다. |
| [MaxCompletionTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxcompletiontokens/) { get; set; } | 실행 중 사용할 수 있는 최대 완료 토큰 수를 가져오거나 설정합니다. |
| [MaxPromptTokens](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/maxprompttokens/) { get; set; } | 실행 중 사용할 수 있는 최대 프롬프트 토큰 수를 가져오거나 설정합니다. |
| override [Model](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/model/) { get; set; } | 어시스턴트에 사용할 비전 모델을 가져오거나 설정합니다. |
| [SystemInstructions](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/systeminstructions/) { get; set; } | 어시스턴트 시스템 지침이 포함된 텍스트 파일의 파일 경로를 가져오거나 설정합니다. |
| [Temperature](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/temperature/) { get; set; } | 모델에 사용할 샘플링 온도를 가져오거나 설정합니다. |
| [TopP](../../aspose.pdf.ai/openaiassistantcopilotoptionsbase/topp/) { get; set; } | 핵심 샘플링을 위한 top-p 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create)() | `OpenAIImageDescriptionCopilotOptions`의 새 인스턴스를 생성합니다. |
| static [Create](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/create/#create_1)(Action&lt;OpenAIImageDescriptionCopilotOptions&gt;) | `OpenAIImageDescriptionCopilotOptions`의 인스턴스를 생성하고 제공된 델리게이트를 사용하여 구성합니다. |
| [GetOptions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/getoptions/)() | 현재 `OpenAIImageDescriptionCopilotOptions`를 가져옵니다. |
| [WithAssistantName](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withassistantname/)(string) | 이미지 설명 코파일럿 옵션의 어시스턴트 이름을 설정합니다. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument)(PdfDocument) | 이미지 설명 코파일럿 옵션의 문서 컬렉션에 PDF 문서를 추가합니다. |
| [WithDocument](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocument/#withdocument_1)(string) | 이미지 설명 코파일럿 옵션의 문서 컬렉션에 문서 경로를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments)(DocumentCollection) | 이미지 설명 코파일럿 옵션의 문서 컬렉션을 설정합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_1)(List&lt;PdfDocument&gt;) | 이미지 설명 코파일럿 옵션의 문서 컬렉션에 여러 PDF 문서를 추가합니다. |
| [WithDocuments](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withdocuments/#withdocuments_2)(List&lt;string&gt;) | 이미지 설명 코파일럿 옵션의 문서 컬렉션에 여러 문서 경로를 추가합니다. |
| [WithImageDescriptionPrompt](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedescriptionprompt/)(string) | 이미지 설명 코파일럿 옵션의 프롬프트를 설정합니다. |
| [WithImageDetail](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withimagedetail/)(string) | 이미지 세부 수준을 설정합니다. |
| [WithInstructions](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withinstructions/)(string) | 이미지 설명 코파일럿 옵션의 지침을 설정합니다. |
| [WithMaxCompletionTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxcompletiontokens/)(int?) | 이미지 설명 코파일럿 옵션의 최대 완료 토큰을 설정합니다. |
| [WithMaxPromptTokens](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmaxprompttokens/)(int?) | 이미지 설명 코파일럿 옵션의 최대 프롬프트 토큰을 설정합니다. |
| [WithModel](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withmodel/)(string) | 이미지 설명 코파일럿 옵션의 모델을 설정합니다. |
| [WithTemperature](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtemperature/)(double?) | 이미지 설명 코파일럿 옵션의 온도를 설정합니다. |
| [WithTopP](../../aspose.pdf.ai/openaiimagedescriptioncopilotoptions/withtopp/)(double?) | 이미지 설명 코파일럿 옵션의 top P 값을 설정합니다. |

### 참조

* class [OpenAIAssistantCopilotOptionsBase](../openaiassistantcopilotoptionsbase/)
* interface [IImageDescriptionCopilotOptions&lt;TOptions&gt;](../iimagedescriptioncopilotoptions-1/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)