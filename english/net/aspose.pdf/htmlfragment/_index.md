---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlFragment class. Represents html fragment
type: docs
weight: 3500
url: /net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

Represents html fragment.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Initializes a new instance of the HtmlFragment class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of paragraph |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Gets or sets HtmlLoadOptions that will be used for loading (and rendering) of HTML into this instance of class. Please use it when it's necessary use specific setting for import of HTML for this or that instance (f.e when this or that instance should use specific BasePath for imported HTML or should use specific loader of external resources) If parameter is default (null), then standard HTML loading options will be used. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Gets or sets words break |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Gets or sets is paragraph has default margin otherwise margin is 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Gets rectangle of the HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Gets or sets font |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Clones html fragment. |

### See Also

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


