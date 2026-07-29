---
title: "类 Id"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Id 类。表示文件标识符结构"
type: docs
weight: 5980
url: /zh/net/aspose.pdf/id/
---
## Id class

表示文件标识符结构。

```csharp
public class Id
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | 根据文档在上次更新时的内容更改标识符。 |
| [Original](../../aspose.pdf/id/original/) { get; } | 基于文档在最初创建时内容的永久标识符。 |

## 示例

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


