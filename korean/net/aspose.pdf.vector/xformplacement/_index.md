---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.XFormPlacement 클래스. XForm 배치를 나타냅니다. XForm이 페이지에 1회 이상 표시되면 이 XForm과 관련된 모든 XformPlacement는 공통 그래픽 요소를 가지지만 서로 다른 그래픽 상태를 가집니다.
type: docs
weight: 11260
url: /ko/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

XForm 배치를 나타냅니다. XForm이 페이지에 1회 이상 표시되면 이 XForm과 관련된 모든 XformPlacement는 공통 그래픽 요소를 가지지만 서로 다른 그래픽 상태를 가집니다.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | 이 XForm 내부의 그래픽 요소를 가져옵니다. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 그래픽 요소 행렬을 가져옵니다. 행렬은 요소가 생성될 때 설정됩니다. SetPosition()이 호출되면 변경됩니다. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | XForm의 이름을 가져옵니다. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 요소를 나타내는 연산자 컬렉션을 가져옵니다. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 요소가 위치한 현재 `XFormPlacement`를 가져옵니다. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 그래픽 요소가 추출된 페이지를 가져옵니다. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | 이 XFormPlacement와 관련된 XForm을 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | 현재 요소를 페이지에 추가합니다. 추가할 요소가 많으면 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)를 사용하는 것이 좋습니다. |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) 클래스에서 사용하는 모든 리소스를 해제합니다. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 현재 요소를 페이지에서 제거합니다. 제거할 요소가 많으면 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)를 사용하는 것이 좋습니다. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 요소를 단일 SVG 이미지로 변환합니다. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 요소를 단일 SVG 이미지 파일로 변환합니다. |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)