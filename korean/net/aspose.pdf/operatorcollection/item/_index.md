---
title: "OperatorCollection.Item"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OperatorCollection 속성. 인덱스로 연산자를 가져옵니다."
type: docs
weight: 40
url: /ko/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

인덱스로 연산자를 가져옵니다.

```csharp
public override Operator this[int index] { get; set; }
```

| 매개변수 | 설명 |
| --- | --- |
| index | 연산자의 인덱스. 번호는 1부터 시작합니다. |

### 반환 값

요청된 인덱스의 연산자

## 예제

예제는 페이지 콘텐츠의 연산자를 인덱스로 가져오는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### 또 보기

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


