---
title: "ReplaceTextStrategy Class"
linktitle: "ReplaceTextStrategy"
articleTitle: "ReplaceTextStrategy"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.ReplaceTextStrategy class. This class contains parameters which define PdfContentEditor behavior when ReplaceText operation is performed."
type: docs
weight: 550
url: "/net/aspose.pdf.facades/replacetextstrategy/"
keywords: "ReplaceTextStrategy, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## ReplaceTextStrategy class

This class contains parameters which define [PdfContentEditor](../pdfcontenteditor/) behavior when ReplaceText operation is performed.

```csharp
public sealed class ReplaceTextStrategy
```

## Constructors

| Name | Description |
| --- | --- |
| [ReplaceTextStrategy](replacetextstrategy/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [IsRegularExpressionUsed](../../aspose.pdf.facades/replacetextstrategy/isregularexpressionused/) { get; set; } | If false, string to find is a simple text. If true, string to find is regular expression. |
| [NoCharacterBehavior](../../aspose.pdf.facades/replacetextstrategy/nocharacterbehavior/) { get; set; } | Action which is performed when no approppriate font found for changed text (Throw exception / Substitute other font / Replace anyway). |
| [ReplaceScope](../../aspose.pdf.facades/replacetextstrategy/replacescope/) { get; set; } | Scope of the replacement operation (replace first occurence or replace all occurences). |

## Other Members

| Name | Description |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf.facades/replacetextstrategy.nocharacteraction) | Action to perform if font does not contain required character |
| enum [Scope](../../aspose.pdf.facades/replacetextstrategy.scope) | Scope where replace text operation is applied REPLACE_FIRST by default |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

