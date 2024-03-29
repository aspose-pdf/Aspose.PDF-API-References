---
title: HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API 参考
description: 如果 HtmlSaveOptions 的 SplitToPages 属性则在将 PDF 转换为 HTML 期间会创建多个 HTML 文件每个转换的页面一个 HTML 文件  此类表示在将 PDF 转换为 HTML 期间与自定义保存一个 HTML 页面的标记 相关的一组数据
type: docs
weight: 3540
url: /zh/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

如果 HtmlSaveOptions 的 SplitToPages 属性，则在将 PDF 转换为 HTML 期间会创建多个 HTML 文件（每个转换的页面一个 HTML 文件） 。 此类表示在将 PDF 转换为 HTML 期间与自定义保存一个 HTML 页面的标记 相关的一组数据

```csharp
public class HtmlPageMarkupSavingInfo
```

## 字段

| 姓名 | 描述 |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlpagemarkupsavinginfo/contentstream) | 由转换器设置。 表示保存的 HTML 为流 |
| [CustomProcessingCancelled](../../aspose.pdf/htmlpagemarkupsavinginfo/customprocessingcancelled) | 应在必要时在自定义代码中设置。 如果出于某些原因 提供的 html 标记不应使用自定义代码处理，而是 使用转换器的代码本身以转换器方式的标准处理，则此标志必须在自定义代码中设置为“true”。 因此，如果在自定义代码中设置此标志意味着 自定义代码没有处理引用的文件， 转换器必须自己处理它 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlpagemarkupsavinginfo/htmlhostpagenumber) | 由转换器设置。 如果设置 SplitToPages 属性，则在转换创建期间会创建多个 HTML 文件（每个转换页面一个 HTML 文件） 。此属性包含已保存 HTML 页面文件的序号。 该属性可用于自定义代码的逻辑 来决定如何处理或保存 HTML 页面和 如果关闭页面拆分，此值始终包含 '1' 因为在在这种情况下，整个源文档只生成一个大 HTML 页面 。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlpagemarkupsavinginfo/pdfhostpagenumber) | 由转换器设置。 如果设置了 SplitToPages 属性，则在创建转换期间会创建多个 HTML 文件（每个转换后的页面一个 HTML 文件） 。 此属性告诉自定义代码从创建原始 PDF 的哪个页面保存的 HTML 标记. 如果由于某种原因原始页码未知或SplitOnPages = false，则此属性始终包含'0' 表示转换器无法为提供的HTML标记文件提供精确的原始PDF页码。 |
| [SupposedFileName](../../aspose.pdf/htmlpagemarkupsavinginfo/supposedfilename) | 由转换器设置。 从转换器到自定义方法代码的假定文件名 可在自定义代码中用于决定如何处理或保存内容的位置 |

### 也可以看看

* class [HtmlSaveOptions](../htmlsaveoptions)
* 命名空间 [Aspose.Pdf](../../aspose.pdf)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
