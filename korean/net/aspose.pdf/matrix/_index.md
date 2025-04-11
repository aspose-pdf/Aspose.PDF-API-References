---
title: Class Matrix
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix 클래스. 클래스는 변환 행렬을 나타냅니다.
type: docs
weight: 6920
url: /ko/net/aspose.pdf/matrix/
---
## 행렬 클래스

클래스는 변환 행렬을 나타냅니다.

```csharp
public sealed class Matrix
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Matrix](matrix/#constructor)() | 생성자는 표준 1 대 1 행렬을 생성합니다: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix](matrix/#constructor_3)(double[]) | 생성자는 다음 배열 표현을 가진 행렬을 허용합니다: [ A B C D E F ] |
| [Matrix](matrix/#constructor_4)(float[]) | 생성자는 다음 배열 표현을 가진 행렬을 허용합니다: [ A B C D E F ] |
| [Matrix](matrix/#constructor_1)(Matrix) | 생성자는 복사본을 만들기 위해 행렬을 허용합니다. |
| [Matrix](matrix/#constructor_2)(double, double, double, double, double, double) | 지정된 계수로 변환 행렬을 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [A](../../aspose.pdf/matrix/a/) { get; set; } | 변환 행렬의 A 구성원. |
| [B](../../aspose.pdf/matrix/b/) { get; set; } | 변환 행렬의 B 구성원. |
| [C](../../aspose.pdf/matrix/c/) { get; set; } | 변환 행렬의 C 구성원. |
| [D](../../aspose.pdf/matrix/d/) { get; set; } | 변환 행렬의 D 구성원. |
| [Data](../../aspose.pdf/matrix/data/) { get; } | 배열로서 행렬의 데이터를 가져옵니다. |
| [E](../../aspose.pdf/matrix/e/) { get; set; } | 변환 행렬의 E 구성원. |
| [Elements](../../aspose.pdf/matrix/elements/) { get; } | 행렬의 요소. |
| [F](../../aspose.pdf/matrix/f/) { get; set; } | 변환 행렬의 F 구성원. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation_1)(double) | 주어진 회전 각도에 대한 행렬을 생성합니다. |
| static [Rotation](../../aspose.pdf/matrix/rotation/#rotation)(Rotation) | 주어진 회전에 대한 행렬을 생성합니다. |
| static [Scale](../../aspose.pdf/matrix/scale/)(double, double, Matrix) | 주어진 행렬에 스케일링을 적용합니다. |
| static [Skew](../../aspose.pdf/matrix/skew/)(double, double) | 주어진 회전 각도에 대한 행렬을 생성합니다. |
| static [Translate](../../aspose.pdf/matrix/translate/)(double, double, Matrix) | 지정된 양만큼 x 및 y 방향으로 행렬을 변환합니다. |
| [Add](../../aspose.pdf/matrix/add/)(Matrix) | 다른 행렬에 행렬을 추가합니다. |
| override [Equals](../../aspose.pdf/matrix/equals/)(object) | 다른 객체와 행렬을 비교합니다. |
| [GetFlipMatrix](../../aspose.pdf/matrix/getflipmatrix/)() | 플리핑 행렬을 가져옵니다. |
| override [GetHashCode](../../aspose.pdf/matrix/gethashcode/)() | 객체의 해시 코드. |
| [Multiply](../../aspose.pdf/matrix/multiply/)(Matrix) | 행렬을 다른 행렬과 곱합니다. |
| [Reverse](../../aspose.pdf/matrix/reverse/)() | 역행렬을 계산합니다. |
| [Scale](../../aspose.pdf/matrix/scale/)(double, double, out double, out double) | 다음 공식을 사용하여 행렬로 x 및 y를 스케일합니다: x1 = A*x + C*y; y1 = B*x + D*y; |
| override [ToString](../../aspose.pdf/matrix/tostring/)() | 행렬의 텍스트 표현을 반환합니다. |
| [Transform](../../aspose.pdf/matrix/transform/#transform)(Point) | 이 행렬을 사용하여 점을 변환합니다. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_1)(Rectangle) | 사각형을 변환합니다. 각도가 90 * N도 아닐 경우 경계 사각형이 반환됩니다. |
| [Transform](../../aspose.pdf/matrix/transform/#transform_2)(double, double, out double, out double) | 이 행렬을 사용하여 좌표를 변환합니다. |
| [UnScale](../../aspose.pdf/matrix/unscale/)(double, double, out double, out double) | x1 및 y1을 다시 스케일하고 다음 공식을 사용하여 행렬 변환 이전의 x 및 y를 반환합니다: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [UnTransform](../../aspose.pdf/matrix/untransform/)(double, double, out double, out double) | x1 및 y1을 다시 변환하고 다음 공식을 사용하여 행렬 변환 이전의 x 및 y를 반환합니다: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |
| static [GetAngle](../../aspose.pdf/matrix/getangle/)(Rotation) | 회전을 각도(도)로 변환합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)