---
title: PdfFileStampWeb
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于向 PDF 文件添加图章水印或背景的类。
type: docs
weight: 47
url: /zh/java/com.aspose.pdf.facades/pdffilestampweb/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.APdfFileStamp

**所有已实现的接口：**
[com.aspose.pdf.facades.IPdfFileStamp](../../com.aspose.pdf.facades/ipdffilestamp)
```
public final class PdfFileStampWeb extends APdfFileStamp implements IPdfFileStamp
```

用于向 PDF 文件添加图章（水印或背景）的类。启用以使用 HttpServletResponse。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileStampWeb()](#PdfFileStampWeb--) | PdfFileStamp 的构造函数。 |
| [PdfFileStampWeb(IDocument document)](#PdfFileStampWeb-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfFileStamp 对象。 |
| [PdfFileStampWeb(IDocument document, OutputStream outputStream)](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | 在文档的基础上初始化新的 PdfFileStamp 对象。 |
| [PdfFileStampWeb(IDocument document, String outputFile)](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-) | 在文档的基础上初始化新的 PdfFileStamp 对象。 |
| [PdfFileStampWeb(InputStream inputStream, OutputStream outputStream)](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-) | PdfFileStamp 的构造函数。 |
| [PdfFileStampWeb(InputStream inputStream, OutputStream outputStream, boolean keepSecurity)](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-) | PdfFileStamp 的构造函数。 |
| [PdfFileStampWeb(String inputFile, String outputFile)](#PdfFileStampWeb-java.lang.String-java.lang.String-) | PdfFileStamp 的构造函数。 |
| [PdfFileStampWeb(String inputFile, String outputFile, boolean keepSecurity)](#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-) | PdfFileStamp 的构造函数。 |
| [PdfFileStampWeb(InputStream inputStream, HttpServletResponse response)](#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | 创建 PdfFileStampWeb，它将结果保存到 HttpResponse 对象中。 |
| [PdfFileStampWeb(String inputFile, HttpServletResponse response)](#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | 创建 PdfFileStampWeb，它将结果保存到 HttpResponse 对象中。 |
## 领域

| 场地 | 描述 |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS-BOTTOM-LEFT) | 左下位置。 |
| [POS_BOTTOM_LEFT](#POS-BOTTOM-LEFT) | 左下位置。 |
| [POS_BOTTOM_MIDDLE](#POS-BOTTOM-MIDDLE) | 底部中间位置。 |
| [POS_BOTTOM_MIDDLE](#POS-BOTTOM-MIDDLE) | 底部中间位置。 |
| [POS_BOTTOM_RIGHT](#POS-BOTTOM-RIGHT) | 右下位置。 |
| [POS_BOTTOM_RIGHT](#POS-BOTTOM-RIGHT) | 右下位置。 |
| [POS_SIDES_LEFT](#POS-SIDES-LEFT) | 左侧位置。 |
| [POS_SIDES_LEFT](#POS-SIDES-LEFT) | 左侧位置。 |
| [POS_SIDES_RIGHT](#POS-SIDES-RIGHT) | 正确的位置。 |
| [POS_SIDES_RIGHT](#POS-SIDES-RIGHT) | 正确的位置。 |
| [POS_UPPER_LEFT](#POS-UPPER-LEFT) | 上让位置。 |
| [POS_UPPER_LEFT](#POS-UPPER-LEFT) | 上让位置。 |
| [POS_UPPER_MIDDLE](#POS-UPPER-MIDDLE) | 中上位置。 |
| [POS_UPPER_MIDDLE](#POS-UPPER-MIDDLE) | 中上位置。 |
| [POS_UPPER_RIGHT](#POS-UPPER-RIGHT) | 右上位置。 |
| [POS_UPPER_RIGHT](#POS-UPPER-RIGHT) | 右上位置。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addFooter(FormattedText formattedText, float bottomMargin)](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | 将页脚添加到文档的页面。 |
| [addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | 将页脚添加到文档的页面。 |
| [addFooter(InputStream imageStream, float bottomMargin)](#addFooter-java.io.InputStream-float-) | 添加图像作为页面的页脚。 |
| [addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-java.io.InputStream-float-float-float-) | 添加图像作为页面的页脚。 |
| [addFooter(String imageFile, float bottomMargin)](#addFooter-java.lang.String-float-) | 将图像作为页脚添加到文档的页面。 |
| [addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin)](#addFooter-java.lang.String-float-float-float-) | 添加图像作为页面的页脚。 |
| [addHeader(FormattedText formattedText, float topMargin)](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | 向页面添加页眉。 |
| [addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | 将页眉添加到文件页面。 |
| [addHeader(InputStream imageStream, float topMargin)](#addHeader-java.io.InputStream-float-) | 在页面上添加图像作为标题。 |
| [addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin)](#addHeader-java.io.InputStream-float-float-float-) | 在页面顶部添加图像。 |
| [addHeader(String imageFile, float topMargin)](#addHeader-java.lang.String-float-) | 将图像作为页眉添加到文件的页面。 |
| [addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin)](#addHeader-java.lang.String-float-float-float-) | 在页面上添加图像作为标题。 |
| [addPageNumber(FormattedText formattedText)](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | 向页面添加页码。 |
| [addPageNumber(FormattedText formattedText, float x, float y)](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | 在页面的指定位置添加页码。 |
| [addPageNumber(FormattedText formattedText, int position)](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | 向页面添加页码。 |
| [addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | 将页码添加到文档的页面。 |
| [addPageNumber(String formatString)](#addPageNumber-java.lang.String-) | 将页码添加到文件。 |
| [addPageNumber(String formatString, float x, float y)](#addPageNumber-java.lang.String-float-float-) | 在页面的指定位置添加页码。 |
| [addPageNumber(String formatString, int position)](#addPageNumber-java.lang.String-int-) | 向页面添加页码。 |
| [addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)](#addPageNumber-java.lang.String-int-float-float-float-float-) | 将页码添加到文档的页面。 |
| [addStamp(Stamp stamp)](#addStamp-com.aspose.pdf.facades.Stamp-) | 向文件添加戳记。 |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 关闭打开的文件并保存更改。 |
| [dispose()](#dispose--) | 关闭此实例使用的所有资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachmentName()](#getAttachmentName--) | 当操作结果作为附件存储到 HttpResponse 对象时获取附件名称。 |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | 获取当操作结果存储到 HttpResponse 对象时将如何存储内容。 |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getInputFile()](#getInputFile--) | 获取输入文件的名称和路径。 |
| [getInputStream()](#getInputStream--) | 获取输入流。 |
| [getKeepSecurity()](#getKeepSecurity--) | 如果为真，则保持安全。 |
| [getNumberingStyle()](#getNumberingStyle--) | 获取或设置页码样式。 |
| [getOptimizeSize()](#getOptimizeSize--) | 获取或设置优化标志。 |
| [getOutputFile()](#getOutputFile--) | 获取输出文件的名称和路径。 |
| [getOutputStream()](#getOutputStream--) | 获取输出流。 |
| [getPageHeight()](#getPageHeight--) | 获取源文件第一页的高度。 |
| [getPageNumberRotation()](#getPageNumberRotation--) | 获取页码的旋转。 |
| [getPageWidth()](#getPageWidth--) | 获取输入文件中第一页的宽度。 |
| [getResponse()](#getResponse--) | 获取将存储操作结果的 Response 对象。 |
| [getSaveOptions()](#getSaveOptions--) | 当结果存储为 HttpResponse 时获取保存选项。 |
| [getStampId()](#getStampId--) | 下一个添加的图章的图章 ID（包括页眉/页眉/页码）。 |
| [getStartingNumber()](#getStartingNumber--) | 获取或设置输入文件中第一页的起始编号。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定的流。 |
| [save(String destFile)](#save-java.lang.String-) | 将 PDF 文档保存到指定文件。 |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件名称。 |
| [setContentDisposition(int value)](#setContentDisposition-int-) | 设置当操作结果存储到 HttpResponse 对象时将如何存储内容。 |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setInputFile(String value)](#setInputFile-java.lang.String-) | 设置输入文件的名称和路径。 |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | 设置输入流。 |
| [setKeepSecurity(boolean value)](#setKeepSecurity-boolean-) | 如果为真，则保持安全。 |
| [setNumberingStyle(int value)](#setNumberingStyle-int-) | 获取或设置页码样式。 |
| [setOptimizeSize(boolean value)](#setOptimizeSize-boolean-) | 获取或设置优化标志。 |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | 设置输出文件的名称和路径。 |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | 设置或设置输出流。 |
| [setPageNumberRotation(float value)](#setPageNumberRotation-float-) | 设置页码的旋转。 |
| [setResponse(HttpServletResponse value)](#setResponse-javax.servlet.http.HttpServletResponse-) | 设置将存储操作结果的 Response 对象。 |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 当结果存储为 HttpResponse 时设置保存选项。 |
| [setStampId(int value)](#setStampId-int-) | 下一个添加的图章的图章 ID（包括页眉/页眉/页码）。 |
| [setStartingNumber(int value)](#setStartingNumber-int-) | 设置输入文件第一页的起始编号。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileStampWeb() {#PdfFileStampWeb--}
```
public PdfFileStampWeb()
```


PdfFileStamp 的构造函数。输入文件和输出文件可以通过相应的属性指定。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp();
 fileStamp.setInputFile ( "input.pdf");
 fileStamp.setOutputFile ( "output.pdf");
```

### PdfFileStampWeb(IDocument document) {#PdfFileStampWeb-com.aspose.pdf.IDocument-}
```
public PdfFileStampWeb(IDocument document)
```


在文档的基础上初始化新的 PdfFileStamp 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### PdfFileStampWeb(IDocument document, OutputStream outputStream) {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public PdfFileStampWeb(IDocument document, OutputStream outputStream)
```


在文档的基础上初始化新的 PdfFileStamp 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |
| outputStream | java.io.OutputStream | 输出流。 |

### PdfFileStampWeb(IDocument document, String outputFile) {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileStampWeb(IDocument document, String outputFile)
```


在文档的基础上初始化新的 PdfFileStamp 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |
| outputFile | java.lang.String | 输出文件名和路径。 |

### PdfFileStampWeb(InputStream inputStream, OutputStream outputStream) {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileStampWeb(InputStream inputStream, OutputStream outputStream)
```


PdfFileStamp 的构造函数。

--------------------

```
InputStream input = new FileInputStream("input.pdf");
 OutputStream output = new FileInputStream("output.pdf");
 PdfFileStamp stamp = new PdfFileStamp(input, output);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入流。 |
| outputStream | java.io.OutputStream | 输出流。 |

### PdfFileStampWeb(InputStream inputStream, OutputStream outputStream, boolean keepSecurity) {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-}
```
public PdfFileStampWeb(InputStream inputStream, OutputStream outputStream, boolean keepSecurity)
```


PdfFileStamp 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入流。 |
| outputStream | java.io.OutputStream | 输出流。 |
| keepSecurity | boolean | 如果属实，请保持安全。 |

### PdfFileStampWeb(String inputFile, String outputFile) {#PdfFileStampWeb-java.lang.String-java.lang.String-}
```
public PdfFileStampWeb(String inputFile, String outputFile)
```


PdfFileStamp 的构造函数。

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件名和路径。 |
| outputFile | java.lang.String | 输出文件名和路径。 |

### PdfFileStampWeb(String inputFile, String outputFile, boolean keepSecurity) {#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-}
```
public PdfFileStampWeb(String inputFile, String outputFile, boolean keepSecurity)
```


PdfFileStamp 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 输入文件名和路径。 |
| outputFile | java.lang.String | 输出文件名和路径。 |
| keepSecurity | boolean | 如果属实，请保持安全。 |

### PdfFileStampWeb(InputStream inputStream, HttpServletResponse response) {#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
```
public PdfFileStampWeb(InputStream inputStream, HttpServletResponse response)
```


创建 PdfFileStampWeb，它将结果保存到 HttpResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 带有输入文档的流。 |
| response | javax.servlet.http.HttpServletResponse | 保存结果的 HttpResponse 对象。 |

### PdfFileStampWeb(String inputFile, HttpServletResponse response) {#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
```
public PdfFileStampWeb(String inputFile, HttpServletResponse response)
```


创建 PdfFileStampWeb，它将结果保存到 HttpResponse 对象中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 源文件名。 |
| response | javax.servlet.http.HttpServletResponse | 保存结果的 HttpResponse 对象。 |

### POS_BOTTOM_LEFT {#POS-BOTTOM-LEFT}
```
public static final int POS_BOTTOM_LEFT
```


左下位置。

### POS_BOTTOM_LEFT {#POS-BOTTOM-LEFT}
```
public static final int POS_BOTTOM_LEFT
```


左下位置。

### POS_BOTTOM_MIDDLE {#POS-BOTTOM-MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```


底部中间位置。

### POS_BOTTOM_MIDDLE {#POS-BOTTOM-MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```


底部中间位置。

### POS_BOTTOM_RIGHT {#POS-BOTTOM-RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```


右下位置。

### POS_BOTTOM_RIGHT {#POS-BOTTOM-RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```


右下位置。

### POS_SIDES_LEFT {#POS-SIDES-LEFT}
```
public static final int POS_SIDES_LEFT
```


左侧位置。

### POS_SIDES_LEFT {#POS-SIDES-LEFT}
```
public static final int POS_SIDES_LEFT
```


左侧位置。

### POS_SIDES_RIGHT {#POS-SIDES-RIGHT}
```
public static final int POS_SIDES_RIGHT
```


正确的位置。

### POS_SIDES_RIGHT {#POS-SIDES-RIGHT}
```
public static final int POS_SIDES_RIGHT
```


正确的位置。

### POS_UPPER_LEFT {#POS-UPPER-LEFT}
```
public static final int POS_UPPER_LEFT
```


上让位置。

### POS_UPPER_LEFT {#POS-UPPER-LEFT}
```
public static final int POS_UPPER_LEFT
```


上让位置。

### POS_UPPER_MIDDLE {#POS-UPPER-MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```


中上位置。

### POS_UPPER_MIDDLE {#POS-UPPER-MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```


中上位置。

### POS_UPPER_RIGHT {#POS-UPPER-RIGHT}
```
public static final int POS_UPPER_RIGHT
```


右上位置。

### POS_UPPER_RIGHT {#POS-UPPER-RIGHT}
```
public static final int POS_UPPER_RIGHT
```


右上位置。

### addFooter(FormattedText formattedText, float bottomMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
```
public void addFooter(FormattedText formattedText, float bottomMargin)
```


将页脚添加到文档的页面。

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addFooter(new FormattedText("Foot of the page"), 10);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 包含页脚文本和文本属性的 FormattedText 对象。 |
| bottomMargin | float | 页面顶部的边距。 |

### addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
```
public void addFooter(FormattedText formattedText, float bottomMargin, float leftMargin, float rightMargin)
```


将页脚添加到文档的页面。

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 包含页脚文本和文本属性的 FormattedText 对象。 |
| bottomMargin | float | 页面底部的边距。 |
| leftMargin | float | 页面左侧的边距。 |
| rightMargin | float | 页面右侧的边距。 |

### addFooter(InputStream imageStream, float bottomMargin) {#addFooter-java.io.InputStream-float-}
```
public void addFooter(InputStream imageStream, float bottomMargin)
```


添加图像作为页面的页脚。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream("test.jpg");
 fileStamp.addFooter(input, 50);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 流包含图像数据。 |
| bottomMargin | float | 页面底部的边距。 |

### addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-java.io.InputStream-float-float-float-}
```
public void addFooter(InputStream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```


添加图像作为页面的页脚。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream("test.jpg");
 fileStamp.addFooter(input, 50, 50, 50);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 流包含图像数据。 |
| bottomMargin | float | 页面底部的边距。 |
| leftMargin | float | 页面左侧的边距。 |
| rightMargin | float | 页面右侧的边距。 |

### addFooter(String imageFile, float bottomMargin) {#addFooter-java.lang.String-float-}
```
public void addFooter(String imageFile, float bottomMargin)
```


将图像作为页脚添加到文档的页面。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 fileStamp.addFooter("image.jpg", 50);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | java.lang.String | 图像文件名和路径。 |
| bottomMargin | float | 页面底部的边距。 |

### addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin) {#addFooter-java.lang.String-float-float-float-}
```
public void addFooter(String imageFile, float bottomMargin, float leftMargin, float rightMargin)
```


添加图像作为页面的页脚。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | java.lang.String | 图片文件名和路径。 |
| bottomMargin | float | 页面底部的边距。 |
| leftMargin | float | 页面左侧的边距。 |
| rightMargin | float | 页面右侧的边距。 |

### addHeader(FormattedText formattedText, float topMargin) {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
```
public void addHeader(FormattedText formattedText, float topMargin)
```


向页面添加页眉。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.addHeader(new FormattedText("Head of the page"), 50);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 标题文本和文本属性。 |
| topMargin | float | 页面顶部的边距。 |

### addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin) {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
```
public void addHeader(FormattedText formattedText, float topMargin, float leftMargin, float rightMargin)
```


将页眉添加到文件页面。

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 包含页面文本及其属性的格式化文本对象。 |
| topMargin | float | 页面顶部的边距。 |
| leftMargin | float | 页面左侧的边距。 |
| rightMargin | float | 页面右侧的边距。 |

### addHeader(InputStream imageStream, float topMargin) {#addHeader-java.io.InputStream-float-}
```
public void addHeader(InputStream imageStream, float topMargin)
```


在页面上添加图像作为标题。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream("test.jpg");
 fileStamp.addHeader(input, 50);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 图像流。 |
| topMargin | float | 页面顶部的边距。 |

### addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin) {#addHeader-java.io.InputStream-float-float-float-}
```
public void addHeader(InputStream inputStream, float topMargin, float leftMargin, float rightMargin)
```


在页面顶部添加图像。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 InputStream input = new FileInputStream("test.jpg");
 fileStamp.addHeader(input, 50, 100, 100);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 包含图像数据的流。 |
| topMargin | float | 页面顶部的边距。 |
| leftMargin | float | 页面左侧的边距。 |
| rightMargin | float | 页面右侧的边距。 |

### addHeader(String imageFile, float topMargin) {#addHeader-java.lang.String-float-}
```
public void addHeader(String imageFile, float topMargin)
```


将图像作为页眉添加到文件的页面。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 fileStamp.addHeader("image.jpg", 50);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | java.lang.String | 图像文件的路径。 |
| topMargin | float | 页面顶部的边距。 |

### addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin) {#addHeader-java.lang.String-float-float-float-}
```
public void addHeader(String imageFile, float topMargin, float leftMargin, float rightMargin)
```


在页面上添加图像作为标题。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
 fileStamp.addHeader("image.jpg", 50, 100, 100);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | java.lang.String | 图像文件的路径。 |
| topMargin | float | 页面顶部的边距。 |
| leftMargin | float | 页面左侧的边距。 |
| rightMargin | float | 页面右侧的边距。 |

### addPageNumber(FormattedText formattedText) {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
```
public void addPageNumber(FormattedText formattedText)
```


向页面添加页码。页码可能包含\将被页码替换的符号。页码位于页面底部，水平居中。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber(new FormattedText("Page #"));
  fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 页码的格式字符串表示为 FormattedText。 |

### addPageNumber(FormattedText formattedText, float x, float y) {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
```
public void addPageNumber(FormattedText formattedText, float x, float y)
```


在页面的指定位置添加页码。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.addPageNumber(new FormattedText("Page  #"), 123, 357);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 表示页码格式和文本属性的格式化文本。格式字符串可以包含\将被页码替换的符号。 |
| x | float | 页码的 X 坐标。 |
| y | float | 页码的 Y 坐标。 |

### addPageNumber(FormattedText formattedText, int position) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
```
public void addPageNumber(FormattedText formattedText, int position)
```


向页面添加页码。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight);
  fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 包含页码格式和文本属性的 FormattedText 对象。这段文字可能包含\将替换为页码。 |
| position | int | 页码将放置在页面上的位置。 0-中下，1-右下，2-右上，3-右侧，4-中上，5-左下，6-左侧，7-左上。您可以使用以下常量：PosBottomMiddle = 0、PosBottomRight = 1、PosUpperRight = 2、PosSidesRight = 3、PosUpperMiddle、PosBottomLeft = 5、PosSidesLeft、PosUpperLeft |

### addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public void addPageNumber(FormattedText formattedText, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


将页码添加到文档的页面。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200);
  fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 表示页码格式和文本属性的 FormattedText 对象。 |
| position | int | 页码将放置在页面上的位置。 0-中下，1-右下，2-右上，3-右侧，4-中上，5-左下，6-左侧，7-左上。您可以使用以下常量：PosBottomMiddle = 0、PosBottomRight = 1、PosUpperRight = 2、PosSidesRight = 3、PosUpperMiddle、PosBottomLeft = 5、PosSidesLeft、PosUpperLeft |
| leftMargin | float | 页面左边缘的边距。 |
| rightMargin | float | 页面右边缘的边距。 |
| topMargin | float | 页面上边缘的边距。 |
| bottomMargin | float | 页面底部边缘的边距。 |

### addPageNumber(String formatString) {#addPageNumber-java.lang.String-}
```
public void addPageNumber(String formatString)
```


将页码添加到文件。页码文本可能包含\将替换为页码的符号。页码位于页面底部，水平居中。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber("Page #");
  fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatString | java.lang.String | 页码文字 |

### addPageNumber(String formatString, float x, float y) {#addPageNumber-java.lang.String-float-float-}
```
public void addPageNumber(String formatString, float x, float y)
```


在页面的指定位置添加页码。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 fileStamp.addPageNumber(new FormattedText("Page  #"), 123, 357);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatString | java.lang.String | 格式化字符串。格式字符串可以包含\将被页码替换的符号。 |
| x | float | 页码的 X 坐标。 |
| y | float | 页码的 Y 坐标。 |

### addPageNumber(String formatString, int position) {#addPageNumber-java.lang.String-int-}
```
public void addPageNumber(String formatString, int position)
```


向页面添加页码。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight);
  fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatString | java.lang.String | 页码的格式。这段文字可能包含\将替换为页码。 |
| position | int | 页码将放置在页面上的位置。 0-中下，1-右下，2-右上，3-右侧，4-中上，5-左下，6-左侧，7-左上。您可以使用以下常量：PosBottomMiddle = 0、PosBottomRight = 1、PosUpperRight = 2、PosSidesRight = 3、PosUpperMiddle、PosBottomLeft = 5、PosSidesLeft、PosUpperLeft |

### addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin) {#addPageNumber-java.lang.String-int-float-float-float-float-}
```
public void addPageNumber(String formatString, int position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


将页码添加到文档的页面。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200);
  fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatString | java.lang.String | 页码的格式字符串。 |
| position | int | 页码将放置在页面上的位置。 0-中下，1-右下，2-右上，3-右侧，4-中上，5-左下，6-左侧，7-左上。您可以使用以下常量：PosBottomMiddle = 0、PosBottomRight = 1、PosUpperRight = 2、PosSidesRight = 3、PosUpperMiddle、PosBottomLeft = 5、PosSidesLeft、PosUpperLeft |
| leftMargin | float | 页面左边缘的边距。 |
| rightMargin | float | 页面右边缘的边距。 |
| topMargin | float | 页面上边缘的边距。 |
| bottomMargin | float | 页面底部边缘的边距。 |

### addStamp(Stamp stamp) {#addStamp-com.aspose.pdf.facades.Stamp-}
```
public void addStamp(Stamp stamp)
```


向文件添加戳记。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  Stamp stamp = new com.aspose.pdf.facades.Stamp();
  stamp.setOrigin(140, 400);
  stamp.setImageSize(50, 50);
  stamp.setOpacity ( 0.8f);
  stamp.isBackground ( true);
  stamp.bindImage("image.jpg");
  fileStamp.addStamp(stamp);
  fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stamp | [Stamp](../../com.aspose.pdf.facades/stamp) | 邮票对象。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcStream | java.io.InputStream | PDF文件流。 |
| password | java.lang.String | PDF文档的密码。 |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件。 |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcFile | java.lang.String | PDF文件 |
| password | java.lang.String | PDF文档的密码。 |

### close() {#close--}
```
public void close()
```


关闭打开的文件并保存更改。警告。如果指定了输入或输出流，则它们不会被 Close() 方法关闭。

--------------------

```
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
 //do some work... 
 stamp.close();
```

### dispose() {#dispose--}
```
public void dispose()
```


关闭此实例使用的所有资源。

此方法已过时，请改用 close() 。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


当操作结果作为附件存储到 HttpResponse 对象时获取附件名称。

**退货：**
java.lang.String - 字符串对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


获取当操作结果存储到 HttpResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**退货：**
int - ContentDisposition 元素
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


获取输入文件的名称和路径。

**退货：**
java.lang.String - 字符串对象
### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```


获取输入流。

**退货：**
java.io.InputStream - InputStream 对象
### getKeepSecurity() {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```


如果为真，则保持安全。 （此功能将在下一版本中实现）。

**退货：**
boolean - 布尔值
### getNumberingStyle() {#getNumberingStyle--}
```
public int getNumberingStyle()
```


获取或设置页码样式。可能的值：NumeralsArabic、NumeralsRomanUppercase、NumeralsRomanLowercase、LettersAppercase、LettersLowercase

**退货：**
int - NumberingStyle 元素
### getOptimizeSize() {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```


获取或设置优化标志。如果设置此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。这允许减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。默认值：假。

**退货：**
boolean - 布尔值
### getOutputFile() {#getOutputFile--}
```
public String getOutputFile()
```


获取输出文件的名称和路径。

**退货：**
java.lang.String - 字符串对象
### getOutputStream() {#getOutputStream--}
```
public OutputStream getOutputStream()
```


获取输出流。

**退货：**
java.io.OutputStream - OutputStream 对象
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


获取源文件第一页的高度。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  System.out.println("Height = " + fileStamp.getPageHeight());
  fileStamp.close();
```

**退货：**
float - 浮点值
### getPageNumberRotation() {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```


获取页码的旋转。旋转以度为单位。默认为 0。

**退货：**
float - 浮点值
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


获取输入文件中第一页的宽度。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  System.out.println("Width = " + fileStamp.getPageWidth());
  fileStamp.close();
```

**退货：**
float - 浮点值
### getResponse() {#getResponse--}
```
public HttpServletResponse getResponse()
```


获取将存储操作结果的 Response 对象。

**退货：**
javax.servlet.http.HttpServletResponse - HttpServletResponse 对象
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


当结果存储为 HttpResponse 时获取保存选项。默认值：PdfSaveOptions。

**退货：**
[SaveOptions](../../com.aspose.pdf/saveoptions) - 保存选项对象
### getStampId() {#getStampId--}
```
public int getStampId()
```


下一个添加的图章的图章 ID（包括页眉/页眉/页码）。

**退货：**
int - 整数值
### getStartingNumber() {#getStartingNumber--}
```
public int getStartingNumber()
```


获取或设置输入文件中第一页的起始编号。下一页将从该值开始编号。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


将 PDF 文档保存到指定的流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destStream | java.io.OutputStream | 目标流。 |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


将 PDF 文档保存到指定文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| destFile | java.lang.String | 目标文件。 |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName(String value)
```


当操作结果作为附件存储到 HttpResponse 对象时，设置附件名称。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int value)
```


设置当操作结果存储到 HttpResponse 对象时将如何存储内容。可能的值：内联/附件。默认值：内联。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ContentDisposition 元素 |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat value)
```


设置 PDF 文件格式。结果文件将以指定的文件格式保存。如果未指定此属性，则文件将以默认 PDF 格式保存而不进行转换。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) | PdfFormat 元素 |

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```


设置输入文件的名称和路径。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


设置输入流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流对象 |

### setKeepSecurity(boolean value) {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```


如果为真，则保持安全。 （此功能将在下一版本中实现）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setNumberingStyle(int value) {#setNumberingStyle-int-}
```
public void setNumberingStyle(int value)
```


获取或设置页码样式。可能的值：NumeralsArabic、NumeralsRomanUppercase、NumeralsRomanLowercase、LettersAppercase、LettersLowercase

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | NumberingStyle 元素 |

### setOptimizeSize(boolean value) {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```


获取或设置优化标志。如果设置此标志，则结果文件中的相等资源流将合并到一个 PDF 对象中。这允许减少生成的文件大小，但可能会导致执行速度变慢和内存需求增加。默认值：假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


设置输出文件的名称和路径。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


设置或设置输出流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.OutputStream | 输出流对象 |

### setPageNumberRotation(float value) {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```


设置页码的旋转。旋转以度为单位。默认为 0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setResponse(HttpServletResponse value) {#setResponse-javax.servlet.http.HttpServletResponse-}
```
public void setResponse(HttpServletResponse value)
```


设置将存储操作结果的 Response 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | javax.servlet.http.HttpServletResponse | HttpServletResponse 对象 |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


当结果存储为 HttpResponse 时设置保存选项。默认值：PdfSaveOptions。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | 保存选项对象 |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


下一个添加的图章的图章 ID（包括页眉/页眉/页码）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setStartingNumber(int value) {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```


设置输入文件第一页的起始编号。下一页将从该值开始编号。例如，如果 StartingNumber 设置为 100，则文档页面的编号将是 100、101、102...

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
  fileStamp.setStartingNumber( 100);
  fileStamp.addPageNumber("Page #");
  fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
