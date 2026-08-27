---
title: "Page.Duration"
second_title: "Aspose.PDF for .NET API 参考"
description: "Page 属性。获取或设置页面显示持续时间。这是页面在演示期间显示的秒数。如果未定义持续时间，则返回 1。"
type: docs
weight: 110
url: /zh/net/aspose.pdf/page/duration/
---
## Page.Duration property

获取或设置页面显示持续时间。这是页面在演示期间应显示的秒数。如果未定义持续时间，则返回 -1。

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

### 另请参见

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


