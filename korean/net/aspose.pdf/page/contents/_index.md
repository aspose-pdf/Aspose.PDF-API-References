---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 페이지의 콘텐츠 스트림에서 연산자 컬렉션을 가져옵니다. OperatorCollection
type: docs
weight: 90
url: /ko/net/aspose.pdf/page/contents/
---
## Page.Contents 속성

페이지의 콘텐츠 스트림에서 연산자 컬렉션을 가져옵니다. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## 예제

예제는 페이지의 연산자 스트림을 스캔하는 방법을 보여줍니다.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### 참조

* 클래스 [OperatorCollection](../../operatorcollection/)
* 클래스 [Page](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)