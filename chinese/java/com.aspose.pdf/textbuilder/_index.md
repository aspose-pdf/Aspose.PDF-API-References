---
title: TextBuilder
second_title: 用于 Java API 参考的 Aspose.PDF
description: 将文本对象附加到 Pdf 页面。
type: docs
weight: 364
url: /zh/java/com.aspose.pdf/textbuilder/
---
**遗产：**
java.lang.Object
```
public final class TextBuilder
```

将文本对象附加到 Pdf 页面。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextBuilder(Page page)](#TextBuilder-com.aspose.pdf.Page-) | 为 Pdf 页面初始化 TextBuilder 类的新实例。 |
| [TextBuilder(Page page, BaseOperatorCollection operatorCollection)](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | 为 Pdf 页面初始化 TextBuilder 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [appendParagraph(TextParagraph textParagraph)](#appendParagraph-com.aspose.pdf.TextParagraph-) | 将文本段落附加到 Pdf 页面。 |
| [appendParagraph(TextParagraph textParagraph, int rotation)](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | 附加段落旋转 |
| [appendText(TextFragment textFragment)](#appendText-com.aspose.pdf.TextFragment-) | 将文本片段附加到 Pdf 页面 |
| [appendText(List<TextFragment> textFragments)](#appendText-java.util.List-com.aspose.pdf.TextFragment--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSegmenter()](#getSegmenter--) | 获取 TextSegmenter 对象 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextBuilder(Page page) {#TextBuilder-com.aspose.pdf.Page-}
```
public TextBuilder(Page page)
```


为 Pdf 页面初始化 TextBuilder 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象。

--------------------

TextBuilder 允许将文本对象附加到 Pdf 页面。|

### TextBuilder(Page page, BaseOperatorCollection operatorCollection) {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
```
public TextBuilder(Page page, BaseOperatorCollection operatorCollection)
```


为 Pdf 页面初始化 TextBuilder 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象。 |
| operatorCollection | [BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection) | 运算符集合。 |

### appendParagraph(TextParagraph textParagraph) {#appendParagraph-com.aspose.pdf.TextParagraph-}
```
public void appendParagraph(TextParagraph textParagraph)
```


将文本段落附加到 Pdf 页面。

--------------------

```
The example demonstrates how to create text paragraph object and append it to the Pdf page.
 
 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 // create text paragraph
 TextParagraph paragraph = new TextParagraph();
            
 // set the paragraph rectangle
 paragraph.setRectangle ( new Rectangle(100, 600, 200, 700));
 // set word wrapping options
 paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords);
 // append string lines
 paragraph.appendLine("the quick brown fox jumps over the lazy dog");
 paragraph.appendLine("line2");
 paragraph.appendLine("line3");
 // append the paragraph to the Pdf page with the TextBuilder
 TextBuilder textBuilder = new TextBuilder(page);
 textBuilder.appendParagraph(paragraph);
 // save Pdf document
 doc.save(outFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textParagraph | [TextParagraph](../../com.aspose.pdf/textparagraph) | 文本段落对象。 |

### appendParagraph(TextParagraph textParagraph, int rotation) {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
```
public void appendParagraph(TextParagraph textParagraph, int rotation)
```


附加段落旋转

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textParagraph | [TextParagraph](../../com.aspose.pdf/textparagraph) | TextParagraph 对象 |
| rotation | int | 整数值 |

### appendText(TextFragment textFragment) {#appendText-com.aspose.pdf.TextFragment-}
```
public void appendText(TextFragment textFragment)
```


将文本片段附加到 Pdf 页面

--------------------

```
The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page.
 
 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 // create text fragment
 TextFragment tf = new TextFragment("main text");
 tf.Position = new Position(100, 600);
 // set it's text properties
 tf.getTextState().setFontSize ( 5);
 tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman"));
 tf.getTextState().setBackgroundColor ( Color.GREY);
 tf.getTextState().setForegroundColor ( Color.Red);
 // add one more segment to text fragment's Segments collection
 TextSegment segment2 = new TextSegment();
 segment2.setText ( "another segment");
 tf.getSegments.add(segment2);
 // create TextBuilder object
 TextBuilder builder = new TextBuilder(page);
 // append the text fragment to the Pdf page
 builder.appendText(tf);
 //save document
 doc.save(outFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textFragment | [TextFragment](../../com.aspose.pdf/textfragment) | 文本片段对象。 |

### appendText(List<TextFragment> textFragments) {#appendText-java.util.List-com.aspose.pdf.TextFragment--}
```
public final void appendText(List<TextFragment> textFragments)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textFragments | java.util.List<com.aspose.pdf.TextFragment> |  |

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
### getSegmenter() {#getSegmenter--}
```
public TextSegmenter getSegmenter()
```


获取 TextSegmenter 对象

**退货：**
[TextSegmenter](../../com.aspose.pdf.engine.commondata.text.segmenting/textsegmenter) - TextSegmenter 对象
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
