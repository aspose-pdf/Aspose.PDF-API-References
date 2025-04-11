---
title: Class Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Matrix3D 클래스. 클래스는 변환 행렬을 나타냅니다.
type: docs
weight: 6930
url: /ko/net/aspose.pdf/matrix3d/
---
## Matrix3D 클래스

클래스는 변환 행렬을 나타냅니다.

```csharp
public sealed class Matrix3D
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Matrix3D](matrix3d/#constructor)() | 생성자는 표준 1 대 1 행렬을 생성합니다: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] |
| [Matrix3D](matrix3d/#constructor_3)(double[]) | 생성자는 다음 배열 표현을 가진 행렬을 허용합니다: [ A B C D E F G H I Tx Ty Tz] |
| [Matrix3D](matrix3d/#constructor_1)(Matrix3D) | 생성자는 복사본을 만들기 위해 행렬을 허용합니다. |
| [Matrix3D](matrix3d/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double) | 지정된 계수로 변환 행렬을 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [A](../../aspose.pdf/matrix3d/a/) { get; set; } | 변환 행렬의 A 구성원입니다. |
| [B](../../aspose.pdf/matrix3d/b/) { get; set; } | 변환 행렬의 B 구성원입니다. |
| [C](../../aspose.pdf/matrix3d/c/) { get; set; } | 변환 행렬의 C 구성원입니다. |
| [D](../../aspose.pdf/matrix3d/d/) { get; set; } | 변환 행렬의 D 구성원입니다. |
| [E](../../aspose.pdf/matrix3d/e/) { get; set; } | 변환 행렬의 E 구성원입니다. |
| [F](../../aspose.pdf/matrix3d/f/) { get; set; } | 변환 행렬의 F 구성원입니다. |
| [G](../../aspose.pdf/matrix3d/g/) { get; set; } | 변환 행렬의 G 구성원입니다. |
| [H](../../aspose.pdf/matrix3d/h/) { get; set; } | 변환 행렬의 H 구성원입니다. |
| [I](../../aspose.pdf/matrix3d/i/) { get; set; } | 변환 행렬의 I 구성원입니다. |
| [Tx](../../aspose.pdf/matrix3d/tx/) { get; set; } | 변환 행렬의 Tx 구성원입니다. |
| [Ty](../../aspose.pdf/matrix3d/ty/) { get; set; } | 변환 행렬의 Ty 구성원입니다. |
| [Tz](../../aspose.pdf/matrix3d/tz/) { get; set; } | 변환 행렬의 Tz 구성원입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf/matrix3d/add/)(Matrix3D) | 행렬을 다른 행렬에 추가합니다. |
| override [Equals](../../aspose.pdf/matrix3d/equals/)(object) | 행렬을 다른 객체와 비교합니다. |
| override [GetHashCode](../../aspose.pdf/matrix3d/gethashcode/)() | 객체의 해시 코드입니다. |
| override [ToString](../../aspose.pdf/matrix3d/tostring/)() | 행렬의 텍스트 표현을 반환합니다. |
| static [GetAngle](../../aspose.pdf/matrix3d/getangle/)(Rotation) | 회전을 각도로 변환합니다 (도) |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)