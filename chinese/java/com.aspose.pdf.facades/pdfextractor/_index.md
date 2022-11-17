---
title: PdfExtractor
second_title: 用于 Java API 参考的 Aspose.PDF
description: 用于从 PDF 文档中提取图像和文本的类。
type: docs
weight: 38
url: /zh/java/com.aspose.pdf.facades/pdfextractor/
---
**遗产：**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade)
```
public final class PdfExtractor extends Facade
```

用于从 PDF 文档中提取图像和文本的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfExtractor()](#PdfExtractor--) | 初始化新的 PdfExtractor 对象。 |
| [PdfExtractor(IDocument document)](#PdfExtractor-com.aspose.pdf.IDocument-) | 在文档的基础上初始化新的 PdfExtractor 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | 初始化门面。 |
| [bindPdf(InputStream inputStream)](#bindPdf-java.io.InputStream-) | 从流中绑定 PDF 文档。 |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | 初始化门面。 |
| [bindPdf(String inputFile)](#bindPdf-java.lang.String-) | 绑定输入 PDF 文件。 |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | 初始化门面。 |
| [close()](#close--) | 处理与外观绑定的文档。 |
| [dispose()](#dispose--) | 处理门面。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractAttachment()](#extractAttachment--) | 从 Pdf 文档中提取附件。 |
| [extractAttachment(String attachmentFileName)](#extractAttachment-java.lang.String-) | 按附件名称将附件提取到 PDF 文件。 |
| [extractImage()](#extractImage--) | 从 PDF 文件中提取图像。 |
| [extractMarkedContentAsImages(Page page, String path)](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | 获取所有标记内容容器作为单独的图像。 |
| [extractText()](#extractText--) | 从 Pdf 文档中提取文本。 |
| [extractText(Charset encoding)](#extractText-java.nio.charset.Charset-) | 使用指定的编码从 Pdf 文档中提取文本。 |
| [extractTextInternal(TextEncodingInternal encoding)](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | 仅供内部使用 |
| [getAttachNames()](#getAttachNames--) | 返回 PDF 文件中的附件列表。 |
| [getAttachment()](#getAttachment--) | 将所有附件文件保存到流中。 |
| [getAttachment(String outputPath)](#getAttachment-java.lang.String-) | 将附件存储到文件中。 |
| [getAttachmentInfo()](#getAttachmentInfo--) | 获取附件列表。 |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | 获取正在处理的文档外观。 |
| [getEndPage()](#getEndPage--) | 获取将执行提取操作的页面范围内的结束页面。 |
| [getExtractImageMode()](#getExtractImageMode--) | 设置提取图像过程的模式。 |
| [getExtractTextMode()](#getExtractTextMode--) | 获取提取文本结果的模式。 |
| [getNextImage(OutputStream outputStream)](#getNextImage-java.io.OutputStream-) | 从 PDF 文件中检索下一张图像并将其存储到流中。 |
| [getNextImage(OutputStream outputStream, ImageType format)](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | 从 PDF 文件中检索下一个图像并将其存储到具有给定图像格式的流中。 |
| [getNextImage(String outputFile)](#getNextImage-java.lang.String-) | 从 PDF 文档中检索下一张图像。 |
| [getNextImage(String outputFile, ImageType format)](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | 从具有给定图像格式的 PDF 文档中检索下一个图像。 |
| [getNextPageText(OutputStream outputStream)](#getNextPageText-java.io.OutputStream-) | 将一页的文本保存到流中。 |
| [getNextPageText(String outputFile)](#getNextPageText-java.lang.String-) | 将一页的文本保存到文件。 |
| [getPassword()](#getPassword--) | 获取输入文件的密码。 |
| [getResolution()](#getResolution--) | 获取提取图像的分辨率。 |
| [getStartPage()](#getStartPage--) | 获取将执行提取操作的页面范围内的起始页。 |
| [getText(OutputStream outputStream)](#getText-java.io.OutputStream-) | 将文本保存到流中。另见：ExtractText  |
| [getText(OutputStream outputStream, boolean filterNotAscii)](#getText-java.io.OutputStream-boolean-) | 将文本保存到流中。另见：ExtractText  |
| [getText(String outputFile)](#getText-java.lang.String-) | 将文本保存到文件。另见：ExtractText  |
| [getTextSearchOptions()](#getTextSearchOptions--) | 获取文本搜索选项。 |
| [hasNextImage()](#hasNextImage--) | 检查 PDF 文档中是否可以访问更多图像。 |
| [hasNextPageText()](#hasNextPageText--) | 表示是否可以获取更多的文本。 |
| [hashCode()](#hashCode--) |  |
| [isBidi()](#isBidi--) | 当文本具有希伯来语或阿拉伯语符号时为真。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEndPage(int value)](#setEndPage-int-) | 在将执行提取操作的页面范围内设置结束页面。 |
| [setExtractImageMode(int value)](#setExtractImageMode-int-) | 设置提取图像过程的模式。 |
| [setExtractTextMode(int value)](#setExtractTextMode-int-) | 设置提取文本结果的模式。 |
| [setPassword(String value)](#setPassword-java.lang.String-) | 设置输入文件的密码。 |
| [setResolution(int value)](#setResolution-int-) | 设置提取图像的分辨率。 |
| [setStartPage(int value)](#setStartPage-int-) | 在将执行提取操作的页面范围内设置起始页。 |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | 设置文本搜索选项。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfExtractor() {#PdfExtractor--}
```
public PdfExtractor()
```


初始化新的 PdfExtractor 对象。

### PdfExtractor(IDocument document) {#PdfExtractor-com.aspose.pdf.IDocument-}
```
public PdfExtractor(IDocument document)
```


在文档的基础上初始化新的 PdfExtractor 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | pdf文档。 |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


初始化门面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | 文档对象。 |

### bindPdf(InputStream inputStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream inputStream)
```


从流中绑定 PDF 文档。

--------------------

```
PdfExtractor ext = new PdfExtractor();
 InputStream stream = new FileInputStream("sample.pdf");
 ext.bindPdf(stream);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputStream | java.io.InputStream | 包含 PDF 文档数据的流 |

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

### bindPdf(String inputFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String inputFile)
```


绑定输入 PDF 文件。

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindPdf("sample.pdf");
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputFile | java.lang.String | 要绑定的 PDF 字段 |

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


处理与外观绑定的文档。

### dispose() {#dispose--}
```
public void dispose()
```


处理门面。

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
### extractAttachment() {#extractAttachment--}
```
public void extractAttachment()
```


从 Pdf 文档中提取附件。

### extractAttachment(String attachmentFileName) {#extractAttachment-java.lang.String-}
```
public void extractAttachment(String attachmentFileName)
```


按附件名称将附件提取到 PDF 文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| attachmentFileName | java.lang.String | 要提取的附件名称 |

### extractImage() {#extractImage--}
```
public void extractImage()
```


从 PDF 文件中提取图像。

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.HasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

### extractMarkedContentAsImages(Page page, String path) {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
```
public void extractMarkedContentAsImages(Page page, String path)
```


获取所有标记内容容器作为单独的图像。

每个标记的内容都将保存为以 MCID 命名的 png 格式的图像\_.png 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 过程页面。 |
| path | java.lang.String | 图像将被保存的路径。 |

### extractText() {#extractText--}
```
public void extractText()
```


从 Pdf 文档中提取文本。

--------------------

```
First example demonstratres how to extract all the text from PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("D:\Text\text.pdf");
 	extractor.extractText();
 	extractor.getText("D:\Text\text.txt");
```

第二个例子演示了如何将每一页的文本提取到一个 txt 文件中。

```
PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText();
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

### extractText(Charset encoding) {#extractText-java.nio.charset.Charset-}
```
public void extractText(Charset encoding)
```


使用指定的编码从 Pdf 文档中提取文本。

--------------------

```
First example demonstrates how to extract all the text from PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("D:\\Text\\text.pdf");
 	extractor.extractText(Encoding.Unicode);
 	extractor.getText("D:\\Text\\text.txt");
```

第二个示例演示如何将每个页面的文本提取到一个 txt 文件中。

```
PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText(java.nio.charset.Charset.forName("UTF-8"));
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| encoding | java.nio.charset.Charset | 提取文本的编码。 |

### extractTextInternal(TextEncodingInternal encoding) {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
```
public void extractTextInternal(TextEncodingInternal encoding)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| encoding | [TextEncodingInternal](../../com.aspose.pdf/textencodinginternal) | 提取文本的编码。 |

### getAttachNames() {#getAttachNames--}
```
public List<String> getAttachNames()
```


返回 PDF 文件中的附件列表。注意：在使用此方法之前必须调用 ExtractAttachments。

--------------------

```
Example demonstrates how to extract attachment names form PDF file.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(TestSettings.GetInputFile("sample.pdf"));
 	extractor.ExtractAttachment();
 	List attachments = extractor.getAttachNames();
 	for (String name : ```
(Iterable)
```attachments)
 		System.out.println(name);
```

**退货：**
java.util.List<java.lang.String> - 附件列表
### getAttachment() {#getAttachment--}
```
public ByteArrayOutputStream[] getAttachment()
```


将所有附件文件保存到流中。

--------------------

```
PdfExtractor extractor = new PdfExtractor();     
 	extractor.bindPdf(path + "Attach.pdf");
 	extractor.extractAttachment();
 	IList names = extractor.getAttachNames();
 	ByteArrayOutputStream[] tempStreams =  extractor.getAttachment();
 	for (int i=0; i<tempStreams.Length; i++)
 	{
 		string name = (string)names[i];
 		OutputStream fs = new FileOutputStream(path + name);
 		fs.write(tempStreams[i].toByteArray()); 
 		fs.close();
 	}
```

**退货：**
java.io.ByteArrayOutputStream[- pdf文档中附件文件的流数组。
### getAttachment(String outputPath) {#getAttachment-java.lang.String-}
```
public void getAttachment(String outputPath)
```


将附件存储到文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputPath | java.lang.String | 将存储附件的目录路径。 Null 或空字符串表示附件将放置在应用程序目录中。 |

### getAttachmentInfo() {#getAttachmentInfo--}
```
public List<FileSpecification> getAttachmentInfo()
```


获取附件列表。

**退货：**
java.util.List<com.aspose.pdf.FileSpecification> - 返回一个列表<FileSpecificatio>.
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


获取正在处理的文档外观。

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 元素
### getEndPage() {#getEndPage--}
```
public int getEndPage()
```


获取将执行提取操作的页面范围内的结束页面。

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(3);
 ext.extractText();
```

**退货：**
int - 结束页。
### getExtractImageMode() {#getExtractImageMode--}
```
public int getExtractImageMode()
```


设置提取图像过程的模式。

--------------------

默认值为 ExtractImageMode.DefinedInResources，它提取资源中定义的所有图像。要提取实际显示的图像，应使用 ExtractImageMode.ActuallyUsed 模式。

**退货：**
int - ExtractImageMode 值
### getExtractTextMode() {#getExtractTextMode--}
```
public int getExtractTextMode()
```


获取提取文本结果的模式。

--------------------

```
The example demonstratres the ```
ExtractTextMode
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(@"D:\Text\text.pdf");
  extractor.setExtractTextMode(1);
 	extractor.extractText();
 	extractor.getText(@"D:\Text\text.txt");
```

值：0 是纯文本模式，1 是原始排序模式。默认为 0。

**退货：**
int - 提取文本的结果。
### getNextImage(OutputStream outputStream) {#getNextImage-java.io.OutputStream-}
```
public boolean getNextImage(OutputStream outputStream)
```


从 PDF 文件中检索下一张图像并将其存储到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 将保存图像数据的流 |

**退货：**
布尔值 - 如果成功提取图像，则为 True。
### getNextImage(OutputStream outputStream, ImageType format) {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public boolean getNextImage(OutputStream outputStream, ImageType format)
```


从 PDF 文件中检索下一个图像并将其存储到具有给定图像格式的流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 将保存图像数据的流 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图片的格式。 |

**退货：**
布尔值 - 如果成功提取图像，则为 True。
### getNextImage(String outputFile) {#getNextImage-java.lang.String-}
```
public boolean getNextImage(String outputFile)
```


从 PDF 文档中检索下一张图像。注意：ExtractImage 必须在使用此方法之前调用。

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.hasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 将存储图像的文件 |

**退货：**
boolean - True 是图像被成功提取
### getNextImage(String outputFile, ImageType format) {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
```
public boolean getNextImage(String outputFile, ImageType format)
```


从具有给定图像格式的 PDF 文档中检索下一个图像。注意：ExtractImage 必须在使用此方法之前调用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 将存储图像的文件 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 图像类型元素 |

**退货：**
boolean - True 是图像被成功提取
### getNextPageText(OutputStream outputStream) {#getNextPageText-java.io.OutputStream-}
```
public void getNextPageText(OutputStream outputStream)
```


将一页的文本保存到流中。

--------------------

```
The example demonstratres the ```
GetNextPageText
``` method usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create);
      extractor.getNextPageText(fs);
      fs.close();
      pageCount++;
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存文本的流。 |

### getNextPageText(String outputFile) {#getNextPageText-java.lang.String-}
```
public void getNextPageText(String outputFile)
```


将一页的文本保存到文件。

--------------------

```
The example demonstratres the GetNextPageText method usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + @"Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存文本的文件路径和名称。 |

### getPassword() {#getPassword--}
```
public String getPassword()
```


获取输入文件的密码。

**退货：**
java.lang.String - 字符串值
### getResolution() {#getResolution--}
```
public int getResolution()
```


获取提取图像的分辨率。默认值为 150。分辨率值越大的图像越清晰。然而，增加分辨率值会导致提取图像所需的时间和内存增加。通常为了获得清晰的图像，将分辨率设置为 150 或 300 就足够了。

**退货：**
int - 整数值
### getStartPage() {#getStartPage--}
```
public int getStartPage()
```


获取将执行提取操作的页面范围内的起始页。

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(5);
 ext.extractText();
```

**退货：**
int - 页面范围内的起始页。
### getText(OutputStream outputStream) {#getText-java.io.OutputStream-}
```
public void getText(OutputStream outputStream)
```


将文本保存到流中。另见：ExtractText 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存文本的流。 |

### getText(OutputStream outputStream, boolean filterNotAscii) {#getText-java.io.OutputStream-boolean-}
```
public void getText(OutputStream outputStream, boolean filterNotAscii)
```


将文本保存到流中。另见：ExtractText 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputStream | java.io.OutputStream | 保存文本的流。 |
| filterNotAscii | boolean | 如果此参数为真，则将删除所有非 ASCII 符号 |

### getText(String outputFile) {#getText-java.lang.String-}
```
public void getText(String outputFile)
```


将文本保存到文件。另见：ExtractText 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | java.lang.String | 保存文本的文件路径和名称。 |

### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


获取文本搜索选项。

**退货：**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) 文本搜索选项。
### hasNextImage() {#hasNextImage--}
```
public boolean hasNextImage()
```


检查 PDF 文档中是否可以访问更多图像。注意：ExtractImage 必须在使用此方法之前调用。

--------------------

```
PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf("sample.pdf");
 	extractor.extractImage();
 	int i = 1;
 	while (extractor.hasNextImage())
 	{
 	    extractor.getNextImage("image-" + i +".pdf");
 	}
```

**退货：**
布尔值 - 如果可以访问更多图像则为真
### hasNextPageText() {#hasNextPageText--}
```
public boolean hasNextPageText()
```


表示是否可以获取更多的文本。

--------------------

```
The example demonstratres the ```
HasNextPageText
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
  extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf");
  extractor.extractText(Encoding.Unicode);
  String prefix = TestPath + "Aspose.Pdf.Kit";
  String suffix = ".txt";
  int pageCount = 1;
  while (extractor.hasNextPageText())
  {
      extractor.getNextPageText(prefix + pageCount + suffix);
      pageCount++;
  }
```

**退货：**
boolean - 是否可以获取更多文本，true 是可以，否则是 false。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isBidi() {#isBidi--}
```
public boolean isBidi()
```


当文本具有希伯来语或阿拉伯语符号时为真。必须特别考虑这种情况，因为字符串函数会改变它们的行为并从右到左开始处理文本（数字和其他非文本字符除外）。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setEndPage(int value) {#setEndPage-int-}
```
public void setEndPage(int value)
```


在将执行提取操作的页面范围内设置结束页面。

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(3);
 ext.extractText();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 结束页。 |

### setExtractImageMode(int value) {#setExtractImageMode-int-}
```
public void setExtractImageMode(int value)
```


设置提取图像过程的模式。

--------------------

默认值为 ExtractImageMode.DefinedInResources，它提取资源中定义的所有图像。要提取实际显示的图像，应使用 ExtractImageMode.ActuallyUsed 模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ExtractImageMode 值 |

### setExtractTextMode(int value) {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```


设置提取文本结果的模式。

--------------------

```
The example demonstratres the ```
ExtractTextMode
``` property usage in text extraction scenario.
 
 
  PdfExtractor extractor = new PdfExtractor();
 	extractor.bindPdf(@"D:\Text\text.pdf");
  extractor.setExtractTextMode(1);
 	extractor.extractText();
 	extractor.getText(@"D:\Text\text.txt");
```

值：0 是纯文本模式，1 是原始排序模式。默认为 0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 提取文本的结果。 |

### setPassword(String value) {#setPassword-java.lang.String-}
```
public void setPassword(String value)
```


设置输入文件的密码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setResolution(int value) {#setResolution-int-}
```
public void setResolution(int value)
```


设置提取图像的分辨率。默认值为 150。分辨率值越大的图像越清晰。然而，增加分辨率值会导致提取图像所需的时间和内存增加。通常为了获得清晰的图像，将分辨率设置为 150 或 300 就足够了。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setStartPage(int value) {#setStartPage-int-}
```
public void setStartPage(int value)
```


在将执行提取操作的页面范围内设置起始页。

--------------------

```
PdfExtractor ext = new PdfExtractor();
 ext.bindBdf("sample.pdf");
 ext.setStartPage(2);
 ext.setEndPage(5);
 ext.extractText();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 页范围内的起始页。 |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


设置文本搜索选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | 文本搜索选项。 |

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
