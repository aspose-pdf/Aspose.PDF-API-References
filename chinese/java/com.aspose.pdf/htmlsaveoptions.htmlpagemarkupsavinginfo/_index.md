---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Aspose.PDF for Java API 参考"
description: "如果 HtmlSaveOptions 的 SplitToPages 属性为 true，则在 PDF 转换为 HTML 的过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此类表示一组。"
type: docs
weight: 2100
url: /zh/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

如果 HtmlSaveOptions 的 SplitToPages 属性为 true，则在 PDF 转换为 HTML 期间会创建多个 HTML 文件（每个转换的页面一个 HTML 文件）。此类表示在 PDF 转换为 HTML 期间与自定义保存单个 HTML 页面标记相关的一组数据

## 方法

| 方法 | 描述 |
| --- | --- |
| [getContentStream](#getContentStream--) | 由转换器设置。表示保存的 HTML 作为流。 |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | 由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性包含已保存 HTML 页面文件的序号。该属性可在自定义代码逻辑中用于决定如何处理或保存 HTML 页面；如果关闭页面拆分，则此值始终为 '1'，因为在这种情况下只会为整个源文档生成一个大的 HTML 页面。 |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | 由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性告诉自定义代码该保存的 HTML 标记来自原始 PDF 的哪一页。如果由于某种原因原始页码未知或 SplitToPages 为 false，则此属性始终为 '0'，表示转换器无法提供对应 HTML 标记文件的确切原始 PDF 页码。 |
| [getSupposedFileName](#getSupposedFileName--) | 由转换器设置。假定的文件名，从转换器传递给自定义方法的代码。可在自定义代码中用于决定如何处理或保存内容。 |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | 在必要时应在自定义代码中设置。若因某些原因提供的 html 标记应由转换器自身的标准代码而非自定义代码处理，则必须在自定义代码中将此标志设置为 \"true\"。因此，在自定义代码中设置此标志表示自定义代码未处理引用的文件，转换器必须自行处理。 |
| [setContentStream](#setContentStream-java.io.InputStream-) | 由转换器设置。表示保存的 HTML 作为流。 |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | 在必要时应在自定义代码中设置。若因某些原因提供的 html 标记应由转换器自身的标准代码而非自定义代码处理，则必须在自定义代码中将此标志设置为 \"true\"。因此，在自定义代码中设置此标志表示自定义代码未处理引用的文件，转换器必须自行处理。 |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | 由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性包含已保存 HTML 页面文件的序号。该属性可在自定义代码逻辑中用于决定如何处理或保存 HTML 页面；如果关闭页面拆分，则此值始终为 '1'，因为在这种情况下只会为整个源文档生成一个大的 HTML 页面。 |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | 由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性告诉自定义代码该保存的 HTML 标记来自原始 PDF 的哪一页。如果由于某种原因原始页码未知或 SplitToPages 为 false，则此属性始终为 '0'，表示转换器无法提供对应 HTML 标记文件的确切原始 PDF 页码。 |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | 由转换器设置。假定的文件名，从转换器传递给自定义方法的代码。可在自定义代码中用于决定如何处理或保存内容。 |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

由转换器设置。表示保存的 HTML 作为流。

**Returns:**
InputStream 实例

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性包含已保存 HTML 页面文件的序号。该属性可在自定义代码逻辑中用于决定如何处理或保存 HTML 页面；如果关闭页面拆分，则此值始终为 '1'，因为在这种情况下只会为整个源文档生成一个大的 HTML 页面。

**Returns:**
int 值

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性告诉自定义代码该保存的 HTML 标记来自原始 PDF 的哪一页。如果由于某种原因原始页码未知或 SplitToPages 为 false，则此属性始终为 '0'，表示转换器无法提供对应 HTML 标记文件的确切原始 PDF 页码。

**Returns:**
int 值

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

由转换器设置。假定的文件名，从转换器传递给自定义方法的代码。可在自定义代码中用于决定如何处理或保存内容。

**Returns:**
字符串值

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

在必要时应在自定义代码中设置。若因某些原因提供的 html 标记应由转换器自身的标准代码而非自定义代码处理，则必须在自定义代码中将此标志设置为 \"true\"。因此，在自定义代码中设置此标志表示自定义代码未处理引用的文件，转换器必须自行处理。

**Returns:**
布尔值

### setContentStream {#setContentStream-java.io.InputStream-}
由转换器设置。表示保存的 HTML 作为流。

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

在必要时应在自定义代码中设置。若因某些原因提供的 html 标记应由转换器自身的标准代码而非自定义代码处理，则必须在自定义代码中将此标志设置为 \"true\"。因此，在自定义代码中设置此标志表示自定义代码未处理引用的文件，转换器必须自行处理。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| customProcessingCancelled |  | 布尔值 |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性包含已保存 HTML 页面文件的序号。该属性可在自定义代码逻辑中用于决定如何处理或保存 HTML 页面；如果关闭页面拆分，则此值始终为 '1'，因为在这种情况下只会为整个源文档生成一个大的 HTML 页面。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| htmlHostPageNumber |  | int 值 |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

由转换器设置。如果设置了 SplitToPages 属性，则在转换过程中会创建多个 HTML 文件（每个转换的页面对应一个 HTML 文件）。此属性告诉自定义代码该保存的 HTML 标记来自原始 PDF 的哪一页。如果由于某种原因原始页码未知或 SplitToPages 为 false，则此属性始终为 '0'，表示转换器无法提供对应 HTML 标记文件的确切原始 PDF 页码。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfHostPageNumber |  | int 值 |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
由转换器设置。假定的文件名，从转换器传递给自定义方法的代码。可在自定义代码中用于决定如何处理或保存内容。
