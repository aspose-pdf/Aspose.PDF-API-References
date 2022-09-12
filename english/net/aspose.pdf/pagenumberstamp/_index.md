---
title: PageNumberStamp
second_title: Aspose.PDF for .NET API Reference
description: Represents page number stamp and used to number pages.
type: docs
weight: 5850
url: /net/aspose.pdf/pagenumberstamp/
---
## PageNumberStamp class

Represents page number stamp and used to number pages.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Constructors

| Name | Description |
| --- | --- |
| [PageNumberStamp](pagenumberstamp#constructor)() | Initializes a new instance of the [`PageNumberStamp`](../pagenumberstamp) class. Format is set to "#". |
| [PageNumberStamp](pagenumberstamp#constructor_1)(FormattedText) | Creates PageNumberStamp by formatted text. |
| [PageNumberStamp](pagenumberstamp#constructor_2)(string) | Initializes a new instance of the [`PageNumberStamp`](../pagenumberstamp) class. |

## Properties

| Name | Description |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Gets or sets bottom margin of stamp. |
| [Draw](../../aspose.pdf/textstamp/draw) { get; set; } | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [Format](../../aspose.pdf/pagenumberstamp/format) { get; set; } | String value for stamping page numbers. Value must include char '#' which is replaced with the page number in the process of stamping. |
| override [Height](../../aspose.pdf/textstamp/height) { get; set; } | Desired height of the stamp on the page. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Gets or sets Horizontal alignment of stamp on the page. |
| [Justify](../../aspose.pdf/textstamp/justify) { get; set; } | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Gets or sets left margin of stamp. |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth) { get; set; } | Max row height for WordWrap option. |
| [NumberingStyle](../../aspose.pdf/pagenumberstamp/numberingstyle) { get; set; } | Numbering style which used by this stamp. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Gets or sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Gets or sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Gets or sets a value of the stamp outline width. By default the value is 1.0. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Gets or sets right margin of stamp. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Sets or gets the rotation of stamp content according [`Rotation`](../rotation) values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Gets or sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [Scale](../../aspose.pdf/textstamp/scale) { get; set; } | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [StartingNumber](../../aspose.pdf/pagenumberstamp/startingnumber) { get; set; } | Gets or sets value of the number of starting page. Other pages will be numbered starting from this value. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment) { get; set; } | Alignment of the text inside the stamp. |
| [TextState](../../aspose.pdf/textstamp/textstate) { get; } | Gets text properties of the stamp. See [`TextState`](../textstamp/textstate) for details. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Gets or sets top margin of stamp. |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline) { get; set; } | Defines coordinate origin for placing text. If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent value will be treated as text base line. If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent value will be treated as bottom (descent line) of text. |
| [Value](../../aspose.pdf/textstamp/value) { get; set; } | Gets or sets string value which is used as stamp on the page. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Gets or sets vertical alignment of stamp on page. |
| override [Width](../../aspose.pdf/textstamp/width) { get; set; } | Desired width of the stamp on the page. |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap) { get; set; } | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Horizontal stamp coordinate, starting from the left. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Vertical stamp coordinate, starting from the bottom. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |

## Methods

| Name | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Returns stamp ID. |
| override [Put](../../aspose.pdf/pagenumberstamp/put)(Page) | Adds page number. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Sets stamp Id. |

### See Also

* class [TextStamp](../textstamp)
* namespace [Aspose.Pdf](../../aspose.pdf)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
