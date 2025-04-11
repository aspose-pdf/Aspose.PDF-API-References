---
title: Class Graph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Drawing.Graph 클래스. 그래프 그래픽 생성기 단락을 나타냅니다.
type: docs
weight: 3940
url: /ko/net/aspose.pdf.drawing/graph/
---
## 그래프 클래스

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
| [Border](../../aspose.pdf.drawing/graph/border/) { get; set; } | 테두기를 가져오거나 설정합니다. |
| [GraphInfo](../../aspose.pdf.drawing/graph/graphinfo/) { get; set; } | 색상, 선 너비 등과 같은 그래프 정보를 나타내는 [`GraphInfo`](./graphinfo/) 객체를 가져오거나 설정합니다. |
| [Height](../../aspose.pdf.drawing/graph/height/) { get; set; } | 그래프 높이를 나타내는 부동 값을 가져오거나 설정합니다. 단위는 포인트입니다. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 단락의 수평 정렬을 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( PDF 생성기용). |
| [IsChangePosition](../../aspose.pdf.drawing/graph/ischangeposition/) { get; set; } | 단락 처리 후 현재 위치 변경 여부를 가져오거나 설정합니다.(기본값 true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지 여부를 나타내는 부울 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 부울 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지 여부를 나타내는 부울 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [Left](../../aspose.pdf.drawing/graph/left/) { get; set; } | 테이블의 왼쪽 좌표를 가져오거나 설정합니다. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다(PDF 생성용). |
| [Shapes](../../aspose.pdf.drawing/graph/shapes/) { get; set; } | 그래프의 모든 도형을 나타내는 [`Shapes`](./shapes/) 컬렉션을 가져오거나 설정합니다. |
| [Title](../../aspose.pdf.drawing/graph/title/) { get; set; } | 그래프의 제목을 나타내는 문자열 값을 가져오거나 설정합니다. |
| [Top](../../aspose.pdf.drawing/graph/top/) { get; set; } | 테이블의 위쪽 좌표를 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| [Width](../../aspose.pdf.drawing/graph/width/) { get; set; } | 그래프 너비를 나타내는 부동 값을 가져오거나 설정합니다. 단위는 포인트입니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf.drawing/graph/clone/)() | 그래프를 복제합니다. |

### 참조

* 클래스 [BaseParagraph](../../aspose.pdf/baseparagraph/)
* 네임스페이스 [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* 어셈블리 [Aspose.PDF](../../)