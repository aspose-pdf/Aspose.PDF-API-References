---
title: Class FloatingBox
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FloatingBox class. 
type: docs
weight: 4990
url: /net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | Initializes a new instance of the `FloatingBox` class. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | Initializes a new instance of the `FloatingBox` class with specified width and height. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | Gets or sets a [`Color`](../color/) object that indicates the background color of the floating box. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | Gets or sets background image for page (for generator only, not filled in when reading document). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | Gets or sets a [`BorderInfo`](../borderinfo/) object that indicates the border info of the floating box. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | Gets or sets a column info |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | Gets or sets a float value that indicates the height of the floating box. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of paragraph |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | Gets or sets a bool value that indicates whether the paragraph need to be repeated on next page. Default value is false.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | Gets or sets the table left coordinate. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | Gets or sets a [`MarginInfo`](../margininfo/) object that indicates the padding of the floating box. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | Gets or sets a [`Paragraphs`](./paragraphs/) collection that indicates all paragraphs in the cell. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | Specifies variant for determining the location of the FloatingBox on the page. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | Gets or sets the table top coordinate. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | Gets or sets a float value that indicates the width of the floating box. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | Clones a new `FloatingBox` object. Paragraphs in the floating box are not cloned. |

### See Also

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


