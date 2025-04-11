---
title: Class Operator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operator 클래스. 연산자를 나타내는 추상 클래스
type: docs
weight: 7070
url: /ko/net/aspose.pdf/operator/
---
## 연산자 클래스

연산자를 나타내는 추상 클래스.

```csharp
public abstract class Operator
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | 페이지 연산자 목록에서의 연산자 인덱스. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | 연산자 처리를 제공하는 방문자 IOperatorSelector를 수락합니다. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 연산자 및 그 매개변수의 텍스트를 반환합니다. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | 이 인스턴스를 주어진 객체와 비교합니다. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | 연산자가 텍스트 출력을 담당하는 연산자인지 여부를 결정합니다 (Tj, TJ 등). |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)