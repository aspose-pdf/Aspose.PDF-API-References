---
title: "类 Page"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Page 类。表示 PDF 文档页面的类"
type: docs
weight: 8190
url: /zh/net/aspose.pdf/page/
---
## Page class

表示 PDF 文档页面的类。

```csharp
public sealed class Page : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | 获取页面属性的集合。 |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | 获取页面注释的集合。 [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | 获取或设置页面的 art box。 |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | 获取页面上 artifacts 的集合。 |
| [Background](../../aspose.pdf/page/background/) { get; set; } | 获取或设置页面的背景颜色。 |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | 获取或设置页面的背景图像（仅用于生成器，在读取文档时不填充）。 |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | 获取或设置页面的 bleed box。 |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | 根据从 SetColor 操作符、图像和表单获取的信息设置页面的颜色类型。 |
| [Contents](../../aspose.pdf/page/contents/) { get; } | 获取页面内容流中操作符的集合。 [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | 获取或设置页面的裁剪框。 |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | 获取或设置页面显示持续时间。这是页面在演示期间应显示的秒数。如果未定义持续时间，则返回 -1。 |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | 获取此页面上按 Tab 顺序排列的 Field 对象列表。 |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | 获取或设置页面页脚。 |
| [Group](../../aspose.pdf/page/group/) { get; set; } | 获取或设置一个组属性类，指定页面的页面组在透明成像模型中的属性。 |
| [Header](../../aspose.pdf/page/header/) { get; set; } | 获取或设置页面页眉。 |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | 获取或设置在页面最后一个段落之后添加的段落。 |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | 获取或设置图层集合。 |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | 获取或设置页面的媒体框。 |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | 获取或设置注释的线条样式。（仅用于生成器，读取文档时不填充） |
| [Number](../../aspose.pdf/page/number/) { get; } | 获取页面的页码。 |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | 获取或设置页面信息（仅用于生成器，读取文档时不填充）。 |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | 获取段落。 |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | 获取或设置页面的矩形。获取时：如果指定，则返回页面裁剪框，否则返回页面媒体框。设置时：始终设置页面媒体框。请注意，此属性不考虑页面旋转。若要获取考虑旋转的页面矩形，请使用 ActualRect。 |
| [Resources](../../aspose.pdf/page/resources/) { get; } | 获取页面资源。Resources 对象包含图像、表单和字体的集合。 [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | 获取或设置页面的旋转角度。 |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | 获取页面的变换矩阵。 |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | 获取或设置页面的 Tab 顺序。可能的值：Row、Column。默认，Manual。 |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | 获取或设置目录信息。 |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | 获取或设置页面的修剪框。 |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | 获取或设置 UserUnit 值。一个正数，表示默认用户空间单位的大小，以 1/72 英寸的倍数计。默认值为 1。请设置为零或负数以清除页面中的此条目。 |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | 获取或设置页面的水印。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | 接受 [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) 访问者对象，提供处理注释的功能。 |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | 接受 [`ImagePlacementAbsorber`](../imageplacementabsorber/) 访问者对象，提供处理图像放置对象的功能。 |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | 接受 [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) 访问者对象，提供处理文本对象的功能。 |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | 接受 [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) 访问者对象，提供处理文本对象的功能。 |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | 向页面添加图形。比使用 [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/) 方法逐个添加元素更快。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | 在页面上添加图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | 在页面上添加图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | 在页面上添加可搜索的图像，并将其定位在指定矩形的中间，同时保持图像的比例。 |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | 在页面上添加图像，并根据图像矩形的位置进行放置。 |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | 将印章放入页面。印章可以是页码、图像或简单文本，例如某个徽标。 |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | 将当前页面转换为位图，然后返回字节数组。 |
| [AsXml](../../aspose.pdf/page/asxml/)() | 将当前页面转换为 UTF-8 编码的 XML。 |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | 计算 bbox 值——包含内容且不含可见边距的矩形。 |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | 将页面转换为 PNG，以用于 DSR、OMR、OCR 图像流。 |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | 从页面删除图形。比使用 [`Remove`](../../aspose.pdf.vector/graphicelement/remove/) 方法逐个删除元素更快。 |
| [Dispose](../../aspose.pdf/page/dispose/)() | 释放内存 |
| [Flatten](../../aspose.pdf/page/flatten/)() | 移除页面上所有字段，并用其值替代。 |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | 清除缓存数据 |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | 返回有关页面内容内部操作的通知。（目前仅支持文本添加场景中段落事件的通知。） |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | 根据页面的 CropBox（如果 CropBox 为 null，则使用 MediaBox）返回页面的矩形。 |
| [GetResources](../../aspose.pdf/page/getresources/)() | 检索与页面关联的资源。 |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | 检测页面上是否存在矢量图形。 |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | 获取页面是否为空的标志。 |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | 将页面转换为灰度。 |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | 将页面上的所有图层合并为具有指定新图层名称的单个图层。 |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | 将页面上的所有图层合并为具有指定新图层名称和可选内容组 Id 的单个图层。 |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | 调整页面大小。 |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | 使用给定的页面设备处理页面。 |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | 使用给定的页面设备处理页面。 |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | 设置页面的尺寸。 |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | 尝试保存页面上存在的矢量图形。保存格式为 SVG。 |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | 将整数值转换为相应的旋转枚举成员。 |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | 将旋转枚举成员转换为整数值。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | 用于自定义页眉和页脚的事件。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | 自定义页眉和页脚的过程。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


