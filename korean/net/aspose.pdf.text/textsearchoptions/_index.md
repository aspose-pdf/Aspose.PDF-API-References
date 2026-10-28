---
title: "클래스 TextSearchOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Text.TextSearchOptions 클래스. 텍스트 검색 옵션을 나타냅니다."
type: docs
weight: 11230
url: /ko/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

텍스트 검색 옵션을 나타냅니다.

```csharp
public sealed class TextSearchOptions : TextOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | `TextSearchOptions` 객체의 새 인스턴스를 초기화합니다. 정규식 사용 모드를 지정합니다. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | `TextSearchOptions` 객체의 새 인스턴스를 초기화합니다. 검색된 텍스트를 제한하는 사각형을 지정합니다. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | `TextSearchOptions` 객체의 새 인스턴스를 초기화합니다. 검색된 텍스트를 제한하는 사각형과 정규식 사용 모드를 지정합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | 텍스트(조각) 흡수기가 글꼴 부재와 관련된 오류를 무시하도록 표시를 가져오거나 설정합니다. true - 글꼴 부재 오류가 무시됨을 의미합니다. 잘못된 리소스를 참조하는 텍스트 세그먼트는 처리 중에 건너뛰어집니다. false (기본값) - 글꼴 부재 오류가 발생하면 예외를 발생시켜 처리를 종료합니다. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | 검색 중에 일반 텍스트의 그림자를 나타내는 텍스트 조각을 무시하도록 표시를 가져오거나 설정합니다. true - 그림자 텍스트가 검색되지 않음을 의미합니다(텍스트 검색이 근접 위치에서 중복 조각을 반환할 경우 시도해 보세요). false - 그림자 텍스트가 일반 텍스트와 함께 검색됨을 의미합니다(기본값). |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | 정규식이 사용되는지를 표시를 가져오거나 설정합니다. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | 텍스트가 page 경계 내에서 검색되는지를 표시를 가져오거나 설정합니다. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | 텍스트 추출(디코딩) 오류가 텍스트(조각) 흡수기에 기록되도록 표시를 가져오거나 설정합니다. true - 텍스트 추출(디코딩) 오류가 기록됨을 의미합니다. 성능이 저하될 수 있습니다. false (기본값) - 오류가 기록되지 않습니다. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | 검색된 텍스트를 제한하는 사각형을 가져오거나 설정합니다. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | 텍스트 검색 중에 텍스트와 관련된 그래픽(밑줄, 배경 등)을 검색하도록 허용하는 값을 가져오거나 설정합니다. true - 텍스트와 관련된 그래픽 검색이 수행됩니다(기본값). false - 원본 document에 존재할 수 있는 그래픽 요소가 무시됩니다. 성능 문제가 있거나 밑줄, 배경, 클리핑을 처리할 필요가 없을 경우 이 값을 설정하십시오. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Annotations에서 텍스트를 검색하도록 허용하는 값을 가져오거나 설정합니다. true - Annotations에서 텍스트가 검색됩니다. false - Annotations의 텍스트는 TextFragmentAbsorber에 의해 파싱되지 않습니다. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | page에서 텍스트와 관련된 그래픽(밑줄, 배경 등)의 검색을 지정된 요소 수로 제한하는 값을 가져오거나 설정합니다. 기본값은 250입니다. 성능 문제가 있을 경우 더 작은 값을 설정하고, 일부 그래픽 요소가 검색되지 않을 경우 더 큰 값을 시도하십시오. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | 텍스트를 글꼴 엔진 인코딩을 사용하여 검색하도록 표시를 가져오거나 설정합니다. true - 글꼴 엔진 인코딩이 사용됨을 의미합니다(문서의 인코딩이 불완전하여 텍스트 검색이 실패할 경우 시도해 보세요). false - document의 글꼴 인코딩이 사용됨을 의미합니다(기본값). |

### 또 보기

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


