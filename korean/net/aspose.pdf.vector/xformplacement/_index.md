---
title: "클래스 XFormPlacement"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Vector.XFormPlacement 클래스. XForm 배치를 나타냅니다. XForm이 Page에 한 번 이상 표시되는 경우, 이 XForm과 연결된 모든 XformPlacements는 공통 그래픽 요소를 가지지만 그래픽 상태는 다릅니다."
type: docs
weight: 11450
url: /ko/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

XForm 배치를 나타냅니다. XForm이 페이지에 한 번 이상 표시되는 경우, 이 XForm과 연결된 모든 XformPlacements는 공통 그래픽 요소를 가지지만 그래픽 상태는 다릅니다.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | 이 XForm 내부의 그래픽 요소를 가져옵니다. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | 그래픽 요소 매트릭스를 가져옵니다. 매트릭스는 요소가 생성될 때 설정됩니다. SetPosition()이 호출될 때 변경됩니다. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | XForm의 이름을 가져옵니다. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | 요소를 나타내는 연산자 컬렉션을 가져옵니다. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | 요소가 위치한 현재 `XFormPlacement`를 가져옵니다. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | 그래픽 요소가 추출된 Page를 가져옵니다. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | 이 XFormPlacement와 연결된 XForm을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | 현재 요소를 Page에 추가합니다. 추가할 요소가 많다면 [`AddGraphics`](../../aspose.pdf/page/addgraphics/)를 사용하는 것이 좋습니다. |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | [`GraphicElement`](../graphicelement/) 클래스가 사용하는 모든 리소스를 해제합니다. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | 현재 요소를 Page에서 제거합니다. 제거할 요소가 많다면 [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/)를 사용하는 것이 좋습니다. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | 요소를 단일 SVG 이미지로 변환합니다. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | 요소를 단일 SVG 이미지 파일로 변환합니다. |

### 또 보기

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


