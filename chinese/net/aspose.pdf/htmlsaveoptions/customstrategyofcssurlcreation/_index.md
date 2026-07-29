---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Aspose.PDF for .NET API 参考"
description: "HtmlSaveOptions 字段。此字段可以包含自定义方法，该方法在启用多页生成时返回 URL 或 URL 模板，详细信息请参见下面关于应放入生成的结果 HTML 中的 CSS 的说明。例如，如果您希望转换器在生成的 CSS 中使用特定的 URL 替代标准 CSS 文件名，则只需创建并将生成所需 URL 的方法放入此属性中。如果设置了 SplitCssIntoPages 标志，则此自定义策略（如果存在）必须返回不是 CSS 的确切 URL，而是模板字符串，该模板在转换器内部使用 string.Format 函数将占位符替换为页码后，可解析为相应页的 CSS URL。此类情况下预期返回字符串的示例包括 SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0"
type: docs
weight: 300
url: /zh/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

此字段可以包含自定义方法，该方法返回应放入生成的结果 HTML 中的 CSS URL（如果启用多页生成，则返回 URL 模板——详见下文）。例如，如果您希望转换器在生成的 CSS 中使用特定的 URL 而不是标准的 CSS 文件名，只需创建并将生成所需 URL 的方法放入此属性。如果设置了标志 'SplitCssIntoPages'，则此自定义策略（若存在）必须返回不是 CSS 的确切 URL，而是模板字符串，转换器内部使用 string.Format() 将占位符替换为页码后即可解析为相应页面的 CSS URL。此类情况下的返回字符串示例包括：'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}'。

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### 另请参见

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


