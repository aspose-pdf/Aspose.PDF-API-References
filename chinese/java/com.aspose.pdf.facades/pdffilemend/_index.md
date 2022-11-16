---
title: PdfFileMend
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示用于在现有 PDF 文档的页面上添加文本和图像的类。
type: docs
weight: 42
url: /zh/java/com.aspose.pdf.facades/pdffilemend/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfFileMend extends SaveableFacade
```

表示用于在现有 PDF 文档的页面上添加文本和图像的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfFileMend()](#PdfFileMend--) | 构造函数。 |
| [PdfFileMend(String inputFileName, String outputFileName)](#PdfFileMend-java.lang.String-java.lang.String-) | 构造函数。 |
| [PdfFileMend(InputStream inputStream, OutputStream outputStream)](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | 构造函数。 |
| [PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream)](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | 构造函数。 |
| [PdfFileMend(IDocument document)](#PdfFileMend-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfFileMend 对象。 |
| [PdfFileMend(IDocument document, String outputFileName)](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | 在文档的基础上初始化新的 PdfFileMend 对象。 |
| [PdfFileMend(IDocument document, System.IO.Stream outputStream)](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | 在文档的基础上初始化新的 PdfFileMend 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.io.InputStream-int-float-float-float-float-) | 在指定坐标处将图像添加到 PDF 文档的指定页面。 |
| [addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | 在指定坐标处将图像添加到 PDF 文档的指定页面。 |
| [addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.io.InputStream-int---float-float-float-float-) | 将图像添加到指定坐标处的 PDF 文档的指定页面。 |
| [addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.io.InputStream-int---float-float-float-float-com.aspose.pdf.CompositingParameters-) | 将图像添加到指定坐标处的 PDF 文档的指定页面。 |
| [addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.lang.String-int-float-float-float-float-) | 在指定坐标处将图像添加到 PDF 文档的指定页面。 |
| [addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | 在指定坐标处将图像添加到 PDF 文档的指定页面。 |
| [addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addImage-java.lang.String-int---float-float-float-float-) | 将图像添加到指定坐标处的 PDF 文档的指定页面。 |
| [addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)](#addImage-java.lang.String-int---float-float-float-float-com.aspose.pdf.CompositingParameters-) | 将图像添加到指定坐标处的 PDF 文档的指定页面。 |
| [addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY)](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | 未实现。 |
| [addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | 未实现。 |
| [addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer---float-float-float-float-) | 未实现。 |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | 初始化门面。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | 初始化门面。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 关闭 PdfFileMend 对象。 |
| [dispose()](#dispose--) | 关闭 PdfFileMend 对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取 PdfFileMend 正在处理的文档。 |
| [getInputFile()](#getInputFile--) | 获取输入文件。 |
| [getInputStream()](#getInputStream--) | 获取输入流。 |
| [getOutputFile()](#getOutputFile--) | 获取输出文件。 |
| [getOutputStream()](#getOutputStream--) | 获取输出流。 |
| [getTextPositioningMode()](#getTextPositioningMode--) | 获取文本定位策略。 |
| [getWrapMode()](#getWrapMode--) | 获取自动换行算法。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | 将 PDF 文档保存到指定文件。 |
| [save(String destFile)](#save-java.lang.String-) | 将 PDF 文档保存到指定文件。 |
| [setInputFile(String value)](#setInputFile-java.lang.String-) |  |
| [setInputStream(InputStream value)](#setInputStream-java.io.InputStream-) | 设置输入流。 |
| [setOutputFile(String value)](#setOutputFile-java.lang.String-) | 设置输出文件。 |
| [setOutputStream(OutputStream value)](#setOutputStream-java.io.OutputStream-) | 此方法已弃用。 |
| [setTextPositioningMode(int value)](#setTextPositioningMode-int-) | 设置文本定位策略。 |
| [setWordWrap(boolean value)](#setWordWrap-boolean-) | 设置一个 bool 值，该值指示 AddText 方法中的自动换行。 |
| [setWrapMode(int value)](#setWrapMode-int-) | 设置自动换行算法。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfFileMend() {#PdfFileMend--}
```
public PdfFileMend()
```


构造函数。

### PdfFileMend(String inputFileName, String outputFileName) {#PdfFileMend-java.lang.String-java.lang.String-}
```
public PdfFileMend(String inputFileName, String outputFileName)
```


构造函数。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | java.lang.String | 输入 PDF 文件名。 |
| outputFileName | java.lang.String | 输出 PDF 文件名。 |

### PdfFileMend(InputStream inputStream, OutputStream outputStream) {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
```
public PdfFileMend(InputStream inputStream, OutputStream outputStream)
```


构造函数。 Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入 PDF 流。 |
| outputStream | java.io.OutputStream | 输出 PDF 流。 |

### PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream) {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public PdfFileMend(System.IO.Stream inputStream, System.IO.Stream outputStream)
```


