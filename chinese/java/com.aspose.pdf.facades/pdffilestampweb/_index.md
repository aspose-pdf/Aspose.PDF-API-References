---
title: "PdfFileStampWeb"
linktitle: "PdfFileStampWeb"
second_title: "Aspose.PDF for Java API 参考"
description: "用于向 PDF 文件添加印章（水印或背景）的类。支持与 HttpServletResponse 配合使用。"
type: docs
weight: 550
url: /zh/java/com.aspose.pdf.facades/pdffilestampweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStampWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStampWeb extends SaveableFacade implements IPdfFileStamp
```

用于向 PDF 文件添加印章（水印或背景）的类。支持与 HttpServletResponse 配合使用。

## 字段

| 字段 | 描述 |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | 左下位置。 |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | 底部中间位置。 |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | 右下位置。 |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | 左侧位置。 |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | 右侧位置。 |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | 左上位置。 |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | 上部中间位置。 |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | 右上位置。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileStampWeb](#PdfFileStampWeb--) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-) | <p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> 向文档的页面添加页脚。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> 向文档的页面添加页脚。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> 在页面底部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> 在页面底部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> 在文档的各页底部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | 将图像添加为页面的页脚。 |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> 向页面添加页眉。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> 向文件的页面添加页眉。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> 在页面顶部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> 在页面顶部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> 在文件的各页顶部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> 在页面顶部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> 在页面上添加页码。页码可以包含 # 符号，# 将被替换为实际页码。页码位于页面底部，水平居中。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> 在页面的指定位置添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> 在页面上添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> 在文档的页面上添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> 向文件添加页码。页码文本可以包含 # 符号，# 将被替换为页面编号。页码位于页面底部，水平居中。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> 在页面的指定位置添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> 在页面上添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> 在文档的页面上添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> 在文件中添加印章。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> 关闭已打开的文件并保存更改。警告：如果指定了输入或输出流，Close() 方法不会关闭它们。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | 已弃用。 |
| [getAttachmentName](#getAttachmentName--) | 获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。 |
| [getContentDisposition](#getContentDisposition--) | 获取操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。 |
| [getInputFile](#getInputFile--) | 获取输入文件的名称和路径。 |
| [getInputStream](#getInputStream--) | 获取输入流。 |
| [getKeepSecurity](#getKeepSecurity--) | 如果为 true，则保持安全。（此功能将在后续版本中实现。） |
| [getNumberingStyle](#getNumberingStyle--) | 获取或设置页面编号样式。 |
| [getOptimizeSize](#getOptimizeSize--) | 获取或设置优化标志。 |
| [getOutputFile](#getOutputFile--) | 获取输出文件的名称和路径。 |
| [getOutputStream](#getOutputStream--) | 获取输出流。 |
| [getPageHeight](#getPageHeight--) | <p> 获取源文件中第一页的高度。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre> |
| [getPageNumberRotation](#getPageNumberRotation--) | 获取页码的旋转角度。旋转以度为单位。默认值为 0。 |
| [getPageWidth](#getPageWidth--) | <p> 获取输入文件中第一页的宽度。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre> |
| [getResponse](#getResponse--) | 获取用于存储操作结果的 Response 对象。 |
| [getSaveOptions](#getSaveOptions--) | 获取结果以 HttpResponse 形式存储时的保存选项。默认值：PdfSaveOptions。 |
| [getStampId](#getStampId--) | 下一个添加的印章的 Stamp ID（包括页眉/页脚/页码）。 |
| [getStartingNumber](#getStartingNumber--) | 获取或设置输入文件中第一页的起始编号。后续页面将从该值开始编号。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存且不进行转换。 |
| [setInputFile](#setInputFile-java.lang.String-) | 设置输入文件的名称和路径。 |
| [setInputStream](#setInputStream-java.io.InputStream-) | 设置输入流。 |
| [setKeepSecurity](#setKeepSecurity-boolean-) | 如果为 true，则保持安全。（此功能将在后续版本中实现。） |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | 获取或设置页面编号样式。 |
| [setOptimizeSize](#setOptimizeSize-boolean-) | 获取或设置优化标志。 |
| [setOutputFile](#setOutputFile-java.lang.String-) | 设置输出文件的名称和路径。 |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | 设置或设置输出流。 |
| [setPageNumberRotation](#setPageNumberRotation-float-) | 设置页码的旋转角度。旋转以度为单位。默认值为 0。 |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | 设置用于存储操作结果的 Response 对象。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 当结果存储为 HttpResponse 时设置保存选项。默认值：PdfSaveOptions。 |
| [setStampId](#setStampId-int-) | 下一个添加的印章的 Stamp ID（包括页眉/页脚/页码）。 |
| [setStartingNumber](#setStartingNumber-int-) | <p> 设置输入文件中第一页的起始编号。后续页面将从该值开始编号。例如，如果 StartingNumber 设置为 100，文档页面的编号将为 100、101、102…… </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

左下位置。

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

底部中间位置。

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

右下位置。

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

左侧位置。

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

右侧位置。

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

左上位置。

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

上部中间位置。

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

右上位置。

### PdfFileStampWeb {#PdfFileStampWeb--}
```
public PdfFileStampWeb()
```

<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-}
<p> PdfFileStamp 的构造函数。可以通过相应属性指定输入文件和输出文件。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( "input.pdf"); fileStamp.setOutputFile ( "output.pdf"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> 向文档的页面添加页脚。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> 向文档的页面添加页脚。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> 在页面底部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> 在页面底部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> 在文档的各页底部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
将图像添加为页面的页脚。

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> 向页面添加页眉。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> 向文件的页面添加页眉。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> 在页面顶部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> 在页面顶部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> 在文件的各页顶部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> 在页面顶部添加图像。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> 在页面上添加页码。页码可以包含 # 符号，# 将被替换为实际页码。页码位于页面底部，水平居中。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> 在页面的指定位置添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> 在页面上添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> 在文档的页面上添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> 向文件添加页码。页码文本可以包含 # 符号，# 将被替换为页面编号。页码位于页面底部，水平居中。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> 在页面的指定位置添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> 在页面上添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> 在文档的页面上添加页码。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> 在文件中添加印章。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> 关闭已打开的文件并保存更改。警告：如果指定了输入或输出流，Close() 方法不会关闭它们。 </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

已弃用。

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。

**Returns:**
字符串对象

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

获取操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。

**Returns:**
ContentDisposition 元素

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

获取输入文件的名称和路径。

**Returns:**
字符串对象

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

获取输入流。

**Returns:**
InputStream 对象

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

如果为 true，则保持安全。（此功能将在后续版本中实现。）

**Returns:**
布尔值

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

获取或设置页面编号样式。

**Returns:**
NumberingStyle 元素

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

获取或设置优化标志。

**Returns:**
布尔值

### getOutputFile {#getOutputFile--}
```
public String getOutputFile()
```

获取输出文件的名称和路径。

**Returns:**
字符串对象

### getOutputStream {#getOutputStream--}
```
public OutputStream getOutputStream()
```

获取输出流。

**Returns:**
OutputStream 对象

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> 获取源文件中第一页的高度。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre>

**Returns:**
float 值

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

获取页码的旋转角度。旋转以度为单位。默认值为 0。

**Returns:**
float 值

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> 获取输入文件中第一页的宽度。 </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre>

**Returns:**
float 值

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

获取用于存储操作结果的 Response 对象。

**Returns:**
HttpServletResponse 对象

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

获取结果以 HttpResponse 形式存储时的保存选项。默认值：PdfSaveOptions。

**Returns:**
SaveOptions 对象

### getStampId {#getStampId--}
```
public int getStampId()
```

下一个添加的印章的 Stamp ID（包括页眉/页脚/页码）。

**Returns:**
int 值

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

获取或设置输入文件中第一页的起始编号。后续页面将从该值开始编号。

**Returns:**
int 值

### setAttachmentName {#setAttachmentName-java.lang.String-}
当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
设置当操作结果存储到 HttpResponse 对象时内容的存储方式。可能的值：inline / attachment。默认：inline。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存且不进行转换。

### setInputFile {#setInputFile-java.lang.String-}
设置输入文件的名称和路径。

### setInputStream {#setInputStream-java.io.InputStream-}
设置输入流。

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

如果为 true，则保持安全。（此功能将在后续版本中实现。）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
获取或设置页面编号样式。

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

获取或设置优化标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setOutputFile {#setOutputFile-java.lang.String-}
设置输出文件的名称和路径。

### setOutputStream {#setOutputStream-java.io.OutputStream-}
设置或设置输出流。

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

设置页码的旋转角度。旋转以度为单位。默认值为 0。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
设置用于存储操作结果的 Response 对象。

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
当结果存储为 HttpResponse 时设置保存选项。默认值：PdfSaveOptions。

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

下一个添加的印章的 Stamp ID（包括页眉/页脚/页码）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> 设置输入文件中第一页的起始编号。后续页面将从该值开始编号。例如，如果 StartingNumber 设置为 100，文档页面的编号将为 100、101、102…… </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
