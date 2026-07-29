---
title: "HtmlSaveOptions.CustomHtmlSavingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "HtmlSaveOptions 字段。转换结果可以包含一个或多个 HTML 页面。您可以为此属性分配由自定义方法创建的委托，该方法实现对单个 HTML 页面进行准确的 markupHTML 处理，且不包含任何在转换过程中生成的外部链接文件。在这种情况下，可以在自定义代码中完成将 HTML 页面保存到流或磁盘的处理。所有保存 HTML 页面所需的操作必须在提供的方法代码中完成，因为转换器代码中的保存结果将不再使用。如果出于某些原因必须由转换器代码本身而非自定义代码完成处理，请在自定义代码中设置 htmlSavingInfo 参数变量的标志 CustomProcessingCancelled，这将通知转换器必须在转换器内部完成该资源的所有必要处理，就像没有任何外部自定义代码一样。"
type: docs
weight: 270
url: /zh/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

转换结果可能包含一个或多个 HTML 页面。您可以将自定义方法生成的委托分配给此属性，以实现对在转换期间创建的单个 HTML 页面（准确来说是标记 HTML，不包含任何外部链接文件）的处理。在这种情况下，诸如将页面的 HTML 保存到流或磁盘的处理可以在自定义代码中完成。所有保存 HTML 页面所需的操作必须在提供的方法代码中执行，因为转换器内部的保存代码将不再使用。如果出于某种原因必须由转换器自身的代码而非自定义代码完成处理，请在自定义代码中设置 'htmlSavingInfo' 参数变量的标志 'CustomProcessingCancelled'：这将通知转换器应自行完成该资源的所有必要处理步骤，就像没有任何外部自定义代码一样。

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### 另请参见

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


