---
title: Class Rectangle
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Rectangle 클래스. 클래스는 사각형을 나타냅니다.
type: docs
weight: 9750
url: /ko/net/aspose.pdf/rectangle/
---
## Rectangle 클래스

클래스는 사각형을 나타냅니다.

```csharp
public sealed class Rectangle : ICloneable
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Rectangle](rectangle/)(double, double, double, double, bool) | Rectangle의 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | 빈 사각형 |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | 위치와 크기가 0인 사각형을 초기화합니다. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | 사각형의 높이. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | 사각형이 비어 있는지 확인합니다. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | 사각형이 점인지 확인합니다. 즉, LLX가 URX와 같고 LLY가 URY와 같습니다. |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | 사각형이 사소한지 확인합니다. 즉, 크기와 위치가 0입니다. |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | 왼쪽 아래 모서리의 X 좌표. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | 왼쪽 아래 모서리의 Y 좌표. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | 오른쪽 위 모서리의 X 좌표. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | 오른쪽 위 모서리의 Y 좌표. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | 사각형의 너비. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | 주어진 System.Drawing.Rectangle 인스턴스에서 새 사각형을 초기화합니다. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | 주어진 System.Drawing.Rectangle 인스턴스에서 새 사각형을 초기화합니다. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | 문자열을 파싱하고 사각형 구성 요소 llx, lly, urx, ury를 추출하려고 시도합니다. |
| [Center](../../aspose.pdf/rectangle/center/)() | 사각형의 중심 좌표를 반환합니다. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Rectangle 객체를 복제합니다. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | 주어진 점이 사각형 내부에 있는지 여부를 결정합니다. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | 사각형이 두 점으로 표현된 선을 포함하는지 여부를 결정합니다. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | 주어진 점이 사각형 내에 포함되는지 여부를 결정합니다. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | 사각형이 동일한지 확인합니다. 즉, 동일한 위치와 크기를 가집니다. |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | 사각형을 교차합니다. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | 이 사각형이 다른 사각형과 교차하는지 여부를 결정합니다. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | 사각형을 결합합니다. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | 지정된 델타만큼 사각형을 이동합니다. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | 사각형이 거의 동일한지 확인합니다. 즉, 거의 동일한 (델타까지) 위치와 크기를 가집니다. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | 지정된 각도만큼 사각형을 회전합니다. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | 지정된 각도만큼 사각형을 회전합니다. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | 사각형을 점 배열("QuadPoints")로 변환합니다. |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | 사각형을 System.Drawing.Rectangle 인스턴스로 변환합니다. 부동 소수점 위치와 크기는 잘립니다. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | 사각형의 문자열 표현을 가져옵니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)