---
title: Class SetAdvancedColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetAdvancedColorStroke 클래스. 스트로킹 작업을 위한 색상을 설정하는 SCN 연산자를 나타내는 클래스
type: docs
weight: 7570
url: /ko/net/aspose.pdf.operators/setadvancedcolorstroke/
---
## SetAdvancedColorStroke 클래스

SCN 연산자(스트로킹 작업을 위한 색상 설정)를 나타내는 클래스입니다.

```csharp
public class SetAdvancedColorStroke : BasicSetColorAndPatternOperator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor)() | 연산자를 초기화합니다. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_1)(double) | scn 연산자를 위한 생성자 |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_4)(double, string) | scn 연산자를 위한 생성자. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_5)(double[], string) | scn 연산자를 위한 생성자. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_3)(double, double, double, string) | scn 연산자를 위한 생성자. |
| [SetAdvancedColorStroke](setadvancedcolorstroke/#constructor_2)(double, double, double, double, string) | scn 연산자를 위한 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | 색상의 빨간 구성 요소를 가져옵니다. |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | CMYK 색상의 시안 구성 요소를 가져옵니다. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 색상 구성 요소 배열을 가져옵니다. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | 색상의 녹색 구성 요소를 가져옵니다. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 회색 색상의 검은 구성 요소를 가져옵니다. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 페이지 연산자 목록에서 연산자 인덱스. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | CMYK 색상의 검은 구성 요소를 가져옵니다. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | CMYK 색상의 마젠타 구성 요소를 가져옵니다. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | 패턴 이름을 가져옵니다. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 색상의 빨간 구성 요소를 가져옵니다. |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | CMYK 색상의 노란 구성 요소를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setadvancedcolorstroke/accept/)(IOperatorSelector) | 연산자를 처리하기 위해 방문자 객체를 수락합니다. |
| override [getColor](../../aspose.pdf.operators/setadvancedcolorstroke/getcolor/)() | 연산자에 의해 지정된 색상을 반환합니다. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 연산자 및 그 매개변수의 텍스트를 반환합니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |

### 참조

* 클래스 [BasicSetColorAndPatternOperator](../basicsetcolorandpatternoperator/)
* 네임스페이스 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 어셈블리 [Aspose.PDF](../../)