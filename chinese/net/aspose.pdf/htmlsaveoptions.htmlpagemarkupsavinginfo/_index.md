---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo 类。如果 HtmlSaveOptions 的 SplitToPages 属性为真，则在将 PDF 转换为 HTML 时，会为每个转换的页面创建多个 HTML 文件（每个 HTML 文件对应一个转换的页面）。此类表示与在将 PDF 转换为 HTML 时自定义保存一个 HTML 页面标记相关的数据集。
type: docs
weight: 5670
url: /zh/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo 类

如果 HtmlSaveOptions 的 SplitToPages 属性为真，则在将 PDF 转换为 HTML 时，会为每个转换的页面创建多个 HTML 文件（每个 HTML 文件对应一个转换的页面）。此类表示与在将 PDF 转换为 HTML 时自定义保存一个 HTML 页面标记相关的数据集。

```csharp
public class HtmlPageMarkupSavingInfo
```

## 字段

| 名称 | 描述 |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | 由转换器设置。表示保存的 HTML 作为流 |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | 在必要时应在自定义代码中设置。如果由于某种原因提供的 HTML 标记应使用转换器的代码而不是自定义代码进行处理，则此标志必须在自定义代码中设置为“true”。因此，在自定义代码中设置此标志意味着自定义代码没有处理引用的文件，转换器必须自行处理。 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | 由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个 HTML 文件对应一个转换的页面）。此属性包含保存的 HTML 页面文件的序号。该属性可用于自定义代码的逻辑，以决定如何处理或保存 HTML 页面。如果关闭页面拆分，则此值始终为 '1'，因为在这种情况下，仅为整个源文档生成一个大的 HTML 页面。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | 由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个 HTML 文件对应一个转换的页面）。此属性告诉自定义代码保存的 HTML 标记是从原始 PDF 的哪一页创建的。如果原始页码由于某种原因未知或 SplitOnPages=false，则此属性始终为 '0'，这表示转换器无法为提供的 HTML 标记文件提供确切的原始 PDF 页码。 |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | 由转换器设置。假定的文件名，从转换器传递到自定义方法的代码中。可用于自定义代码以决定如何处理或保存内容。 |

### 另请参阅

* 类 [HtmlSaveOptions](../htmlsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)