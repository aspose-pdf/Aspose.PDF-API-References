---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.SetDash 클래스. d 연산자를 설정하는 선 대시 패턴을 나타내는 클래스
type: docs
weight: 7690
url: /ko/net/aspose.pdf.operators/setdash/
---
## SetDash 클래스

d 연산자(선 대시 패턴 설정)를 나타내는 클래스입니다.

```csharp
public class SetDash : Operator
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SetDash](setdash/)(int[], int) | 대시 패턴 연산자를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 페이지 연산자 목록에서의 연산자 인덱스입니다. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | 대시 패턴입니다. 배열의 요소는 교차하는 대시와 간격의 길이를 지정하는 숫자여야 합니다. 하나의 요소 배열인 경우 대시와 간격의 길이는 같습니다. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | 대시 단계입니다. 경로를 스트로크하기 시작하기 전에 대시 배열이 순환되어 대시와 간격의 길이를 합산해야 합니다. 누적 길이가 대시 단계에서 지정한 값과 같아지면 경로의 스트로크가 시작되며, 그 시점부터 대시 배열이 순환적으로 사용됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | 연산자를 처리하기 위해 방문자 객체를 수락합니다. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | 연산자의 문자열 표현을 가져옵니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |

### 참조

* 클래스 [Operator](../../aspose.pdf/operator/)
* 네임스페이스 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* 어셈블리 [Aspose.PDF](../../)