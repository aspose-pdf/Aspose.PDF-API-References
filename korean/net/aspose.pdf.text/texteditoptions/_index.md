---
title: Class TextEditOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextEditOptions 클래스. 텍스트 편집 작업의 옵션을 설명합니다.
type: docs
weight: 10820
url: /ko/net/aspose.pdf.text/texteditoptions/
---
## TextEditOptions 클래스

텍스트 편집 작업의 옵션을 설명합니다.

```csharp
public sealed class TextEditOptions : TextOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextEditOptions](texteditoptions/#constructor)(bool) | 지정된 언어 변환 권한에 대한 `TextEditOptions` 객체의 새 인스턴스를 초기화합니다. |
| [TextEditOptions](texteditoptions/#constructor_1)(FontReplace) | 지정된 글꼴 교체 동작 모드에 대한 `TextEditOptions` 객체의 새 인스턴스를 초기화합니다. |
| [TextEditOptions](texteditoptions/#constructor_2)(LanguageTransformation) | 지정된 언어 변환 동작 모드에 대한 `TextEditOptions` 객체의 새 인스턴스를 초기화합니다. |
| [TextEditOptions](texteditoptions/#constructor_3)(NoCharacterAction) | 지정된 문자 없음 동작 모드에 대한 `TextEditOptions` 객체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllowLanguageTransformation](../../aspose.pdf.text/texteditoptions/allowlanguagetransformation/) { get; set; } | 텍스트 추가 또는 편집 중 언어 변환 사용을 허용하는 값을 가져오거나 설정합니다. true - 필요할 경우 언어 변환이 적용됩니다(기본값). false - 언어 변환이 적용되지 않습니다. |
| [ClippingPathsProcessing](../../aspose.pdf.text/texteditoptions/clippingpathsprocessing/) { get; set; } | 편집된 텍스트의 클리핑 경로 처리 모드를 가져옵니다. |
| [FontReplaceBehavior](../../aspose.pdf.text/texteditoptions/fontreplacebehavior/) { get; set; } | 글꼴 교체 시나리오에 대한 동작을 정의하는 모드를 가져옵니다. |
| [LanguageTransformationBehavior](../../aspose.pdf.text/texteditoptions/languagetransformationbehavior/) { get; set; } | 언어 변환 시나리오에 대한 동작을 정의하는 모드를 가져옵니다. |
| [NoCharacterBehavior](../../aspose.pdf.text/texteditoptions/nocharacterbehavior/) { get; set; } | 요청된 문자가 포함되지 않은 경우의 동작을 정의하는 모드를 가져오거나 설정합니다. |
| [ReplacementFont](../../aspose.pdf.text/texteditoptions/replacementfont/) { get; set; } | 사용자의 글꼴에 필요한 문자가 포함되지 않은 경우 교체에 사용되는 글꼴을 가져오거나 설정합니다. |
| [ToAttemptGetUnderlineFromSource](../../aspose.pdf.text/texteditoptions/toattemptgetunderlinefromsource/) { get; set; } | 원본 문서 페이지에서 텍스트 밑줄 검색을 허용하는 값을 가져오거나 설정합니다. (더 이상 사용되지 않음) 대신 TextSearchOptions.SearchForTextRelatedGraphics를 사용하십시오. |

### 참조

* 클래스 [TextOptions](../textoptions/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)