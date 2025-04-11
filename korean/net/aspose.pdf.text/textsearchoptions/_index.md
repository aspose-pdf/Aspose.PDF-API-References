---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSearchOptions 클래스. 텍스트 검색 옵션을 나타냅니다.
type: docs
weight: 11040
url: /ko/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions 클래스

텍스트 검색 옵션을 나타냅니다.

```csharp
public sealed class TextSearchOptions : TextOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | `TextSearchOptions` 객체의 새 인스턴스를 초기화합니다. 정규 표현식 사용 모드를 지정합니다. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | `TextSearchOptions` 객체의 새 인스턴스를 초기화합니다. 검색할 텍스트를 한정하는 사각형을 지정합니다. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | `TextSearchOptions` 객체의 새 인스턴스를 초기화합니다. 검색할 텍스트를 한정하는 사각형과 정규 표현식 사용 모드를 지정합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | 글꼴이 없을 때 발생하는 오류를 텍스트(조각) 흡수기가 무시할 것인지 여부를 가져오거나 설정합니다. true - 글꼴이 없을 때 발생하는 오류를 무시합니다. 잘못된 리소스를 참조하는 텍스트 세그먼트는 처리 중에 건너뜁니다. false(기본값) - 글꼴 없음 오류가 발생하면 예외를 던져 처리 중단됩니다. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | 일반 텍스트의 그림자를 나타내는 텍스트 조각을 검색 중에 무시할 것인지 여부를 가져오거나 설정합니다. true - 그림자 텍스트가 발견되지 않습니다(텍스트 검색이 가까운 위치에서 중복된 조각을 반환하는 경우 시도해 보세요). false - 그림자 텍스트와 일반 텍스트가 모두 발견됩니다(기본값). |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | 정규 표현식이 사용되고 있는지 여부를 가져오거나 설정합니다. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | 텍스트가 페이지 경계 내에서 검색되는지 여부를 가져오거나 설정합니다. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | 텍스트 추출(디코딩) 오류가 텍스트(조각) 흡수기에 기록될 것인지 여부를 가져오거나 설정합니다. true - 텍스트 추출(디코딩) 오류가 기록됩니다. 성능이 저하될 수 있습니다. false(기본값) - 오류 기록이 없습니다. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | 검색할 텍스트를 한정하는 사각형을 가져오거나 설정합니다. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | 텍스트 검색 중 텍스트 관련 그래픽(밑줄, 배경 등)을 검색할 수 있는 값을 가져오거나 설정합니다. true - 텍스트 관련 그래픽 검색이 수행됩니다(기본값). false - 원본 문서에 존재할 수 있는 그래픽 요소는 무시됩니다. 성능 문제나 밑줄, 배경 또는 클리핑을 처리할 필요가 없는 경우 설정합니다. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | 주석에서 텍스트를 검색할 수 있는 값을 가져오거나 설정합니다. true - 주석에서 텍스트가 검색됩니다. false - 주석의 텍스트는 TextFragmentAbsorber에 의해 구문 분석되지 않습니다. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | 지정된 수의 요소에 대해 페이지에서 텍스트 관련 그래픽(밑줄, 배경 등)을 검색하는 것을 제한하는 값을 가져오거나 설정합니다. 기본값은 250입니다. 성능 문제의 경우 더 작은 값을 설정하고, 일부 그래픽 요소가 발견되지 않은 경우 더 큰 값을 시도해 보세요. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | 텍스트가 글꼴 엔진 인코딩을 사용하여 검색될 것인지 여부를 가져오거나 설정합니다. true - 글꼴 엔진 인코딩이 사용됩니다(문서의 불완전한 인코딩으로 인해 텍스트 검색이 실패하는 경우 시도해 보세요). false - 문서 글꼴 인코딩이 사용됩니다(기본값). |

### 참조

* 클래스 [TextOptions](../textoptions/)
* 네임스페이스 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../)