---
title: Class BasicSetColorAndPatternOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.BasicSetColorAndPatternOperator 클래스. 모든 색상 설정 연산자의 기본 연산자
type: docs
weight: 7150
url: /ko/net/aspose.pdf.operators/basicsetcolorandpatternoperator/
---
## BasicSetColorAndPatternOperator 클래스

모든 색상 설정 연산자의 기본 연산자입니다.

```csharp
public abstract class BasicSetColorAndPatternOperator : BasicSetColorOperator
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | 색상의 빨간색 구성 요소를 가져옵니다. |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | CMYK 색상의 청록색 구성 요소를 가져옵니다. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | 색상 구성 요소의 배열을 가져옵니다. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | 색상의 녹색 구성 요소를 가져옵니다. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | 회색 색상의 검은색 구성 요소를 가져옵니다. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 페이지 연산자 목록에서 연산자 인덱스입니다. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | CMYK 색상의 검은색 구성 요소를 가져옵니다. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | CMYK 색상의 자홍색 구성 요소를 가져옵니다. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | 패턴 이름을 가져옵니다. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | 색상의 빨간색 구성 요소를 가져옵니다. |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | CMYK 색상의 노란색 구성 요소를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | 연산자 처리를 제공하는 방문자 IOperatorSelector를 수락합니다. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | 연산자에 의해 지정된 색상을 반환합니다. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 연산자 및 그 매개변수의 텍스트를 반환합니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |

### 참조

* 클래스 [BasicSetColorOperator](../basicsetcoloroperator/)
* 네임스페이스 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 어셈블리 [Aspose.PDF](../../)