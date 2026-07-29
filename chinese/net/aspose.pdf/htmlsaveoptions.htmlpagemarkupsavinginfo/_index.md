---
title: "类 HtmlSaveOptions.HtmlPageMarkupSavingInfo。"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo 类。如果 HtmlSaveOptions 的 SplitToPages 属性，则在将 PDF 转换为 HTML 的过程中会创建多个 HTML 文件，每个转换的页面对应一个 HTML 文件。此类表示与在 PDF 转换为 HTML 时自定义保存单个 HTML 页面标记相关的一组数据。"
type: docs
weight: 5800
url: /zh/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

如果 HtmlSaveOptions 的 SplitToPages 属性，则在将 PDF 转换为 HTML 的过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此类表示与在 PDF 转换为 HTML 时自定义保存单个 HTML 页面标记相关的一组数据。

```csharp
public class HtmlPageMarkupSavingInfo
```

## 字段

| 名称 | 描述 |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | 由转换器设置。表示已保存的 HTML 作为流。 |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | 在必要时应在自定义代码中设置。此标志必须在自定义代码中设置为 "true"，如果出于某些原因提供的 html 标记应由转换器的代码而不是自定义代码进行处理，以转换器的标准方式。因此，在自定义代码中设置此标志意味着自定义代码未处理引用的文件，转换器必须自行处理。 |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | 由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性包含已保存的 HTML 页面文件的序号。该属性可在自定义代码的逻辑中用于决定如何处理或保存 HTML 页面；如果关闭了分页，则此值始终为 '1'，因为在这种情况下仅为整个源文档生成一个大的 HTML 页面。 |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | 由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性告诉自定义代码原始 PDF 的哪一页生成了已保存的 HTML 标记。如果由于某些原因原始页码未知或 SplitToPages 为 false，则此属性始终为 '0'，表示转换器无法为提供的 HTML 标记文件提供确切的原始 PDF 页码。 |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | 由转换器设置。假定的文件名由转换器传递给自定义方法的代码，可在自定义代码中用于决定如何处理或保存内容。 |

### 另请参见

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


