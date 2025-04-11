---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetColorStroke 클래스. 색상 스트로크 연산자를 위한 색상을 설정하는 SC 연산자를 나타내는 클래스
type: docs
weight: 7680
url: /ko/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke 클래스

색상 스트로크 연산자를 위한 색상을 설정하는 SC 연산자를 나타내는 클래스입니다.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | 연산자를 초기화합니다. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | DeviceGray, CalGray 및 Indexed 색상 공간을 위한 스트로크 연산자의 색상을 설정합니다. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | 색상 구성 요소를 설정할 수 있는 생성자입니다. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | DeviceRGB, CalRGB 및 Lab 색상 공간을 위한 스트로크 연산자의 색상을 설정합니다. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | CMYK 색상 공간을 위한 스트로크 연산자의 색상을 설정합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | 파란색 구성 요소를 가져오거나 설정합니다. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | 청록색 구성 요소를 가져오거나 설정합니다. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 색상 구성 요소 배열을 가져옵니다. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | 녹색 구성 요소를 가져오거나 설정합니다. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 회색 색상의 검은색 구성 요소를 가져옵니다. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 페이지 연산자 목록에서 연산자 인덱스입니다. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | 검은색 구성 요소를 가져오거나 설정합니다. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | 마젠타 구성 요소를 가져오거나 설정합니다. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | 빨간색 구성 요소를 가져오거나 설정합니다. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | 노란색 구성 요소를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | 연산자를 처리하기 위해 방문자 객체를 수락합니다. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | 연산자에 의해 지정된 색상을 반환합니다. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 연산자 및 그 매개변수의 텍스트를 반환합니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |

### 참조

* 클래스 [BasicSetColorOperator](../basicsetcoloroperator/)
* 네임스페이스 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 어셈블리 [Aspose.PDF](../../)