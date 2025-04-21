---
title: Class TextStateOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextStateOperator 클래스. 현재 텍스트 상태를 변경하는 연산자의 추상 기본 클래스（Tc, Tf, TL 등）.
type: docs
weight: 7930
url: /ko/net/aspose.pdf.operators/textstateoperator/
---
## TextStateOperator class

현재 텍스트 상태(Tc, Tf, TL 등)를 변경하는 연산자의 추상 기본 클래스입니다.

```csharp
public class TextStateOperator : TextOperator
```

## Constructors

| Name | Description |
| --- | --- |
| [TextStateOperator](textstateoperator/#constructor)() | TextStateOperator를 초기화합니다. |
| [TextStateOperator](textstateoperator/#constructor_1)(TextProperties) | TextProperties를 전달할 수 있는 TextStateOperator를 초기화합니다. |

## Properties

| Name | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 페이지 연산자 목록에서 연산자 인덱스입니다. |

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