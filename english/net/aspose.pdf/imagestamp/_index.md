---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageStamp class. Reresents graphic stamp
type: docs
weight: 3850
url: /net/aspose.pdf/imagestamp/
---
## ImageStamp class

Reresents graphic stamp.

```csharp
public sealed class ImageStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Initializes a new instance of the `ImageStamp` class. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Creates image stamp by image in the specified file. |

## Properties

| Name | Description |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Sets or gets a bool value that indicates the content is stamped as background. If the value is true, the stamp content is layed at the bottom. By defalt, the value is false, the stamp content is layed at the top. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Gets or sets bottom margin of stamp. |
| [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Gets or sets image height. Setting this image allows to scale image vertically. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Gets or sets Horizontal alignment of stamp on the page. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Gets image stream used for stamping. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Gets or sets left margin of stamp. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Gets or sets a value to indicate the stamp opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Gets or sets a value to indicate the stamp outline opacity. The value is from 0.0 to 1.0. By default the value is 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Gets or sets a value of the stamp outline width. By default the value is 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Gets or sets quality of image stamp in percent. Valid values are 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Gets or sets right margin of stamp. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Sets or gets the rotation of stamp content according [`Rotation`](../rotation/) values. Note. This property is for set angles which are multiples of 90 degrees (0, 90, 180, 270 degrees). To set arbitrary angle use RotateAngle property. If angle set by ArbitraryAngle is not multiple of 90 then Rotate property returns Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Gets or sets rotate angle of stamp in degrees. This property allows to set arbitrary rotate angle. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Gets or sets top margin of stamp. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Gets or sets vertical alignment of stamp on page. |
| [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Gets or sets image width. Setting this property allos to scal image horizontally. |
| [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Horizontal stamp coordinate, starting from the left. |
| [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertical stamp coordinate, starting from the bottom. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zooming factor of the stamp. Allows to scale stamp. Please note that pair of properties ZoomX and ZoomY allows to set zoom factor for every axe separately. Setting of this property changes both ZoomX and ZoomY properties. If ZoomX and ZoomY are different then Zoom property returns ZoomX value. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horizontal zooming factor of the stamp. Allows to scale stamp horizontally. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertical zooming factor of the stamp. Allows to scale stamp vertically. |

## Methods

| Name | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returns stamp ID. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Adds graphic stamp on the page. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Sets stamp Id. |

### See Also

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


