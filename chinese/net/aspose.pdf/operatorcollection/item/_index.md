---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection 属性。通过索引获取操作符
type: docs
weight: 40
url: /zh/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection 索引器

通过索引获取操作符。

```csharp
public override Operator this[int index] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| index | 操作符的索引。编号从 1 开始。 |

### 返回值

来自请求索引的操作符

## 示例

示例演示如何通过索引获取页面内容的操作符。

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### 另请参阅

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)