---
title: "클래스 SetColor"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Operators.SetColor 클래스. sc 연산자의 비스트로크 작업에 대한 색상을 설정하는 클래스를 나타냅니다."
type: docs
weight: 7770
url: /ko/net/aspose.pdf.operators/setcolor/
---
## SetColor class

비스트로크 연산을 위한 색상을 설정하는 sc operator를 나타내는 클래스.

```csharp
public class SetColor : BasicSetColorOperator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SetColor](setcolor/#constructor)() | 연산자를 초기화합니다. |
| [SetColor](setcolor/#constructor_1)(double) | DeviceGray, CalGray 및 Indexed 색상 공간에 대한 스트로크 연산자의 색상을 설정합니다. |
| [SetColor](setcolor/#constructor_4)(double[]) | 색상 구성 요소를 지정할 수 있는 생성자입니다. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | DeviceRGB, CalRGB 및 Lab 색상 공간에 대한 스트로크 연산자의 색상을 설정합니다 |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | CMYK 색상 공간에 대한 비스트로크 연산자의 색상을 설정합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | 파란색 구성 요소를 가져오거나 설정합니다. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | 시안 구성 요소를 가져오거나 설정합니다. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Color 구성 요소 배열을 가져옵니다. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | 녹색 구성 요소를 가져오거나 설정합니다. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | gray Color의 검은색 구성 요소를 가져옵니다. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Page 연산자 목록에서 연산자 인덱스입니다. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | 검은색 구성 요소를 가져오거나 설정합니다. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | 마젠타 구성 요소를 가져오거나 설정합니다. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | 빨간색 구성 요소를 가져오거나 설정합니다. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | 노란색 구성 요소를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | 연산자를 처리하기 위해 방문자 객체를 수락합니다. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | 연산자에 의해 지정된 색상을 반환합니다. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | 색상의 문자열 표현을 반환합니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |

### 또 보기

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


