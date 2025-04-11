---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: 页面属性。获取或设置页面显示持续时间。这是页面在演示期间应显示的时间（以秒为单位）。如果未定义持续时间，则返回 1。
type: docs
weight: 110
url: /zh/net/aspose.pdf/page/duration/
---
## Page.Duration 属性

获取或设置页面显示持续时间。这是页面在演示期间应显示的时间（以秒为单位）。如果未定义持续时间，则返回 -1。

```csharp
public double Duration { get; set; }
```

## 示例

示例演示如何获取页面持续时间

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### 另请参阅

* 类 [Page](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)