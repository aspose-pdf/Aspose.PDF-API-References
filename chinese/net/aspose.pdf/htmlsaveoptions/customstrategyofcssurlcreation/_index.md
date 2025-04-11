---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions字段。该字段可以包含自定义方法，该方法在多页生成开启时返回URL或URL模板。请参见下面关于主题CSS的详细信息，了解它应如何放入生成的结果HTML中。例如，如果您希望转换器在生成的CSS中放入某个特定的URL，而不是标准的CSS文件名，那么您只需创建并放入此属性的方法，该方法生成所需的URL。如果标志SplitCssIntoPages被设置，则此自定义策略（如果有）必须返回的不是CSS的确切URL，而是模板字符串，该字符串在转换器内部使用string.Format函数将占位符替换为页码后，可以解析为该页或其他页的CSS URL。在这种情况下，预期返回字符串的示例是SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0。
type: docs
weight: 300
url: /zh/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
