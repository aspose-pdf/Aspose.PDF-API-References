---
title: PdfProducer
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示从其他格式生成 PDF 的类。
type: docs
weight: 51
url: /zh/java/com.aspose.pdf.facades/pdfproducer/
---
**遗产：**
java.lang.Object
```
public abstract class PdfProducer
```

表示从其他格式生成 PDF 的类。

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 try
 {
     PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile);
     // Success produced pdf file.
 }
 catch (Exception e)
 {
     //  Do something...
 }
```
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getImportOptions(int format)](#getImportOptions-int-) | 获取指定导入格式的 ImportOptions。 |
| [getProducer(ImportOptions options)](#getProducer-com.aspose.pdf.ImportOptions-) | 获取指定导入选项的生产者。 |
| [getProducer(int format)](#getProducer-int-) | 获取指定导入格式的生产者。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [produce(InputStream inputStream, ImportOptions options, OutputStream outputStream)](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-) | 使用指定的导入选项生成 PDF 文件。 |
| [produce(InputStream inputStream, ImportOptions options, String outputFileName)](#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-) |  |
| [produce(InputStream inputStream, int format, OutputStream outputStream)](#produce-java.io.InputStream-int-java.io.OutputStream-) | 使用指定的导入格式生成 PDF 流。 |
| [produce(InputStream inputStream, int format, String outputFileName)](#produce-java.io.InputStream-int-java.lang.String-) | 使用指定的导入格式生成 PDF 文件。 |
| [produce(String inputFileName, ImportOptions options, OutputStream outputStream)](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-) |  |
| [produce(String inputFileName, ImportOptions options, String outputFileName)](#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-) | 使用指定的导入选项生成 PDF 文件。 |
| [produce(String inputFileName, int format, OutputStream outputStream)](#produce-java.lang.String-int-java.io.OutputStream-) |  |
| [produce(String inputFileName, int format, String outputFileName)](#produce-java.lang.String-int-java.lang.String-) | 使用指定的导入格式生成 PDF 文件。 |
| [produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream)](#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getImportOptions(int format) {#getImportOptions-int-}
```
public static ImportOptions getImportOptions(int format)
```


获取指定导入格式的 ImportOptions。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| format | int | 导入格式。 |

**退货：**
[ImportOptions](../../com.aspose.pdf/importoptions) 导入选项。
### getProducer(ImportOptions options) {#getProducer-com.aspose.pdf.ImportOptions-}
```
public static PdfProducer getProducer(ImportOptions options)
```


获取指定导入选项的生产者。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | 导入选项 |

**退货：**
[PdfProducer](../../com.aspose.pdf.facades/pdfproducer) PDF 制作人。
### getProducer(int format) {#getProducer-int-}
```
public static PdfProducer getProducer(int format)
```


获取指定导入格式的生产者。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| format | int | 导入选项 |

**退货：**
[PdfProducer](../../com.aspose.pdf.facades/pdfproducer) PDF 制作人。
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




### produce(InputStream inputStream, ImportOptions options, OutputStream outputStream) {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
```
public static void produce(InputStream inputStream, ImportOptions options, OutputStream outputStream)
```


使用指定的导入选项生成 PDF 文件。

--------------------

```
This sample shows how to produce Pdf stream from CGM stream.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 using (FileInputStream inputStream = File.OpenRead(inputFile))
 using (FileOutputStream outputStream = File.Create(outputFile))
 {
     PdfProducer.produce(inputStream, importOptions, outputStream);
 }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入流。 |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | 导入选项。 |
| outputStream | java.io.OutputStream | 输出 PDF 流。 |

### produce(InputStream inputStream, ImportOptions options, String outputFileName) {#produce-java.io.InputStream-com.aspose.pdf.ImportOptions-java.lang.String-}
```
public static void produce(InputStream inputStream, ImportOptions options, String outputFileName)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputFileName | java.lang.String |  |

### produce(InputStream inputStream, int format, OutputStream outputStream) {#produce-java.io.InputStream-int-java.io.OutputStream-}
```
public static void produce(InputStream inputStream, int format, OutputStream outputStream)
```


使用指定的导入格式生成 PDF 流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入流。 |
| format | int | 导入格式。 |
| outputStream | java.io.OutputStream | 输出 PDF 流。 |

### produce(InputStream inputStream, int format, String outputFileName) {#produce-java.io.InputStream-int-java.lang.String-}
```
public static void produce(InputStream inputStream, int format, String outputFileName)
```


使用指定的导入格式生成 PDF 文件。

--------------------

```
This sample shows how to produce Pdf file from CGM stream.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 using (FileInputStream inputStream = File.OpenRead(inputFile))
 using (FileOutputStream outputStream = File.Create(outputFile))
 {
     PdfProducer.produce(inputStream, ImportFormat.Cgm, outputStream);
 }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 输入流。 |
| format | int | 导入格式。 |
| outputFileName | java.lang.String | 输出PDF文件 |

### produce(String inputFileName, ImportOptions options, OutputStream outputStream) {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.io.OutputStream-}
```
public static void produce(String inputFileName, ImportOptions options, OutputStream outputStream)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | java.lang.String |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputStream | java.io.OutputStream |  |

### produce(String inputFileName, ImportOptions options, String outputFileName) {#produce-java.lang.String-com.aspose.pdf.ImportOptions-java.lang.String-}
```
public static void produce(String inputFileName, ImportOptions options, String outputFileName)
```


使用指定的导入选项生成 PDF 文件。

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 ImportOptions importOptions = new CgmImportOptions();
 PdfProducer.produce(inputStream, importOptions, outputStream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | java.lang.String | 输入文件名。 |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) | 导入选项。 |
| outputFileName | java.lang.String | 输出 PDF 流。 |

### produce(String inputFileName, int format, OutputStream outputStream) {#produce-java.lang.String-int-java.io.OutputStream-}
```
public static void produce(String inputFileName, int format, OutputStream outputStream)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | java.lang.String |  |
| format | int |  |
| outputStream | java.io.OutputStream |  |

### produce(String inputFileName, int format, String outputFileName) {#produce-java.lang.String-int-java.lang.String-}
```
public static void produce(String inputFileName, int format, String outputFileName)
```


使用指定的导入格式生成 PDF 文件。

--------------------

```
This sample shows how to produce Pdf file from CGM file.
 
 String inputFile = "myImage.cgm";
 String outputFile = "myPdf.pdf";
 PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFileName | java.lang.String | 输入文件名。 |
| format | int | 导入格式。 |
| outputFileName | java.lang.String | 输出PDF文件 |

### produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream) {#produceInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImportOptions-com.aspose.ms.System.IO.Stream-}
```
public static void produceInternal(System.IO.Stream inputStream, ImportOptions options, System.IO.Stream outputStream)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | com.aspose.ms.System.IO.Stream |  |
| options | [ImportOptions](../../com.aspose.pdf/importoptions) |  |
| outputStream | com.aspose.ms.System.IO.Stream |  |

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
