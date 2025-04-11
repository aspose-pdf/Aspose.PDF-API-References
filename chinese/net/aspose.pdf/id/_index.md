---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Id 类。表示文件标识符结构
type: docs
weight: 5850
url: /zh/net/aspose.pdf/id/
---
## Id 类

表示文件标识符结构。

```csharp
public class Id
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | 基于文档最后更新时的内容更改标识符。 |
| [Original](../../aspose.pdf/id/original/) { get; } | 基于文档最初创建时的内容的永久标识符。 |

## 示例

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)