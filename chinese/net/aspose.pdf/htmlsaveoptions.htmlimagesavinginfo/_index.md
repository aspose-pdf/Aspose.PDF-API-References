---
title: "类 HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo 类。此类表示在 PDF 转换为 HTML 期间与外部资源图像文件保存相关的一组数据。"
type: docs
weight: 5770
url: /zh/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

此类表示与 PDF 转换为 HTML 期间外部资源图像文件保存相关的一组数据。

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | 由转换器设置。假定的文件名从转换器传递到自定义方法的代码，可在自定义代码中使用，以决定如何处理或将文件保存在哪里。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | 由转换器设置。表示已保存文件的二进制内容。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 如果出于某些原因建议的文件应由转换器的代码而非自定义代码进行处理，则必须在自定义代码中将此标志设置为 \"true\"。因此，将此设置为 true 表示自定义代码未处理引用的文件，转换器必须自行处理它（包括保存位置和在引用文件中的命名）。 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | 指示自定义代码保存的图像对应于生成的 HTML 页面文件集合中的哪一页。如果关闭分页，此值始终为 '1'，因为此情况下只生成一个 HTML 页面。 |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | 表示在 HTML 中引用的已保存图像的类型。由转换器设置，可在自定义代码中使用以决定应执行的操作 |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | 已保存的图像可以属于 HTML 本身，也可以从嵌入到 HTML 的 SVG 中提取。此属性可告知自定义代码处理图像的父级类型。它由转换器设置，可在自定义代码中使用，以决定对该图像应执行的操作（例如，自定义代码可以决定图像保存的位置或在父级内容中如何引用它）。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | 告知自定义代码已保存图像对应原始 PDF 文档的哪一页。由于可能并非原始文档的所有页面都会被保存，此值指示在原始 PDF 中的宿主页码。如果由于某种原因原始页码未知，则始终返回 “1”。 |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | 由转换器设置。假定的文件名从转换器传递到自定义方法的代码，可在自定义代码中使用，以决定如何处理或将文件保存在哪里。 |

### 另请参见

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


