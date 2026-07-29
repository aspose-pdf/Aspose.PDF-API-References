---
title: "Page.Resources"
second_title: "Aspose.PDF for .NET API 参考"
description: "Page 属性。获取页面资源。Resources 对象包含图像、表单和字体的集合。Resources"
type: docs
weight: 240
url: /zh/net/aspose.pdf/page/resources/
---
## Page.Resources property

获取页面资源。Resources 对象包含图像、表单和字体的集合。`Resources`

```csharp
public Resources Resources { get; }
```

## 示例

示例演示遍历页面图像：

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### 另请参见

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


