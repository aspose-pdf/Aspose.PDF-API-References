---
title: Id
second_title: Aspose.PDF for .NET API 参考
description: 表示文件标识符结构
type: docs
weight: 3710
url: /zh/net/aspose.pdf/id/
---
## Id class

表示文件标识符结构。

```csharp
public class Id
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified) { get; } | 根据文档上次更新时的内容更改标识符。 |
| [Original](../../aspose.pdf/id/original) { get; } | 基于文档最初创建时的内容的永久标识符。 |

### 例子

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### 也可以看看

* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
