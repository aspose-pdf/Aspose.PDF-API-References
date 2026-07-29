---
title: "Page.Contents"
second_title: "Aspose.PDF for .NET API 参考"
description: "Page 属性。获取页面内容流中操作符的集合。OperatorCollection"
type: docs
weight: 90
url: /zh/net/aspose.pdf/page/contents/
---
## Page.Contents property

获取页面内容流中操作符的集合。 [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## 示例

示例演示如何扫描页面的操作符流。

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### 另请参见

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


