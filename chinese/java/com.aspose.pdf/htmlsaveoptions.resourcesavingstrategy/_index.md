---
title: "HtmlSaveOptions.ResourceSavingStrategy"
linktitle: "HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "通过此属性，您可以分配由自定义方法创建的委托，该方法实现对从 PDF 中提取并必须保存的外部资源（字体或图像）的处理。"
type: docs
weight: 2150
url: /zh/java/com.aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy, com.aspose.ms.System.MulticastDelegate, com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy

```
public abstract static class HtmlSaveOptions.ResourceSavingStrategy extends com.aspose.ms.System.MulticastDelegate
```

您可以将由自定义方法创建的委托分配给此属性，该方法实现对从 PDF 中提取并在 PDF 转换为 HTML 期间必须保存为外部资源的外部资源（字体或图像）的处理。在这种情况下，处理（例如保存到流或磁盘）可以在该自定义代码中完成，并且该自定义代码必须返回路径（或任何不带引号的字符串），该路径随后会被合并到生成的 HTML 中，以替代原本假定的图像资源路径。此时，保存图像的所有必要操作必须在提供的方法代码中完成，因为转换器代码中的保存将不再使用。如果由于某种原因必须由转换器自身的代码而非自定义代码进行处理，请在自定义代码中设置 'resourceSavingInfo' 参数变量的标志 'CustomProcessingCancelled'：它向转换器指示，所有对该资源的必要处理步骤应由转换器本身完成，就像没有任何外部自定义代码一样。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ResourceSavingStrategy](#ResourceSavingStrategy--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke](#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-) | 调用的方法 |

### ResourceSavingStrategy {#ResourceSavingStrategy--}
```
public ResourceSavingStrategy()
```



### invoke {#invoke-com.aspose.pdf.SaveOptions.ResourceSavingInfo-}
调用的方法
