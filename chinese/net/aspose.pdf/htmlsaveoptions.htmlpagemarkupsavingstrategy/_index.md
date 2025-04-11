---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 转换的结果可以包含一个或多个 HTML 页面，这些页面也可以引用外部文件，如图像或字体。您可以将此属性分配给从自定义方法创建的委托，该方法实现了处理在转换过程中生成的 HTML 页面（HTML 本身）。在这种情况下，处理（如保存到流或磁盘）可以在该自定义代码中完成。在这种情况下，保存 HTML 页面标记的所有必要操作必须在提供的方法的代码中进行，因为在转换器的代码中保存结果将不被使用。如果出于某种原因，某个案例的处理必须由转换器的代码本身完成，而不是在自定义代码中，请在自定义代码中设置 'htmlSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志：这向转换器发出信号，表明处理该资源的所有必要步骤必须在转换器本身中完成，就像没有任何外部自定义保存代码一样。
type: docs
weight: 5680
url: /zh/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy 委托

转换的结果可以包含一个或多个 HTML 页面（这些页面也可以引用外部文件，如图像或字体）。您可以将此属性分配给从自定义方法创建的委托，该方法实现了处理在转换过程中生成的 HTML 页面（HTML 本身）。在这种情况下，处理（如保存到流或磁盘）可以在该自定义代码中完成。在这种情况下，保存 HTML 页面标记的所有必要操作必须在提供的方法的代码中进行，因为在转换器的代码中保存结果将不被使用。如果出于某种原因，某个案例的处理必须由转换器的代码本身完成，而不是在自定义代码中，请在自定义代码中设置 'htmlSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志：这向转换器发出信号，表明处理该资源的所有必要步骤必须在转换器本身中完成，就像没有任何外部自定义保存代码一样。

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | 表示可以用于保存或处理提供的 HTML 页面的数据 |

### 另请参阅

* 类 [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* 类 [HtmlSaveOptions](../htmlsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)