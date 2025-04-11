---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions 字段。转换的结果可以包含一个或多个 HTML 页面。您可以将此属性分配给从自定义方法创建的委托，该方法实现对一个 HTML 页面的处理（准确地说 - 标记 HTML，且不包含任何在转换过程中创建的外部链接文件）。在这种情况下，处理（如将页面的 HTML 保存到流或磁盘）可以在该自定义代码中完成。在这种情况下，必须在提供的方法的代码中进行保存 HTML 页面的所有必要操作，因为转换器代码中的结果保存将不被使用。如果出于某种原因，某个案例的处理必须由转换器的代码本身完成，而不是在自定义代码中，请在自定义代码中设置 'htmlSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志：这将向转换器发出信号，表明处理该资源的所有必要步骤必须在转换器本身中完成，就像没有任何外部自定义代码进行处理一样。
type: docs
weight: 270
url: /zh/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy 字段

转换的结果可以包含一个或多个 HTML 页面。您可以将此属性分配给从自定义方法创建的委托，该方法实现对一个 HTML 页面的处理（准确地说 - 标记 HTML，且不包含任何外部链接文件，如果有的话），该页面是在转换过程中创建的。在这种情况下，处理（如将页面的 HTML 保存到流或磁盘）可以在该自定义代码中完成。在这种情况下，必须在提供的方法的代码中进行保存 HTML 页面的所有必要操作，因为转换器代码中的结果保存将不被使用。如果出于某种原因，某个案例的处理必须由转换器的代码本身完成，而不是在自定义代码中，请在自定义代码中设置 'htmlSavingInfo' 参数变量的 'CustomProcessingCancelled' 标志：这将向转换器发出信号，表明处理该资源的所有必要步骤必须在转换器本身中完成，就像没有任何外部自定义代码进行处理一样。

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### 另请参阅

* 委托 [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* 类 [HtmlSaveOptions](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)