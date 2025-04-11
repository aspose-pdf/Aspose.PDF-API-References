---
title: Page.Contents
second_title: Aspose.PDF for .NET API Reference
description: 页面属性。获取页面内容流中的操作符集合。操作符集合
type: docs
weight: 90
url: /zh/net/aspose.pdf/page/contents/
---
## 页面.内容属性

获取页面内容流中的操作符集合。 [`操作符集合`](../../operatorcollection/)

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

### 另请参阅

* 类 [操作符集合](../../operatorcollection/)
* 类 [页面](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)