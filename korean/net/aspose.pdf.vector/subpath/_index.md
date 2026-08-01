---
title: "클래스 SubPath"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Vector.SubPath 클래스. 페이지상의 벡터 그래픽 객체를 나타냅니다. 기본적으로 벡터 그래픽 객체는 두 개의 SubPath 그룹으로 표현됩니다. 그 중 하나는 선과 곡선 집합으로 나타내며, 다른 하나는 사각형으로 표시되어 때때로 혼동될 수 있습니다. 일반적으로 색상이 있는 사각형 영역이며, 이 사각형은 페이지 시작 부분에 배치되어 페이지 전체 공간을 흰색으로 정의하는 경우가 많습니다. 따라서 SubPath를 얻지만 시각적으로는 페이지의 텍스트만 보이게 됩니다."
type: docs
weight: 11410
url: /ko/net/aspose.pdf.vector/subpath/
---
## SubPath class

페이지에 있는 벡터 그래픽 객체를 나타냅니다. 기본적으로 벡터 그래픽 객체는 두 그룹의 SubPath로 표현됩니다. 그 중 하나는 선과 곡선 집합으로 표현되고, 다른 하나는 사각형으로 표시되어 때때로 혼동될 수 있습니다. 일반적으로 색상이 있는 사각형 영역이지만, 이 사각형이 페이지 시작 부분에 배치되어 페이지 전체 공간을 흰색으로 정의하는 경우가 많습니다. 따라서 SubPath를 얻지만, 시각적으로는 페이지의 텍스트만 보입니다.

```csharp
public sealed class SubPath : GraphicElement
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 그래픽 요소 매트릭스를 가져옵니다. 매트릭스는 요소가 생성될 때 설정됩니다. SetPosition()이 호출될 때 변경됩니다. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 요소를 나타내는 연산자 컬렉션을 가져옵니다. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 요소가 위치한 현재 [`XFormPlacement`](../xformplacement/)을 가져옵니다. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | 현재 좌표 공간에서 위치를 가져오거나 설정합니다. 만약 [`Parent`](../graphicelement/parent/)가 !:null이면 요소는 xForm 좌표 공간을 가집니다. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 그래픽 요소가 추출된 Page를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | 현재 요소를 Page에 추가합니다. 추가할 요소가 많다면 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)를 사용하는 것이 좋습니다. |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) 클래스가 사용하는 모든 리소스를 해제합니다. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 현재 요소를 Page에서 제거합니다. 제거할 요소가 많다면 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)를 사용하는 것이 좋습니다. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 요소를 단일 SVG 이미지로 변환합니다. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 요소를 단일 SVG 이미지 파일로 변환합니다. |

### 또 보기

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


