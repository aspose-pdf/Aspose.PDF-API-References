---
title: "클래스 Heading"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Heading 클래스. 헤딩을 나타냅니다."
type: docs
weight: 5590
url: /ko/net/aspose.pdf/heading/
---
## Heading class

머리글을 나타냅니다.

```csharp
public sealed class Heading : TextFragment
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Heading](heading/)(int) | Cell 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | 텍스트 위치를 가져옵니다. 텍스트는 [`TextFragment`](../../aspose.pdf.text/textfragment/) 객체로 표시됩니다. Position 구조의 YIndent는 텍스트 조각의 기준선 좌표를 나타냅니다. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | 대상 페이지를 가져옵니다. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 단락 끝 주석을 가져오거나 설정합니다.(pdf 생성 전용) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 단락 각주를 가져오거나 설정합니다.(pdf 생성 전용) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | TextFragment를 포함하는 폼 객체를 가져옵니다 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | 텍스트 조각의 수평 정렬을 가져오거나 설정합니다. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | 조각 하이퍼링크를 설정합니다 |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | 헤딩이 자동으로 번호 매겨져야 하는지를 가져옵니다. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 가져오거나 설정합니다. 이 단락이 다음 열에 배치될지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 가져오거나 설정합니다. 단락이 인라인인지 여부입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | 헤딩이 목차 목록에 포함되어야 하는지를 가져옵니다. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 가져오거나 설정합니다. 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 가져오거나 설정합니다. 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | 레벨을 가져옵니다. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다. (pdf 생성용) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | TextFragment를 포함하는 페이지를 가져옵니다 |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | 텍스트 위치를 가져오거나 설정합니다. 텍스트는 [`TextFragment`](../../aspose.pdf.text/textfragment/) 객체로 표시됩니다. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | TextFragment의 사각형을 가져옵니다 |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | 텍스트 교체 옵션을 가져옵니다. 옵션은 조각 텍스트가 더 짧거나 길게 교체될 때의 동작을 정의합니다. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 현재 [`TextFragment`](../../aspose.pdf.text/textfragment/)에 대한 텍스트 세그먼트를 가져옵니다. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | 헤딩 시작 번호를 가져옵니다. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | 스타일을 가져오거나 설정합니다. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) 객체가 나타내는 문자열 텍스트 객체를 가져오거나 설정합니다. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | 텍스트 편집 옵션을 가져오거나 설정합니다. 옵션은 요청된 기호를 글꼴로 쓸 수 없을 때의 특수 동작을 정의합니다. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | [`TextFragment`](../../aspose.pdf.text/textfragment/) 객체가 나타내는 텍스트에 대한 텍스트 상태를 가져오거나 설정합니다. |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | 이 헤딩을 포함하는 페이지를 가져옵니다. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | 이 헤딩들의 상단 Y 좌표를 가져옵니다. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | 사용자 레이블을 가져오거나 설정합니다. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | 텍스트 조각의 수직 정렬을 가져오거나 설정합니다. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | 이 단락의 줄 바꿈 횟수를 가져오거나 설정합니다.(pdf 생성 전용) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z 순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. ZIndex가 음수인 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | 제목을 복제합니다. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | 모든 세그먼트를 포함하여 제목을 복제합니다. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | `[`TextSegment`](../../aspose.pdf.text/textsegment/)(s)`을 가져와 지정된 부분의 [`TextFragment`](../../aspose.pdf.text/textfragment/) 텍스트를 나타냅니다. |

### 또 보기

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


