---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于在现有 PDF 文档页面上添加文本和图像的类。"
type: docs
weight: 500
url: /zh/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

表示用于在现有 PDF 文档页面上添加文本和图像的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | 构造函数。 |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | 构造函数。 |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | 构造函数。 |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | 构造函数。 |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | 构造函数。 |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | 构造函数。 |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | 构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | 未实现。 |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | 未实现。 |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | 未实现。 |
| [close](#close--) | 关闭 PdfFileMend 对象。 |
| [dispose](#dispose--) | 关闭 PdfFileMend 对象。此方法已过时，请改用 close()。 |
| [getDocument](#getDocument--) | 获取 {@code PdfFileMend} 正在处理的文档。 |
| [getInputFile](#getInputFile--) | 获取输入文件。 |
| [getInputStream](#getInputStream--) | 获取输入流。 |
| [getOutputFile](#getOutputFile--) | 获取输出文件。 |
| [getOutputStream](#getOutputStream--) | 获取输出流。 |
| [getTextPositioningMode](#getTextPositioningMode--) | 获取文本定位策略。{@code PositioningMode} 默认模式为 Legacy。 |
| [getWrapMode](#getWrapMode--) | 获取换行算法。 |
| [save](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定文件。 |
| [save](#save-java.lang.String-) | 将 PDF 文档保存到指定文件。 |
| [setInputFile](#setInputFile-java.lang.String-) | 已弃用。 |
| [setInputStream](#setInputStream-java.io.InputStream-) | 设置输入流。 |
| [setOutputFile](#setOutputFile-java.lang.String-) | 设置输出文件。 |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | 此方法已弃用。使用 Save(outputStream) 方法获取外观结果。 |
| [setTextPositioningMode](#setTextPositioningMode-int-) | 设置文本定位策略。{@code PositioningMode} 默认模式为 Legacy。 |
| [setWordWrap](#setWordWrap-boolean-) | 设置一个布尔值，指示 AddText 方法中的换行。如果值为 true，FormattedText 中的文本将换行。默认情况下，值为 false。 |
| [setWrapMode](#setWrapMode-int-) | 设置换行算法。 |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

构造函数。

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
构造函数。

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
构造函数。

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
构造函数。

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
构造函数。

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
构造函数。

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
构造函数。

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> 在指定坐标处向 PDF 文档的指定页面添加图像。 </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
未实现。

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
未实现。

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
未实现。

### close {#close--}
```
public void close()
```

关闭 PdfFileMend 对象。

### dispose {#dispose--}
```
public void dispose()
```

关闭 PdfFileMend 对象。此方法已过时，请改用 close()。

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

获取 {@code PdfFileMend} 正在处理的文档。

**Returns:**
IDocument 对象

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

获取输入文件。

**Returns:**
字符串值

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

获取输入流。

**Returns:**
输入流。

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

获取输出文件。

**Returns:**
字符串值

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

获取输出流。

**Returns:**
输出流。

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

获取文本定位策略。{@code PositioningMode} 默认模式为 Legacy。

**Returns:**
PositioningMode 元素 @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

获取换行算法。

**Returns:**
WordWrapMode 值 @see WordWrapMode

### save {#save-java.io.OutputStream-}
将 PDF 文档保存到指定文件。

### save {#save-java.lang.String-}
将 PDF 文档保存到指定文件。

### setInputFile {#setInputFile-java.lang.String-}
已弃用。

### setInputStream {#setInputStream-java.io.InputStream-}
设置输入流。

### setOutputFile {#setOutputFile-java.lang.String-}
设置输出文件。

### setOutputStream {#setOutputStream-java.io.OutputStream-}
此方法已弃用。使用 Save(outputStream) 方法获取外观结果。

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

设置文本定位策略。{@code PositioningMode} 默认模式为 Legacy。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | PositioningMode 元素 @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

设置一个布尔值，指示 AddText 方法中的换行。如果值为 true，FormattedText 中的文本将换行。默认情况下，值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

设置换行算法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | WordWrapMode 元素 @see WordWrapMode |
