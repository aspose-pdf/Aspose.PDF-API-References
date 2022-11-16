---
title: TextAbsorber
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示文本的吸收器对象。
type: docs
weight: 360
url: /zh/java/com.aspose.pdf/textabsorber/
---
**遗产：**
java.lang.Object
```
public class TextAbsorber
```

表示文本的吸收器对象。执行文本提取并通过 TextAbsorber.Text 对象提供对结果的访问。

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
 //打开文件
 Document doc = new Document(inFile);
 //创建 TextAbsorber 对象以提取文本
 TextAbsorber absorber = new TextAbsorber();
 //接受第一页的吸收器
 doc.getPages().get(1).accept(absorber);
 //获取提取的文本
 String extractedText = absorber.getText();
```

--------------------

TextAbsorber 对象用于从 Pdf 文档或文档页面中提取文本。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextAbsorber()](#TextAbsorber--) | 初始化 TextAbsorber 的新实例。 |
| [TextAbsorber(TextExtractionOptions extractionOptions)](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | 使用提取选项初始化 TextAbsorber 的新实例。 |
| [TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | 使用提取和文本搜索选项初始化 TextAbsorber 的新实例。 |
| [TextAbsorber(TextSearchOptions textSearchOptions)](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | 使用文本搜索选项初始化 TextAbsorber 的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrors()](#getErrors--) | TextExtractionError 对象列表。 |
| [getExtractionOptions()](#getExtractionOptions--) | 获取文本提取选项。 |
| [getText()](#getText--) | 获取 TextAbsorber 在 PDF 文档或页面上提取的提取文本。 |
| [getTextSearchOptions()](#getTextSearchOptions--) | 获取文本搜索选项。 |
| [hasErrors()](#hasErrors--) | 值指示在文本提取期间是否发现错误。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExtractionOptions(TextExtractionOptions value)](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | 设置文本提取选项。 |
| [setTextSearchOptions(TextSearchOptions value)](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | 设置文本搜索选项。 |
| [toString()](#toString--) |  |
| [visit(IDocument pdf)](#visit-com.aspose.pdf.IDocument-) | 提取指定文档中的文本 |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | 提取指定页面上的文本 |
| [visit(XForm form)](#visit-com.aspose.pdf.XForm-) | 在指定的 XForm 上提取文本。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextAbsorber() {#TextAbsorber--}
```
public TextAbsorber()
```


初始化 TextAbsorber 的新实例。

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 //打开文件
 Document doc = new Document(inFile);
 //创建 TextAbsorber 对象以提取文本
 TextAbsorber absorber = new TextAbsorber();
 //接受所有文档页面的吸收器
 doc.getPages().accept(absorber);
 //获取提取的文本
 String extractedText = absorber.getText();
```

--------------------

执行文本提取并通过 TextAbsorber.Text 对象提供对提取文本的访问。

### TextAbsorber(TextExtractionOptions extractionOptions) {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
```
public TextAbsorber(TextExtractionOptions extractionOptions)
```


使用提取选项初始化 TextAbsorber 的新实例。

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 //打开文件
 Document doc = new Document(inFile);
 //创建 TextAbsorber 对象以提取带格式的文本
 TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 //接受所有文档页面的吸收器
 doc.getPages().accept(absorber);
 //获取提取的文本
 String extractedText = absorber.getText();
```

--------------------

执行文本提取并通过 TextAbsorber.Text 对象提供对提取文本的访问。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | 文本提取选项

 ----------------------|

### TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions) {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
```
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```


使用提取和文本搜索选项初始化 TextAbsorber 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| extractionOptions | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | 文本提取选项 |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | 文本搜索选项

--------------------

执行文本提取并通过 TextAbsorber.Text 对象提供对提取文本的访问。|

### TextAbsorber(TextSearchOptions textSearchOptions) {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
```
public TextAbsorber(TextSearchOptions textSearchOptions)
```


使用文本搜索选项初始化 TextAbsorber 的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textSearchOptions | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | 文本搜索选项

--------------------

执行文本提取并通过 TextAbsorber.Text 对象提供对提取文本的访问。|

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
### getErrors() {#getErrors--}
```
public List<TextExtractionError> getErrors()
```


TextExtractionError 对象列表。它包含有关在文本提取期间发现的错误的信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；它可能会降低性能。

**退货：**
java.util.List<com.aspose.pdf.TextExtractionError> - TextExtractionError 对象列表
### getExtractionOptions() {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```


获取文本提取选项。

--------------------

