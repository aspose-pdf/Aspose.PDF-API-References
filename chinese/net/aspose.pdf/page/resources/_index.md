---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: 页面属性。获取页面资源。资源对象包含图像、表单和字体的集合。资源
type: docs
weight: 240
url: /zh/net/aspose.pdf/page/resources/
---
## 页面.资源属性

获取页面资源。资源对象包含图像、表单和字体的集合。`Resources`

```csharp
public Resources Resources { get; }
```

## 示例

示例演示扫描页面图像：

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### 另请参阅

* 类 [Resources](../../resources/)
* 类 [Page](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)