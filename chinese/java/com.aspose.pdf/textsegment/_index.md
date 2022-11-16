---
title: TextSegment
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 Pdf 文本段。
type: docs
weight: 386
url: /zh/java/com.aspose.pdf/textsegment/
---
**遗产：**
java.lang.Object
```
public final class TextSegment
```

表示 Pdf 文本段。

--------------------

```
The example demonstrates how to change text color and font size of the text with ```
TextState
``` object of
  ```
文本段
``` object.


  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");

  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  //接受第一页的吸收器
  doc.getPages().get(1).accept(absorber);

  //更改第一个文本出现的第一个文本段的前景色
  absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED);
  //更改第一个文本出现的第一个文本段的字体大小
  absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15);

  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

```
In a few words, ```
TextSegment
``` objects are children of ```
TextFragment
``` object.

 In details:

 Text of pdf document in ```
Aspose.Pdf
``` is represented by two basic objects:
 ```
文本片段
``` and ```
文本段
``` The differences between them is mostly
 context-dependent. Let's consider following scenario. User searches text "hello world" to operate
 with it, change it's properties, look etc.


  Document doc = new Document(docFile);
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  doc.getPages().get(1).accept(absorber);
```

物理上 pdf 文本的表示非常复杂。文本“hello world”可能由几个物理上独立的文本段组成。 Aspose.PDF 文本模型基本上建立了 TextFragment 对象提供单一逻辑操作集，而不是代表用户查询的物理 TextSegment 对象集。在文本搜索场景中，TextFragment 是逻辑上的“hello world”文本表示，TextSegment 对象集合表示构造“hello world”文本对象的所有物理段。因此，TextFragment 接近于逻辑文本表示。而 TextSegment 接近物理文本表示。显然，每个 TextSegment 对象都可能有自己的字体、颜色、定位属性。 TextFragment 提供了使用其属性更改文本的简单方法：设置字体、设置字体大小、设置字体颜色等。同时 TextSegment 对象是可访问的，用户可以独立地使用 TextSegment 对象进行操作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextSegment()](#TextSegment--) | 创建 TextSegment 对象。 |
| [TextSegment(String text)](#TextSegment-java.lang.String-) | 创建 TextSegment 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaselinePosition()](#getBaselinePosition--) | 获取文本的文本位置，用 TextSegment 对象表示。 |
| [getCharacters()](#getCharacters--) | 获取 CharInfo 对象的集合，这些对象表示有关文本段中字符的信息。 |
| [getClass()](#getClass--) |  |
| [getEndCharIndex()](#getEndCharIndex--) | 获取显示文本运算符 (Tj, TJ) 段中当前段的结束字符索引。 |
| [getHyperlink()](#getHyperlink--) | 获取或设置段超链接（用于 pdf 生成器）。 |
| [getPosition()](#getPosition--) | 获取文本的文本位置，用 TextSegment 对象表示。 |
| [getRectangle()](#getRectangle--) | 获取 TextSegment 的矩形 |
| [getStartCharIndex()](#getStartCharIndex--) | 获取显示文本运算符 (Tj, TJ) 段中当前段的起始字符索引。 |
| [getText()](#getText--) | 获取 TextSegment 对象表示的字符串文本对象。 |
| [getTextEditOptions()](#getTextEditOptions--) | 获取文本编辑选项。 |
| [getTextState()](#getTextState--) | 获取或设置 TextSegment 对象表示的文本的文本状态。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) | 设置文本的文本位置，用 TextSegment 对象表示。 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 获取或设置段超链接（用于 pdf 生成器）。 |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | 设置文本的文本位置，用 TextSegment 对象表示。 |
| [setText(String value)](#setText-java.lang.String-) | 设置 TextSegment 对象表示的字符串文本对象。 |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | 设置文本编辑选项。 |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) | 为 TextSegment 对象表示的文本设置文本状态。 |
| [setTextSuppressedUpdate(String value)](#setTextSuppressedUpdate-java.lang.String-) | 设置 TextSegment 对象表示希望抑制更新的字符串文本对象。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextSegment() {#TextSegment--}
```
public TextSegment()
```


创建 TextSegment 对象。

--------------------

```
The example demonstrates how to create text fragment object, add a text segment to the text fragment
 collection and append it to the Pdf page.


 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 //创建文本片段
 TextFragment tf = new TextFragment("main text");
 tf.setPosition ( new Position(100, 600));
 //设置它的文本属性
 tf.getTextState().setFontSize ( 5);
 tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman"));
 tf.getTextState().setBackgroundColor ( Color.GRAY);
 tf.getTextState().setForegroundColor ( Color.RED);
 //在文本片段的 Segments 集合中再添加一个片段
 TextSegment segment2 = new TextSegment();
 segment2.setText ( "another segment");
 tf.getSegments().add(segment2);
 //创建 TextBuilder 对象
 TextBuilder builder = new TextBuilder(page);
 //将文本片段附加到 Pdf 页面
 builder.appendText(tf);
 //保存文档
 doc.save(outFile);