```
The example demonstrates how to set Pure text formatting mode and perform text extraction.
 
 //打开文件
 Document doc = new Document(inFile);
 //创建 TextAbsorber 对象以提取带格式的文本
 TextAbsorber absorber = new TextAbsorber();
 //设置纯文本格式化模式
 absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 //接受所有文档页面的吸收器
 doc.getPages().accept(absorber);
 //获取提取的文本
 String extractedText = absorber.getText();
```

--------------------

允许在提取期间定义文本格式化模式 TextExtractionOptions。默认模式是 TextExtractionOptions.TextFormattingMode.Pure 

**退货：**
[TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) - TextExtractionOptions 值
### getText() {#getText--}
```
public String getText()
```


获取 TextAbsorber 在 PDF 文档或页面上提取的提取文本。

**退货：**
java.lang.String - 字符串值

--------------------

```
The example demonstrates how to extract text from all pages of the PDF document.
 
 //打开文件
 Document doc = new Document(inFile);
 //创建 TextAbsorber 对象以提取文本
 TextAbsorber absorber = new TextAbsorber();
 //接受所有文档页面的吸收器
 doc.getPages().accept(absorber);
 //获取提取的文本
 String extractedText = absorber.getText();
```
### getTextSearchOptions() {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```


获取文本搜索选项。

允许定义分隔提取文本的矩形。默认情况下，矩形是空的。这意味着页面边界仅定义文本提取区域。

**退货：**
[TextSearchOptions](../../com.aspose.pdf/textsearchoptions) - TextSearchOptions 值
### hasErrors() {#hasErrors--}
```
public boolean hasErrors()
```


值指示在文本提取期间是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；它可能会降低性能。

**退货：**
boolean - 布尔值
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




### setExtractionOptions(TextExtractionOptions value) {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
```
public void setExtractionOptions(TextExtractionOptions value)
```


设置文本提取选项。

--------------------

```
The example demonstrates how to set Pure text formatting mode and perform text extraction.
 
 //打开文件
 Document doc = new Document(inFile);
 //创建 TextAbsorber 对象以提取带格式的文本
 TextAbsorber absorber = new TextAbsorber();
 //设置纯文本格式化模式
 absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));
 //接受所有文档页面的吸收器
 doc.getPages().accept(absorber);
 //获取提取的文本
 String extractedText = absorber.getText();
```

--------------------

允许在提取期间定义文本格式化模式 TextExtractionOptions。默认模式是 TextExtractionOptions.TextFormattingMode.Pure 

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextExtractionOptions](../../com.aspose.pdf/textextractionoptions) | TextExtractionOptions 值 |

### setTextSearchOptions(TextSearchOptions value) {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
```
public void setTextSearchOptions(TextSearchOptions value)
```


设置文本搜索选项。

允许定义分隔提取文本的矩形。默认情况下，矩形是空的。这意味着页面边界仅定义文本提取区域。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextSearchOptions](../../com.aspose.pdf/textsearchoptions) | TextSearchOptions 值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### visit(IDocument pdf) {#visit-com.aspose.pdf.IDocument-}
```
public void visit(IDocument pdf)
```


提取指定文档中的文本

--------------------

```
The example demonstrates how to extract text on PDF document.
 
 //打开文件
 Document doc = new Document(inFile);
 //创建 TextAbsorber 对象以提取文本
 TextAbsorber absorber = new TextAbsorber();
 //接受所有文档页面的吸收器
 absorber.visit(doc);
 //获取提取的文本
 String extractedText = absorber.getText();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdf | [IDocument](../../com.aspose.pdf/idocument) | Pdf 文档对象。 |

### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public void visit(Page page)
```


提取指定页面上的文本

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
 //打开文件
 Document doc = new Document(inFile);
 //创建 TextAbsorber 对象以提取文本
 TextAbsorber absorber = new TextAbsorber();
 //接受所有文档页面的吸收器
 absorber.visit(doc.getPages(1));
 //获取提取的文本
 String extractedText = absorber.getText();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Pdf 文档页面对象。 |

### visit(XForm form) {#visit-com.aspose.pdf.XForm-}
```
public void visit(XForm form)
```


在指定的 XForm 上提取文本。

--------------------

```
The example demonstrates how to extract text on the first PDF document page.
 
  //打开文件
  Document doc = new Document(inFile);
  
  //创建 TextAbsorber 对象以提取文本
  TextAbsorber absorber = new TextAbsorber();
   
  //接受所有文档页面的吸收器
  absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1"));
     
  //获取提取的文本
  String extractedText = absorber.getText();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | PDF 表单对象。 |

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
