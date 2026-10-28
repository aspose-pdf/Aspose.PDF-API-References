---
title: "Class XYZExplicitDestination"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations.XYZExplicitDestination class. 왼쪽 위 좌표가 창의 왼쪽 위 모서리에 위치하고 페이지 내용이 줌 팩터에 의해 확대된 명시적 목적지를 나타냅니다. left, top 또는 zoom 매개변수 중 하나에 null 값을 지정하면 해당 매개변수의 현재 값이 변경되지 않고 유지됩니다. 줌 값이 0인 경우는 null 값과 동일한 의미를 가집니다."
type: docs
weight: 2830
url: /ko/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## XYZExplicitDestination class

명시적 목적지를 나타내며, 페이지를 좌표 (left, top) 로 창의 왼쪽 상단에 배치하고 페이지 내용을 zoom 비율로 확대하여 표시합니다. left, top 또는 zoom 매개변수 중 어느 하나가 null 값이면 해당 매개변수의 현재 값이 변경되지 않고 유지됩니다. zoom 값이 0인 경우는 null 값과 동일한 의미입니다.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | 원격 명시적 목적지를 생성합니다. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | 로컬 명시적 목적지를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | 창의 왼쪽 위 모서리의 왼쪽 수평 좌표를 가져옵니다. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | 목적지 페이지 객체를 가져옵니다. |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | 목적지 페이지 번호를 가져옵니다. |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | 창의 왼쪽 위 모서리의 위쪽 수직 좌표를 가져옵니다. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | 줌 팩터를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | 필요한 경우 페이지 회전을 고려하여 페이지의 지정된 위치에 목적지를 생성합니다. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | 지정된 페이지에 목적지를 생성합니다. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | 지정된 페이지의 왼쪽 위 모서리에 목적지를 생성합니다. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | 객체 상태를 문자열 값으로 변환합니다. 예: "1 XYZ 100 200 3". |

## 예제

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### 또 보기

* class [ExplicitDestination](../explicitdestination/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


