---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextShowOperator 클래스. 텍스트를 출력하는 모든 연산자의 추상 기본 클래스 （Tj, TJ 등）.
type: docs
weight: 7920
url: /ko/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

텍스트를 출력하는 모든 연산자의 추상 기본 클래스 (Tj, TJ 등).

```csharp
public class TextShowOperator : TextOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | TextShowOperator를 초기화합니다. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | TextProperties를 전달할 수 있는 TextShowOperator를 초기화합니다. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 페이지 연산자 목록에서 연산자 인덱스. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | 페이지에 출력된 텍스트를 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | 연산자를 처리하기 위해 방문자 객체를 수락합니다. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 연산자와 그 매개변수의 텍스트를 반환합니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |

### See Also

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)