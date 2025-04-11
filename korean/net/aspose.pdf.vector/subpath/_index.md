---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SubPath 클래스. 페이지의 벡터 그래픽 객체를 나타냅니다. 기본적으로 벡터 그래픽 객체는 두 그룹의 SubPaths로 표현됩니다. 그 중 하나는 선과 곡선의 집합으로 표현됩니다. 다른 하나는 사각형으로 표현되며 때때로 혼동될 수 있습니다. 일반적으로 색상이 있는 직사각형 영역이지만, 이 직사각형은 페이지의 시작 부분에 배치되어 페이지의 전체 공간을 흰색으로 정의하는 경우가 많습니다. 따라서 SubPath를 얻지만 시각적으로는 페이지의 텍스트만 볼 수 있습니다.
type: docs
weight: 11220
url: /ko/net/aspose.pdf.vector/subpath/
---
## SubPath class

페이지의 벡터 그래픽 객체를 나타냅니다. 기본적으로 벡터 그래픽 객체는 두 그룹의 SubPaths로 표현됩니다. 그 중 하나는 선과 곡선의 집합으로 표현됩니다. 다른 하나는 사각형으로 표현되며 때때로 혼동될 수 있습니다. 일반적으로 색상이 있는 직사각형 영역이지만, 이 직사각형은 페이지의 시작 부분에 배치되어 페이지의 전체 공간을 흰색으로 정의하는 경우가 많습니다. 따라서 SubPath를 얻지만 시각적으로는 페이지의 텍스트만 볼 수 있습니다.

```csharp
public sealed class SubPath : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 그래픽 요소 행렬을 가져옵니다. 행렬은 요소가 생성될 때 설정됩니다. SetPosition()이 호출되면 변경됩니다. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 요소를 나타내는 연산자 컬렉션을 가져옵니다. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 요소가 위치한 현재 [`XFormPlacement`](../xformplacement/)를 가져옵니다. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | 현재 좌표 공간에서 위치를 가져오거나 설정합니다. [`Parent`](../graphicelement/parent/)가 !:null이 아니면 요소는 xForm 좌표 공간을 가집니다. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 그래픽 요소가 추출된 페이지를 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | 현재 요소를 페이지에 추가합니다. 추가할 요소가 많으면 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)를 사용하는 것이 좋습니다. |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) 클래스에서 사용하는 모든 리소스를 해제합니다. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 현재 요소를 페이지에서 제거합니다. 제거할 요소가 많으면 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)를 사용하는 것이 좋습니다. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 요소를 단일 SVG 이미지로 변환합니다. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 요소를 단일 SVG 이미지 파일로 변환합니다. |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)