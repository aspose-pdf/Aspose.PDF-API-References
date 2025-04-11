---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection 속성. 인덱스를 통해 연산자를 가져옵니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection 인덱서

인덱스를 통해 연산자를 가져옵니다.

```csharp
public override Operator this[int index] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| index | 연산자의 인덱스. 번호는 1부터 시작합니다. |

### 반환 값

요청된 인덱스의 연산자

## 예제

예제는 인덱스를 통해 페이지 내용의 연산자를 가져오는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)