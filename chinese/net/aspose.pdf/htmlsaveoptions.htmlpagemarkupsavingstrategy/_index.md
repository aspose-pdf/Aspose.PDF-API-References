---
title: "委托 HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "转换结果可能包含一个或多个 HTML 页面，这些页面也可能引用图像或字体等外部文件。您可以为此属性分配由自定义方法创建的委托，该方法实现对在转换期间生成的 HTMLpageHTML 本身的处理。在这种情况下，可以在自定义代码中完成流或磁盘保存等处理。此时，所有保存 HTML 页面标记所需的操作必须在提供的方法代码中完成，因为转换器代码中的结果保存将不再使用。如果出于某些原因必须由转换器代码本身（而非自定义代码）进行此类处理，请在自定义代码中设置 htmlSavingInfo 参数变量的标志 CustomProcessingCancelled；这向转换器指示所有对该资源的必要处理步骤应由转换器自行完成，就像没有任何外部自定义保存代码一样。"
type: docs
weight: 5810
url: /zh/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

转换结果可能包含一个或多个 HTML 页面（这些页面也可能引用图像或字体等外部文件）。您可以为此属性分配由自定义方法创建的委托，该方法实现对在转换期间生成的 HTML 页面（HTML 本身）的处理。在这种情况下，可以在自定义代码中完成流或磁盘保存等处理。此时，所有保存 HTML 页面标记所需的操作必须在提供的方法代码中完成，因为转换器代码中的结果保存将不再使用。如果出于某些原因必须由转换器的代码本身（而非自定义代码）进行此类处理，请在自定义代码中设置 'CustomProcessingCancelled' 标志，针对 'htmlSavingInfo' 参数的变量；这向转换器指示所有对该资源的必要处理步骤应由转换器自行完成，就像没有任何外部自定义保存代码一样。

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | 表示可用于保存或处理提供的 HTML 页面的数据 |

### 另请参见

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


