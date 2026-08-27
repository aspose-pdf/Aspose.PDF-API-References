---
title: "클래스 Graph"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Drawing.Graph 클래스. 그래프 및 그래픽 생성기 단락을 나타냅니다"
type: docs
weight: 4060
url: /ko/net/aspose.pdf.drawing/graph/
---
## Graph class

그래프 - 그래픽 생성기 단락을 나타냅니다.

```csharp
public sealed class Graph : BaseParagraph
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Graph](graph/#constructor)(double, double) | `Graph` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | 테두리를 가져오거나 설정합니다. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | `[`GraphInfo`](./graphinfo/)` 객체를 가져오거나 설정합니다. 이 객체는 색상, 선 너비 등과 같은 그래프 정보를 나타냅니다. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | 그래프 높이를 나타내는 부동 소수점 값을 가져오거나 설정합니다. 단위는 포인트입니다. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 단락의 수평 정렬을 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | 단락을 처리한 후 현재 위치를 변경하는지 여부를 가져오거나 설정합니다. (기본값 true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 가져오거나 설정합니다. 이 단락이 다음 열에 배치될지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 가져오거나 설정합니다. 단락이 인라인인지 여부입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 가져오거나 설정합니다. 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 가져오거나 설정합니다. 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | 표의 왼쪽 좌표를 가져오거나 설정합니다. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다. (pdf 생성용) |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | 그래프에 있는 모든 도형을 나타내는 [`Shapes`](./shapes/) 컬렉션을 가져오거나 설정합니다. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | 그래프의 제목을 나타내는 문자열 값을 가져오거나 설정합니다. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | 표의 상단 좌표를 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | 그래프 너비를 나타내는 부동 소수점 값을 가져오거나 설정합니다. 단위는 포인트입니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z 순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. ZIndex가 음수인 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | 그래프를 복제합니다. |

### 또 보기

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)


