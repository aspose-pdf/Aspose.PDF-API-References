---
title: "TextStamp Class"
linktitle: "TextStamp"
articleTitle: "TextStamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.TextStamp class. Represents textual stamp."
type: docs
weight: 2990
url: "/net/aspose.pdf/textstamp/"
keywords: "TextStamp, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextStamp class

Represents textual stamp.

```csharp
public class TextStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [TextStamp](./textstamp/#constructor)(FormattedText) | Initializes a new instance of the [`TextStamp`](../../aspose.pdf/textstamp/) class with formattedText object |
| [TextStamp](./textstamp/#constructor_1)(string) | Initializes a new instance of the [`TextStamp`](../../aspose.pdf/textstamp/) class. |
| [TextStamp](./textstamp/#constructor_2)(string, TextState) | Initializes a new instance of the [`TextStamp`](../../aspose.pdf/textstamp/) class. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustFontSizePrecision](./autoadjustfontsizeprecision/) { get; set; } | Automatically adjust font size precision. Default value: 0.1; |
| [AutoAdjustFontSizeToFitStampRectangle](./autoadjustfontsizetofitstamprectangle/) { get; set; } | If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: `Width` and `Height`. Default width and height are derived from the page rectangle. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Gets or sets bottom margin of stamp. |
| [Draw](./draw/) { get; set; } | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [FontSize](./fontsize/) { get; } | Actual font size after the stamp has been placed. (May differ from the initial font size provided through the constructor if the 'AutoAdjustFontSizeToFitStampRectangle' option is enabled.) |
| override [Height](./height/) { get; set; } | Desired height of the stamp on the page. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Gets or sets Horizontal alignment of stamp on the page. |
| [Justify](./justify/) { get; set; } | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Gets or sets left margin of stamp. |
| [MaxRowWidth](./maxrowwidth/) { get; set; } | Max row height for WordWrap option. |
| [NoCharacterBehavior](./nocharacterbehavior/) { get; set; } | Gets or sets mode that defines behavior in case fonts don't contain requested characters. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Gets or sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Gets or sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Gets or sets a value of the stamp outline width. By default the value is 1.0. |
| [ReplacementFont](./replacementfont/) { get; set; } | Gets or sets font used for replacing if user font does not contain required character. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Gets or sets right margin of stamp. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Sets or gets the rotation of stamp content according [`Rotation`](../../aspose.pdf/rotation/) values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Gets or sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [Scale](./scale/) { get; set; } | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [TextAlignment](./textalignment/) { get; set; } | Alignment of the text inside the stamp. |
| [TextState](./textstate/) { get; } | Gets text properties of the stamp. See `TextState` for details. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Gets or sets top margin of stamp. |
| [TreatYIndentAsBaseLine](./treatyindentasbaseline/) { get; set; } | Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text. |
| [Value](./value/) { get; set; } | Gets or sets string value which is used as stamp on the page. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Gets or sets vertical alignment of stamp on page. |
| override [Width](./width/) { get; set; } | Desired width of the stamp on the page. |
| [WordWrapMode](./wordwrapmode/) { get; set; } | Gets or sets the word wrap mode for text rendering. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Horizontal stamp coordinate, starting from the left. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertical stamp coordinate, starting from the bottom. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |

## Methods

| Name | Description |
| --- | --- |
| override [Put](./put/)(Page) | Adds textual stamp on the page. |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returns stamp ID. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Sets stamp Id. |

## Other Members

| Name | Description |
| --- | --- |
| enum [NoCharacterAction](../../aspose.pdf/textstamp.nocharacteraction) | Action to perform if font does not contain required character. |

### See Also

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

