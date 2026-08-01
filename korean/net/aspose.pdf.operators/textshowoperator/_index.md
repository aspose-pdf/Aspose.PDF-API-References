---
title: "클래스 TextShowOperator"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Operators.TextShowOperator 클래스. 텍스트 Tj TJ 등을 출력하는 데 사용되는 모든 연산자의 추상 기본 클래스"
type: docs
weight: 8060
url: /ko/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

텍스트를 출력하는 모든 연산자(Tj, TJ 등)를 위한 추상 기본 클래스.

```csharp
public class TextShowOperator : TextOperator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | TextShowOperator를 초기화합니다. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | TextProperties를 전달할 수 있는 TextShowOperator를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Page 연산자 목록에서 연산자 인덱스입니다. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | 연산자가 페이지에 출력하는 텍스트를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | 연산자를 처리하기 위해 방문자 객체를 수락합니다. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 연산자의 텍스트와 매개변수를 반환합니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |

### 또 보기

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


