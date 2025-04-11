---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo 类。此类表示与 PDF 转换为 HTML 过程中外部资源图像文件保存相关的数据集
type: docs
weight: 5640
url: /zh/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo 类

此类表示与 PDF 转换为 HTML 过程中外部资源图像文件保存相关的数据集。

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
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | 由转换器设置。假定的文件名，从转换器传递到自定义方法的代码中。可以在自定义代码中使用，以决定如何处理或保存该文件 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | 由转换器设置。表示保存文件的二进制内容。 |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | 如果由于某种原因提议的文件应以标准转换器方式而不是自定义代码进行处理，则此标志必须在自定义代码中设置为“true”。因此，将其设置为 true 意味着自定义代码未处理引用的文件，转换器必须自行处理（在保存到某处和在引用文件中命名的两个方面）。 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | 告诉自定义代码保存的图像属于生成的 HTML 页面文件集的哪个页面。如果关闭按页面拆分，则此值始终包含 '1'，因为在这种情况下只生成一个 HTML 页面。 |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | 表示在 HTML 中引用的保存图像的类型。由转换器设置，可以在自定义代码中使用以决定应采取何种措施 |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | 保存的图像可以属于 HTML 本身或可以从嵌入到 HTML 中的 SVG 中提取。此属性可以告诉自定义代码处理图像的父级类型。由转换器设置，可以在自定义代码中使用以决定应对该图像采取何种措施（例如，自定义代码可以决定将图像保存到何处或如何在父内容中引用它）。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | 告诉自定义代码保存的图像属于原始 PDF 文档的哪个页面。由于可能不会保存原始文档的所有页面，因此此值告诉我们原始 PDF 中的主页面编号。如果由于某种原因原始页面编号未知，则始终返回 '1' |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | 由转换器设置。假定的文件名，从转换器传递到自定义方法的代码中。可以在自定义代码中使用，以决定如何处理或保存该文件 |

### 另请参阅

* 类 [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* 类 [HtmlSaveOptions](../htmlsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)