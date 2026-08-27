---
title: "Matrix3D 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Matrix3D 클래스. 변환 행렬을 나타내는 클래스입니다."
type: docs
weight: 7070
url: /ko/net/aspose.pdf/matrix3d/
---
## Matrix3D class

클래스는 변환 매트릭스를 나타냅니다.

```csharp
public sealed class Matrix3D
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Matrix3D](matrix3d/#constructor)() | 생성자는 표준 1 대 1 행렬을 생성합니다: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] |
| [Matrix3D](matrix3d/#constructor_3)(double[]) | 생성자는 다음 배열 표현을 사용하는 행렬을 허용합니다: [ A B C D E F G H I Tx Ty Tz] |
| [Matrix3D](matrix3d/#constructor_1)(Matrix3D) | 생성자는 복사를 만들기 위해 Matrix를 허용합니다 |
| [Matrix3D](matrix3d/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double) | 지정된 계수를 사용하여 변환 Matrix를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [A](../../aspose.pdf/matrix3d/a/) { get; set; } | A는 변환 Matrix의 구성원입니다. |
| [B](../../aspose.pdf/matrix3d/b/) { get; set; } | B는 변환 Matrix의 구성원입니다. |
| [C](../../aspose.pdf/matrix3d/c/) { get; set; } | C는 변환 Matrix의 구성원입니다. |
| [D](../../aspose.pdf/matrix3d/d/) { get; set; } | D는 변환 Matrix의 구성원입니다. |
| [E](../../aspose.pdf/matrix3d/e/) { get; set; } | E는 변환 Matrix의 구성원입니다. |
| [F](../../aspose.pdf/matrix3d/f/) { get; set; } | F는 변환 Matrix의 구성원입니다. |
| [G](../../aspose.pdf/matrix3d/g/) { get; set; } | 변환 행렬의 G 멤버. |
| [H](../../aspose.pdf/matrix3d/h/) { get; set; } | 변환 행렬의 H 멤버. |
| [I](../../aspose.pdf/matrix3d/i/) { get; set; } | 변환 행렬의 I 멤버. |
| [Tx](../../aspose.pdf/matrix3d/tx/) { get; set; } | 변환 행렬의 Tx 멤버. |
| [Ty](../../aspose.pdf/matrix3d/ty/) { get; set; } | 변환 행렬의 Ty 멤버. |
| [Tz](../../aspose.pdf/matrix3d/tz/) { get; set; } | 변환 행렬의 Tz 멤버. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf/matrix3d/add/)(Matrix3D) | Matrix를 다른 Matrix에 추가합니다. |
| override [Equals](../../aspose.pdf/matrix3d/equals/)(object) | 행렬을 다른 객체와 비교합니다. |
| override [GetHashCode](../../aspose.pdf/matrix3d/gethashcode/)() | 객체의 해시 코드를 가져옵니다. |
| override [ToString](../../aspose.pdf/matrix3d/tostring/)() | 행렬의 텍스트 표현을 반환합니다. |
| static [GetAngle](../../aspose.pdf/matrix3d/getangle/)(Rotation) | 회전을 각도(도)로 변환합니다. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


