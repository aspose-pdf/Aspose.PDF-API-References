---
title: Page
second_title: Aspose.PDF for .NET API 参考
description: 代表 PDF 文档页面的类
type: docs
weight: 5790
url: /zh/net/aspose.pdf/page/
---
## Page class

代表 PDF 文档页面的类。

```csharp
public sealed class Page : IDisposable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | 获取页面属性的集合。 |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | 获取页面注释集合。 [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | 获取或设置页面的艺术框。 |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | 获取页面上的工件集合。 |
| [Background](../../aspose.pdf/page/background) { get; set; } | 获取或设置页面的背景颜色。 |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | 获取或设置页面的背景图像（仅用于生成器）。 |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | 获取或设置页面出血框。 |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | 根据从运算符 SetColor、 图像和表单获取的信息设置页面的颜色类型。 |
| [Contents](../../aspose.pdf/page/contents) { get; } | 获取页面内容流中的运算符集合。 [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | 获取或设置页面的裁剪框。 |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | 获取设置的页面显示持续时间。这是在演示期间应显示页面的时间（以秒为单位）。 如果没有定义持续时间，则返回 -1。 |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | 在此页面上按 Tab 顺序获取 Field 对象的列表。 |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | 获取或设置页脚。 |
| [Group](../../aspose.pdf/page/group) { get; set; } | 获取或设置一个组属性类，该类指定在透明成像模型中使用的页面的页面组的属性。 |
| [Header](../../aspose.pdf/page/header) { get; set; } | 获取或设置页眉。 |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | 获取或设置在页面最后一段之后添加的段落 |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | 获取或设置图层集合。 |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | 获取或设置页面的媒体框。 |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | 获取或设置笔记的线条样式。（仅用于生成器） |
| [Number](../../aspose.pdf/page/number) { get; } | 获取页码。 |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | 获取或设置页面信息（仅用于生成器，读取文件时不填写）。 |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | 获取段落。 |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | 获取或设置页面的矩形。如果指定则返回页面裁剪框，否则返回页面媒体框。 请注意，此属性不考虑页面旋转。要获得考虑旋转的页面矩形，请使用 ActualRect。 |
| [Resources](../../aspose.pdf/page/resources) { get; } | 获取页面资源。资源对象包含图像、表格和字体的集合。 [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | 获取或设置页面的旋转。 |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | 获取页面的变换矩阵。 |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | 获取或设置页面的tab顺序。 可能的值:行、列。默认，手动 |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | 获取或设置目录信息。 |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | 获取或设置页面的裁切框。 |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | 获取或设置 UserUnit 值。一个正数，表示默认用户空间单位的大小，以 1 ⁄ 72 英寸的倍数表示。 默认值为1。请设置零或负值以清除页面中的此条目。 |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | 获取或设置页面的水印。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | 接受[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector)提供使用注释功能的访问者对象。 |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | 接受[`ImagePlacementAbsorber`](../imageplacementabsorber)访问者对象，该对象提供使用图像放置对象的功能。 |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | 接受[`TextAbsorber`](../../aspose.pdf.text/textabsorber)访问者对象，该对象提供使用文本对象的功能。 |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | 接受[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber)访问者对象，提供使用文本对象的功能。 |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | 将图像添加到页面上，并将其定位在指定矩形保存图像比例的中间。 |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | 将图像添加到页面上，并将其定位在指定矩形保存图像比例的中间。 |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | 将可搜索图像添加到页面上，并将其定位在指定矩形保存图像比例的中间。 |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | 在页面上添加图像并根据图像矩形位置放置它。 |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | 将邮票放入页面。印章可以是页码、图像或简单的文本，例如一些标志。 |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | 将当前页面转换为位图，然后返回字节数组。 |
| [AsXml](../../aspose.pdf/page/asxml)() | 将当前页面转换为 utf8 编码的 xml。 |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | 计算 bbox 值 - 包含没有可见边距的内容的矩形。 |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | 将页面转换为 DSR、OMR、OCR 图像流的 PNG。 |
| [Dispose](../../aspose.pdf/page/dispose)() | 释放内存 |
| [Flatten](../../aspose.pdf/page/flatten)() | 删除页面上的所有字段并放置它们的值。 |
| [FreeMemory](../../aspose.pdf/page/freememory)() | 清除缓存数据 |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | 返回有关页面内容内部操作的通知。 （现在仅支持文本添加场景中有关段落事件的通知。） |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | 返回页面的矩形。 |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | 获取页面是否为空白的标志。 |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | 将页面转换为灰度。 |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | 使用给定的页面设备将页面发送到进程。 |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | 使用给定的页面设备将页面发送到进程。 |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | 设置页面的页面大小。 |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | 将整数值转换为相应的旋转枚举成员。 |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | 将旋转枚举成员转换为整数值。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | 自定义页眉和页脚的过程。 |

### 也可以看看

* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
