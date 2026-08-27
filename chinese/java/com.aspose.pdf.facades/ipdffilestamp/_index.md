---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Aspose.PDF for Java API 参考"
description: "用于向 PDF 文件添加印章（水印或背景）的接口。"
type: docs
weight: 320
url: /zh/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

用于向 PDF 文件添加印章（水印或背景）的接口。

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

## 方法

| 方法 | 描述 |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | 向文档的页面添加页脚。 |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | 向文档的页面添加页脚。 |
| [addFooter](#addFooter-java.io.InputStream-float-) | 将图像添加为页面的页脚。 |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | 将图像添加为页面的页脚。 |
| [addFooter](#addFooter-java.lang.String-float-) | 将图像添加为文档页面的页脚。 |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | 将图像添加为页面的页脚。 |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | 向页面添加页眉。 |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | 向文件的页面添加页眉。 |
| [addHeader](#addHeader-java.io.InputStream-float-) | 将图像添加为页面的页眉。 |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | 在页面顶部添加图像。 |
| [addHeader](#addHeader-java.lang.String-float-) | 将图像添加为文件页面的页眉。 |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | 将图像添加为页面的页眉。 |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | 向页面添加页码。 |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | 在页面的指定位置添加页码。 |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | 向页面添加页码。 |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | 向文档的页面添加页码。 |
| [addPageNumber](#addPageNumber-java.lang.String-) | 向文件添加页码。 |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | 在页面的指定位置添加页码。 |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | 向页面添加页码。 |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | 向文档的页面添加页码。 |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | 向文件添加印章。 |
| [close](#close--) | 关闭已打开的文件并保存更改。 |
| [dispose](#dispose--) | 已弃用。 |
| [getAttachmentName](#getAttachmentName--) | 获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。 |
| [getContentDisposition](#getContentDisposition--) | 获取当操作结果存储到 HttpResponse 对象时内容的存储方式。 |
| [getDocument](#getDocument--) | 获取 PdfFileStamp 正在处理的文档。 |
| [getInputFile](#getInputFile--) | 获取输入文件的名称和路径。 |
| [getInputStream](#getInputStream--) | 获取输入流。 |
| [getKeepSecurity](#getKeepSecurity--) | 如果为 true，则保持安全性。 |
| [getOutputFile](#getOutputFile--) | 获取输出文件的名称和路径。 |
| [getOutputStream](#getOutputStream--) | 获取输出流。 |
| [getPageHeight](#getPageHeight--) | 获取 souorce 文件中第一页的高度。 |
| [getPageNumberRotation](#getPageNumberRotation--) | 获取页面编号的旋转角度。 |
| [getPageWidth](#getPageWidth--) | 获取输入文件中第一页的宽度。 |
| [getSaveOptions](#getSaveOptions--) | 获取当结果存储为 HttpResponse 时的保存选项。 |
| [getStartingNumber](#getStartingNumber--) | 获取或设置输入文件中第一页的起始编号。 |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | 当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。 |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | 设置当操作结果存储到 HttpResponse 对象时内容的存储方式。 |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | 设置 PDF 文件格式。 |
| [setInputFile](#setInputFile-java.lang.String-) | 设置输入文件的名称和路径。 |
| [setInputStream](#setInputStream-java.io.InputStream-) | 设置输入流。 |
| [setKeepSecurity](#setKeepSecurity-boolean-) | 设置保持安全性 |
| [setOutputFile](#setOutputFile-java.lang.String-) | 设置输出文件的名称和路径。 |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | 设置或设置输出流。 |
| [setPageNumberRotation](#setPageNumberRotation-float-) | 设置页面编号的旋转角度。 |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | 设置当结果存储为 HttpResponse 时的保存选项。 |
| [setStartingNumber](#setStartingNumber-int-) | 设置输入文件中第一页的起始编号。 |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

左下位置。

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

底部中间位置。

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

右下位置。

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

左侧位置。

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

右侧位置。

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

左上位置。

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

上部中间位置。

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

右上位置。

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
向文档的页面添加页脚。

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
向文档的页面添加页脚。

### addFooter {#addFooter-java.io.InputStream-float-}
将图像添加为页面的页脚。

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
将图像添加为页面的页脚。

### addFooter {#addFooter-java.lang.String-float-}
将图像添加为文档页面的页脚。

### addFooter {#addFooter-java.lang.String-float-float-float-}
将图像添加为页面的页脚。

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
向页面添加页眉。

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
向文件的页面添加页眉。

### addHeader {#addHeader-java.io.InputStream-float-}
将图像添加为页面的页眉。

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
在页面顶部添加图像。

### addHeader {#addHeader-java.lang.String-float-}
将图像添加为文件页面的页眉。

### addHeader {#addHeader-java.lang.String-float-float-float-}
将图像添加为页面的页眉。

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
向页面添加页码。

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
在页面的指定位置添加页码。

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
向页面添加页码。

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
向文档的页面添加页码。

### addPageNumber {#addPageNumber-java.lang.String-}
向文件添加页码。

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
在页面的指定位置添加页码。

### addPageNumber {#addPageNumber-java.lang.String-int-}
向页面添加页码。

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
向文档的页面添加页码。

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
向文件添加印章。

### close {#close--}
```
void close()
```

关闭已打开的文件并保存更改。

### dispose {#dispose--}
```
@Deprecated void dispose()
```

已弃用。

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

获取操作结果以附件形式存储到 HttpResponse 对象时的附件名称。

**Returns:**
字符串值

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

获取当操作结果存储到 HttpResponse 对象时内容的存储方式。

**Returns:**
ContentDisposition 元素

### getDocument {#getDocument--}
```
IDocument getDocument()
```

获取 PdfFileStamp 正在处理的文档。

**Returns:**
IDocument 对象

### getInputFile {#getInputFile--}
```
String getInputFile()
```

获取输入文件的名称和路径。

**Returns:**
字符串对象

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

获取输入流。

**Returns:**
InputStream 对象

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

如果为 true，则保持安全性。

**Returns:**
布尔值

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

获取输出文件的名称和路径。

**Returns:**
字符串对象

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

获取输出流。

**Returns:**
OutputStream 对象

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

获取 souorce 文件中第一页的高度。

**Returns:**
float 值

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

获取页面编号的旋转角度。

**Returns:**
float 值

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

获取输入文件中第一页的宽度。

**Returns:**
float 值

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

获取当结果存储为 HttpResponse 时的保存选项。

**Returns:**
SaveOptions 对象

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

获取或设置输入文件中第一页的起始编号。

**Returns:**
int 值

### setAttachmentName {#setAttachmentName-java.lang.String-}
当操作结果作为附件存储到 HttpResponse 对象时，设置附件的名称。

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
设置当操作结果存储到 HttpResponse 对象时内容的存储方式。

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
设置 PDF 文件格式。

### setInputFile {#setInputFile-java.lang.String-}
设置输入文件的名称和路径。

### setInputStream {#setInputStream-java.io.InputStream-}
设置输入流。

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

设置保持安全性

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
void setPageNumberRotation(float value)
```

设置页面编号的旋转角度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
设置当结果存储为 HttpResponse 时的保存选项。

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

设置输入文件中第一页的起始编号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
