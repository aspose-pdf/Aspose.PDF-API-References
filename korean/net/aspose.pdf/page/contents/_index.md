---
title: "Page.Contents"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Page 속성. 페이지의 콘텐츠 스트림에 있는 연산자들의 컬렉션을 가져옵니다. OperatorCollection"
type: docs
weight: 90
url: /ko/net/aspose.pdf/page/contents/
---
## Page.Contents property

페이지의 콘텐츠 스트림에 있는 연산자들의 컬렉션을 가져옵니다. [`OperatorCollection`](../../operatorcollection/)

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

### 또 보기

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