```

### TextSegment(String text) {#TextSegment-java.lang.String-}
```
public TextSegment(String text)
```


创建 TextSegment 对象。

```
The example demonstrates how to create text fragment object, add a text segment to the text fragment
 collection and append it to the Pdf page.

 Document doc = new Document(inFile);
 Page page = (Page)doc.getPages().get(1);
 //创建文本片段
 TextFragment tf = new TextFragment("main text");
 tf.setPosition ( new Position(100, 600));
 //设置它的文本属性
 tf.getTextState().setFontSize ( 5);
 tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman"));
 tf.getTextState().setBackgroundColor ( Color.GRAY);
 tf.getTextState().setForegroundColor ( Color.RED);
 //在文本片段的 Segments 集合中再添加一个片段
 TextSegment segment2 = new TextSegment("another segment");
 tf.getSegments().add(segment2);
 //创建 TextBuilder 对象
 TextBuilder builder = new TextBuilder(page);
 //将文本片段附加到 Pdf 页面
 builder.appendText(tf);
 //保存文档
 doc.save(outFile);
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文本段的文本。 |

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
### getBaselinePosition() {#getBaselinePosition--}
```
public Position getBaselinePosition()
```


获取文本的文本位置，用 TextSegment 对象表示。 Position 结构的 YIndent 表示文本段的基线坐标。

**退货：**
[Position](../../com.aspose.pdf/position) - 位置值
### getCharacters() {#getCharacters--}
```
public CharInfoCollection getCharacters()
```


获取 CharInfo 对象的集合，这些对象表示有关文本段中字符的信息。

**退货：**
[CharInfoCollection](../../com.aspose.pdf/charinfocollection) - CharInfoCollection 对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEndCharIndex() {#getEndCharIndex--}
```
public int getEndCharIndex()
```


获取显示文本运算符 (Tj, TJ) 段中当前段的结束字符索引。

**退货：**
int - 整数值
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


获取或设置段超链接（用于 pdf 生成器）。

**退货：**
[Hyperlink](../../com.aspose.pdf/hyperlink) 超链接对象
### getPosition() {#getPosition--}
```
public Position getPosition()
```


获取文本的文本位置，用 TextSegment 对象表示。

**退货：**
[Position](../../com.aspose.pdf/position) - 位置值
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取 TextSegment 的矩形

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getStartCharIndex() {#getStartCharIndex--}
```
public int getStartCharIndex()
```


获取显示文本运算符 (Tj, TJ) 段中当前段的起始字符索引。

**退货：**
int - 整数值
### getText() {#getText--}
```
public String getText()
```


获取 TextSegment 对象表示的字符串文本对象。

**退货：**
java.lang.String - 字符串值
### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


获取文本编辑选项。这些选项定义了请求的符号不能用字体书写时的特殊行为。

**退货：**
[TextEditOptions](../../com.aspose.pdf/texteditoptions) TextEditOptions 值
### getTextState() {#getTextState--}
```
public TextState getTextState()
```


获取或设置 TextSegment 对象表示的文本的文本状态。

--------------------

提供一种方法来更改文本的以下属性：Font FontSize FontStyle ForegroundColor BackgroundColor

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态值
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




### setBaselinePosition(Position value) {#setBaselinePosition-com.aspose.pdf.Position-}
```
public void setBaselinePosition(Position value)
```


设置文本的文本位置，用 TextSegment 对象表示。 Position 结构的 YIndent 表示文本段的基线坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | 位置值 |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


获取或设置段超链接（用于 pdf 生成器）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | 超链接对象 |

### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


设置文本的文本位置，用 TextSegment 对象表示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | 位置值 |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


设置 TextSegment 对象表示的字符串文本对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions(TextEditOptions value)
```


设置文本编辑选项。这些选项定义了请求的符号不能用字体书写时的特殊行为。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) | 文本编辑选项值 |

### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public void setTextState(TextState value)
```


为 TextSegment 对象表示的文本设置文本状态。

--------------------

提供一种方法来更改文本的以下属性：Font FontSize FontStyle ForegroundColor BackgroundColor

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态值 |

### setTextSuppressedUpdate(String value) {#setTextSuppressedUpdate-java.lang.String-}
```
public void setTextSuppressedUpdate(String value)
```


设置 TextSegment 对象表示希望抑制更新的字符串文本对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

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
