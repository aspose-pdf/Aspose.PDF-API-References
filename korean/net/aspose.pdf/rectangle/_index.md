---
title: "Rectangle 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Rectangle 클래스. 사각형을 나타내는 클래스"
type: docs
weight: 9900
url: /ko/net/aspose.pdf/rectangle/
---
## Rectangle class

사각형을 나타내는 클래스입니다.

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
| static [Empty](../../aspose.pdf/rectangle/empty/) { get; } | 빈 Rectangle |
| static [Trivial](../../aspose.pdf/rectangle/trivial/) { get; } | 위치와 크기가 0인 사소한 Rectangle를 초기화합니다. |
| [Height](../../aspose.pdf/rectangle/height/) { get; } | Rectangle의 높이. |
| [IsEmpty](../../aspose.pdf/rectangle/isempty/) { get; } | Rectangle가 비었는지 확인합니다. |
| [IsPoint](../../aspose.pdf/rectangle/ispoint/) { get; } | Rectangle가 점인지 확인합니다(예: LLX가 URX와 같고 LLY가 URY와 같은 경우). |
| [IsTrivial](../../aspose.pdf/rectangle/istrivial/) { get; } | Rectangle가 사소한지 확인합니다(예: 크기와 위치가 0인 경우). |
| [LLX](../../aspose.pdf/rectangle/llx/) { get; set; } | 왼쪽 아래 모서리의 X 좌표. |
| [LLY](../../aspose.pdf/rectangle/lly/) { get; set; } | 왼쪽 아래 모서리의 Y 좌표. |
| [URX](../../aspose.pdf/rectangle/urx/) { get; set; } | 오른쪽 위 모서리의 X 좌표. |
| [URY](../../aspose.pdf/rectangle/ury/) { get; set; } | 오른쪽 위 모서리의 Y 좌표. |
| [Width](../../aspose.pdf/rectangle/width/) { get; } | Rectangle의 너비. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect)(Rectangle) | 주어진 System.Drawing.Rectangle 인스턴스로부터 새로운 Rectangle를 초기화합니다. |
| static [FromRect](../../aspose.pdf/rectangle/fromrect/#fromrect_1)(RectangleF) | 주어진 System.Drawing.Rectangle 인스턴스로부터 새로운 Rectangle를 초기화합니다. |
| static [Parse](../../aspose.pdf/rectangle/parse/)(string) | 문자열을 파싱하여 그 안에서 Rectangle 구성 요소인 llx, lly, urx, ury를 추출합니다. |
| [Center](../../aspose.pdf/rectangle/center/)() | Returncs Rectangle 중심의 좌표를 반환합니다. |
| [Clone](../../aspose.pdf/rectangle/clone/)() | Rectangle 객체를 복제합니다. |
| [Contains](../../aspose.pdf/rectangle/contains/)(Point, bool) | 주어진 점이 Rectangle 내부에 있는지 판단합니다. |
| [ContainsLine](../../aspose.pdf/rectangle/containsline/)(double, double, double, double) | Rectangle가 두 점으로 표현된 선을 포함하는지 판단합니다. |
| [ContainsPoint](../../aspose.pdf/rectangle/containspoint/)(double, double) | 주어진 점이 Rectangle 내부에 포함되는지 판단합니다. |
| [Equals](../../aspose.pdf/rectangle/equals/#equals)(Rectangle) | Rectangle들이 동일한지 확인합니다(예: 위치와 크기가 같은 경우). |
| [Intersect](../../aspose.pdf/rectangle/intersect/)(Rectangle) | 두 Rectangle가 교차합니다. |
| [IsIntersect](../../aspose.pdf/rectangle/isintersect/)(Rectangle) | 이 Rectangle가 다른 Rectangle와 교차하는지 판단합니다. |
| [Join](../../aspose.pdf/rectangle/join/)(Rectangle) | Rectangle들을 결합합니다. |
| [MoveBy](../../aspose.pdf/rectangle/moveby/)(double, double) | 지정된 델타만큼 Rectangle를 이동합니다. |
| [NearEquals](../../aspose.pdf/rectangle/nearequals/)(Rectangle, double) | Rectangle들이 거의 동일한지 확인합니다(예: 델타 범위 내에서 위치와 크기가 거의 같은 경우). |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate_1)(int) | 지정된 각도로 사각형을 회전합니다. |
| [Rotate](../../aspose.pdf/rectangle/rotate/#rotate)(Rotation) | 지정된 각도로 사각형을 회전합니다. |
| [ToPoints](../../aspose.pdf/rectangle/topoints/)() | 사각형을 점 배열("QuadPoints")로 변환합니다. |
| [ToRect](../../aspose.pdf/rectangle/torect/)() | 사각형을 System.Drawing.Rectangle 인스턴스로 변환합니다. 부동 소수점 위치와 크기는 잘립니다. |
| override [ToString](../../aspose.pdf/rectangle/tostring/)() | 사각형의 문자열 표현을 가져옵니다. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