构造函数。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | com.aspose.ms.System.IO.Stream | 输入 PDF 流。 |
| outputStream | com.aspose.ms.System.IO.Stream | 输出 PDF 流。 |

### PdfFileMend(IDocument document) {#PdfFileMend-com.aspose.pdf.IDocument-}
```
public PdfFileMend(IDocument document)
```


在文档的基础上初始化新的 PdfFileMend 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### PdfFileMend(IDocument document, String outputFileName) {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
```
public PdfFileMend(IDocument document, String outputFileName)
```


在文档的基础上初始化新的 PdfFileMend 对象。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |
| outputFileName | java.lang.String | 输出 PDF 文件名。 |

### PdfFileMend(IDocument document, System.IO.Stream outputStream) {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public PdfFileMend(IDocument document, System.IO.Stream outputStream)
```


在文档的基础上初始化新的 PdfFileMend 对象。

Obsolete("使用没有目的地的构造函数。")

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |
| outputStream | com.aspose.ms.System.IO.Stream | 输出 PDF 流。 |

### addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.io.InputStream-int-float-float-float-float-}
```
public boolean addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


在指定坐标处将图像添加到 PDF 文档的指定页面。

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg"))
 mendor.addImage(stream, 1, 10, 10, 100, 100);
 mendor.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 输入图像流。 |
| pageNum | int | 将接收图像的页数。 |
| lowerLeftX | float | 图像矩形的左下角 x。 |
| lowerLeftY | float | 图像矩形的左下角y。 |
| upperRightX | float | 图像矩形的右上角 x。 |
| upperRightY | float | 图像矩形的右上角y。 |

**退货：**
boolean - 如果成功则为真否则为假。
### addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(InputStream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


在指定坐标处将图像添加到 PDF 文档的指定页面。

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg"))
 mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
 mendor.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 输入图像流。 |
| pageNum | int | 将接收图像的页数。 |
| lowerLeftX | float | 图像矩形的左下角 x。 |
| lowerLeftY | float | 图像矩形的左下角y。 |
| upperRightX | float | 图像矩形的右上角 x。 |
| upperRightY | float | 图像矩形的右上角y。 |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | 图像的图形合成参数。 |

**退货：**
boolean - 如果成功则为真否则为假。
### addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.io.InputStream-int---float-float-float-float-}
```
public boolean addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


将图像添加到指定坐标处的 PDF 文档的指定页面。

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg")
     mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
 mendor.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 输入图像流。 |
| pageNums | int[] | 将接收图像的页数。 |
| lowerLeftX | float | 图像矩形的左下角 x。 |
| lowerLeftY | float | 图像矩形的左下角y。 |
| upperRightX | float | 图像矩形的右上角 x。 |
| upperRightY | float | 图像矩形的右上角y。 |

**退货：**
boolean - 如果成功则为真否则为假。
### addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.io.InputStream-int---float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(InputStream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


将图像添加到指定坐标处的 PDF 文档的指定页面。

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 InputStream stream = new FileInputStream("picture.jpg")
     mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
 mendor.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageStream | java.io.InputStream | 输入图像流。 |
| pageNums | int[] | 将接收图像的页数。 |
| lowerLeftX | float | 图像矩形的左下角 x。 |
| lowerLeftY | float | 图像矩形的左下角y。 |
| upperRightX | float | 图像矩形的右上角 x。 |
| upperRightY | float | 图像矩形的右上角y。 |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | 图像的图形合成参数。 |

**退货：**
boolean - 如果成功则为真否则为假。
### addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.lang.String-int-float-float-float-float-}
```
public boolean addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


在指定坐标处将图像添加到 PDF 文档的指定页面。

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100);
 mendor.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | java.lang.String | 输入图像文件的路径。 |
| pageNum | int | 将接收图像的页数。 |
| lowerLeftX | float | 图像矩形的左下角 x。 |
| lowerLeftY | float | 图像矩形的左下角y。 |
| upperRightX | float | 图像矩形的右上角 x。 |
| upperRightY | float | 图像矩形的右上角y。 |

**退货：**
boolean - 如果成功则为真否则为假。
### addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(String imageName, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


在指定坐标处将图像添加到 PDF 文档的指定页面。

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
 mendor.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | java.lang.String | 输入图像文件的路径。 |
| pageNum | int | 将接收图像的页数。 |
| lowerLeftX | float | 图像矩形的左下角 x。 |
| lowerLeftY | float | 图像矩形的左下角y。 |
| upperRightX | float | 图像矩形的右上角 x。 |
| upperRightY | float | 图像矩形的右上角y。 |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | 图像的图形合成参数。 |

**退货：**
boolean - 如果成功则为真否则为假。
### addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addImage-java.lang.String-int---float-float-float-float-}
```
public boolean addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


将图像添加到指定坐标处的 PDF 文档的指定页面。

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100);
 mendor.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | java.lang.String | 输入图像文件的路径。 |
| pageNums | int[] | 将接收图像的页数。 |
| lowerLeftX | float | 图像矩形的左下角 x。 |
| lowerLeftY | float | 图像矩形的左下角y。 |
| upperRightX | float | 图像矩形的右上角 x。 |
| upperRightY | float | 图像矩形的右上角y。 |

**退货：**
boolean - 如果成功则为真否则为假。
### addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters) {#addImage-java.lang.String-int---float-float-float-float-com.aspose.pdf.CompositingParameters-}
```
public boolean addImage(String imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```


将图像添加到指定坐标处的 PDF 文档的指定页面。

--------------------

```
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
 mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
 mendor.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageName | java.lang.String | 输入图像文件的路径。 |
| pageNums | int[] | 将接收图像的页数。 |
| lowerLeftX | float | 图像矩形的左下角 x。 |
| lowerLeftY | float | 图像矩形的左下角y。 |
| upperRightX | float | 图像矩形的右上角 x。 |
| upperRightY | float | 图像矩形的右上角y。 |
| compositingParameters | [CompositingParameters](../../com.aspose.pdf/compositingparameters) | 图像的图形合成参数。 |

**退货：**
boolean - 如果成功则为真否则为假。
### addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY) {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
```
public boolean addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY)
```


未实现。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 格式化文本对象。 |
| pageNum | int | 页码。 |
| lowerLeftX | float | 左下角的 X 坐标。 |
| lowerLeftY | float | 左下角的 Y 坐标。 |

**退货：**
布尔值 - 如果文本已成功添加，则为 True。
### addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
```
public boolean addText(FormattedText text, int pageNum, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


未实现。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 格式化文本对象。 |
| pageNum | int | 页码。 |
| lowerLeftX | float | 左下角的 X 坐标。 |
| lowerLeftY | float | 左下角的 Y 坐标。 |
| upperRightX | float | 右上角 X 坐标。 |
| upperRightY | float | 右上角的 Y 坐标。 |

**退货：**
布尔值 - 如果文本已成功添加，则为 True。
### addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY) {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer---float-float-float-float-}
```
public boolean addText(FormattedText text, Integer[] pageNums, float lowerLeftX, float lowerLeftY, float upperRightX, float upperRightY)
```


未实现。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 格式化文本对象。 |
| pageNums | java.lang.Integer[] | 页码数组。 |
| lowerLeftX | float | 左下角的 X 坐标。 |
| lowerLeftY | float | 左下角的 Y 坐标。 |
| upperRightX | float | 右上角 X 坐标。 |
| upperRightY | float | 右上角的 Y 坐标。 |

**退货：**
布尔值 - 如果文本已成功添加，则为 True。
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


关闭 PdfFileMend 对象。

### dispose() {#dispose--}
```
public void dispose()
```


关闭 PdfFileMend 对象。此方法已过时，请改用 close() 。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


获取 PdfFileMend 正在处理的文档。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 对象
### getInputFile() {#getInputFile--}
```
public String getInputFile()
```


获取输入文件。

**退货：**
java.lang.String - 字符串值
### getInputStream() {#getInputStream--}
```
public InputStream getInputStream()
```


获取输入流。

**退货：**
java.io.InputStream - 输入流。
### getOutputFile() {#getOutputFile--}
```
public String getOutputFile()
```


获取输出文件。

**退货：**
java.lang.String - 字符串值
### getOutputStream() {#getOutputStream--}
```
public OutputStream getOutputStream()
```


获取输出流。

**退货：**
java.io.OutputStream - 输出流。
### getTextPositioningMode() {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```


获取文本定位策略。 PositioningMode 默认模式是 Legacy。

**退货：**
int - PositioningMode 元素
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


获取自动换行算法。

**退货：**
int - WordWrapMode 值
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


将 PDF 文档保存到指定文件。

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

### setInputFile(String value) {#setInputFile-java.lang.String-}
```
public void setInputFile(String value)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setInputStream(InputStream value) {#setInputStream-java.io.InputStream-}
```
public void setInputStream(InputStream value)
```


设置输入流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流。 |

### setOutputFile(String value) {#setOutputFile-java.lang.String-}
```
public void setOutputFile(String value)
```


设置输出文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setOutputStream(OutputStream value) {#setOutputStream-java.io.OutputStream-}
```
public void setOutputStream(OutputStream value)
```


此方法已弃用。使用 Save(outputStream) 方法获取外观结果。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.OutputStream | 输出流。 |

### setTextPositioningMode(int value) {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```


设置文本定位策略。 PositioningMode 默认模式是 Legacy。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PositioningMode 元素 |

### setWordWrap(boolean value) {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```


设置一个 bool 值，该值指示 AddText 方法中的自动换行。如果该值为 true，则 FormattedText 中的文本将自动换行。默认情况下，值为 false。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


设置自动换行算法。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | WordWrapMode 元素 |

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
