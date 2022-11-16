---
title: TextFragment
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 Pdf 文本的片段。
type: docs
weight: 372
url: /zh/java/com.aspose.pdf/textfragment/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public class TextFragment extends BaseParagraph
```

表示 Pdf 文本的片段。

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text and it's font.


  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");

  //查找将用于更改文档文本字体的字体
  Font font = FontRepository.findFont("Arial");

  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  //接受第一页的吸收器
  doc.getPages().get(1).accept(absorber);

  //更改第一个文本出现的文本和字体
  absorber.getTextFragments().get_Item(1).setText ( "hi world");
  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);

  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

```
In a few words, ```
TextFragment
``` object contains list of ```
TextSegment
``` objects.

 In details: Text of pdf document in ```
com.aspose.pdf
``` is represented by two basic objects:
 ```
文本片段
``` and ```
文本段
``` The differences between them is mostly
 context-dependent.

 Let's consider following scenario. User searches text "hello world" to operate with it, change
 it's properties, look etc.


  Document doc = new Document(docFile);
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  doc.getPages().get(1).accept(absorber);
```

Phisycally pdf 文本的表示非常复杂。文本“hello world”可能由几个物理上独立的文本段组成。 Aspose.Pdf 文本模型基本上建立了 TextFragment 对象提供单一逻辑操作集，而不是代表用户查询的物理 TextSegment 对象集。在文本搜索场景中，TextFragment 是逻辑上的“hello world”文本表示，TextSegment 对象集合表示构造“hello world”文本对象的所有物理段。因此，TextFragment 接近于逻辑文本表示。而 TextSegment 接近物理文本表示。显然，每个 TextSegment 对象都可能有自己的字体、颜色、定位属性。 TextFragment 提供了使用其属性更改文本的简单方法：设置字体、设置字体大小、设置字体颜色等。同时 TextSegment 对象是可访问的，用户可以独立地使用 TextSegment 对象进行操作。

请注意，更改 TextFragment 属性可能会更改内部 Segments 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部段或将它们合并为单个段。如果您的要求是保持 Segments 集合不变，请单独更改内部段。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFragment()](#TextFragment--) | 初始化 TextFragment 对象的新实例。 |
| [TextFragment(TabStops tabStops)](#TextFragment-com.aspose.pdf.TabStops-) | 使用预定义的 TabStops 位置初始化 TextFragment 对象的新实例。 |
| [TextFragment(String text)](#TextFragment-java.lang.String-) | 创建内部具有单个 TextSegment 对象的 TextFragment 对象。 |
| [TextFragment(String text, TabStops tabStops)](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | 创建内部具有单个 TextSegment 对象和预定义 TabStops 位置的 TextFragment 对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [cloneWithSegments()](#cloneWithSegments--) | 克隆包含所有片段的片段。 |
| [deepClone()](#deepClone--) | 克隆片段。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaselinePosition()](#getBaselinePosition--) | 获取文本的文本位置，用 TextFragment 对象表示。 |
| [getClass()](#getClass--) |  |
| [getEndNote()](#getEndNote--) | 获取段落尾注。 |
| [getFootNote()](#getFootNote--) | 获取段落脚注。 |
| [getForm()](#getForm--) | 获取包含 TextFragment 的表单对象
如果 TextFragment 对象不属于表单，则该值可以为 null。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取文本片段的水平对齐方式。 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getPage()](#getPage--) | 获取包含 TextFragment 的页面
如果 TextFragment 对象不属于任何页面，则该值可以为 null。 |
| [getPosition()](#getPosition--) | 获取文本的文本位置，用 TextFragment 对象表示。 |
| [getRectangle()](#getRectangle--) | 获取 TextFragment 的矩形 |
| [getReplaceOptions()](#getReplaceOptions--) | 获取文本替换选项。 |
| [getSegments()](#getSegments--) | 获取当前 TextFragment 的文本段。 |
| [getText()](#getText--) | 获取 TextFragment 对象表示的字符串文本对象。 |
| [getTextState()](#getTextState--) | 获取或设置 TextFragment 对象表示的文本的文本状态。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取文本片段的垂直对齐方式。 |
| [getWrapLinesCount()](#getWrapLinesCount--) | 获取本段的换行数（仅用于生成 pdf） |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [isolateTextSegments(int startIndex, int length)](#isolateTextSegments-int-int-) | 获取表示 TextFragment 文本指定部分的 TextSegment。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) | 设置文本的文本位置，用 TextFragment 对象表示。 |
| [setEndNote(Note value)](#setEndNote-com.aspose.pdf.Note-) | 设置段落尾注。 |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setFootNote(Note value)](#setFootNote-com.aspose.pdf.Note-) | 设置段落脚注。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置文本片段的水平对齐方式。 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置片段超链接 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setMarkedContentProperties(String name, int id)](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | 设置文本的文本位置，用 TextFragment 对象表示。 |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | 获取 TextFragment 的矩形 |
| [setSegments(TextSegmentCollection value)](#setSegments-com.aspose.pdf.TextSegmentCollection-) | 表示 setSegments 方法 |
| [setText(String value)](#setText-java.lang.String-) | 设置 TextFragment 对象表示的字符串文本对象。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置文本片段的垂直对齐方式。 |
| [setWrapLinesCount(int value)](#setWrapLinesCount-int-) | 设置此段落的换行数（仅用于生成 pdf） |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextFragment() {#TextFragment--}
```
public TextFragment()
```


初始化 TextFragment 对象的新实例。

### TextFragment(TabStops tabStops) {#TextFragment-com.aspose.pdf.TabStops-}
```
public TextFragment(TabStops tabStops)
```


使用预定义的 TabStops 位置初始化 TextFragment 对象的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| tabStops | [TabStops](../../com.aspose.pdf/tabstops) | 制表位置 |

### TextFragment(String text) {#TextFragment-java.lang.String-}
```
public TextFragment(String text)
```


创建内部具有单个 TextSegment 对象的 TextFragment 对象。指定段内的文本字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文本片段的文本。 |

### TextFragment(String text, TabStops tabStops) {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
```
public TextFragment(String text, TabStops tabStops)
```


创建内部具有单个 TextSegment 对象和预定义 TabStops 位置的 TextFragment 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 文本片段的文本。 |
| tabStops | [TabStops](../../com.aspose.pdf/tabstops) | 制表位置 |

### cloneWithSegments() {#cloneWithSegments--}
```
public Object cloneWithSegments()
```


克隆包含所有片段的片段。

**退货：**
java.lang.Object - 克隆的对象
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆片段。

**退货：**
java.lang.Object - 克隆的对象
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


获取文本的文本位置，用 TextFragment 对象表示。 Position 结构的 YIndent 表示文本片段的基线坐标。

**退货：**
[Position](../../com.aspose.pdf/position) - 位置值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEndNote() {#getEndNote--}
```
public Note getEndNote()
```


获取段落尾注。（仅用于 pdf 生成）

**退货：**
[Note](../../com.aspose.pdf/note) - 注意值
### getFootNote() {#getFootNote--}
```
public Note getFootNote()
```


获取段落脚注。（仅用于生成 pdf）

**退货：**
[Note](../../com.aspose.pdf/note) - 注意值
### getForm() {#getForm--}
```
public XForm getForm()
```


获取包含 TextFragment 的表单对象
如果 TextFragment 对象不属于表单，则该值可以为 null。

**退货：**
[XForm](../../com.aspose.pdf/xform) - 变形值
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取文本片段的水平对齐方式。

**退货：**
int - HorizontalAlignment 值
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


获取片段超链接（用于 pdf 生成器）。

**退货：**
[Hyperlink](../../com.aspose.pdf/hyperlink) - 片段超链接（用于 pdf 生成器）。
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取段落的外边距（用于生成 pdf）

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getPage() {#getPage--}
```
public Page getPage()
```


获取包含 TextFragment 的页面
如果 TextFragment 对象不属于任何页面，则该值可以为 null。

**退货：**
[Page](../../com.aspose.pdf/page) 页面对象
### getPosition() {#getPosition--}
```
public Position getPosition()
```


获取文本的文本位置，用 TextFragment 对象表示。

**退货：**
[Position](../../com.aspose.pdf/position) - 位置值

--------------------

```
The example demonstrates how to view placement of a text, represented by ```
TextFragment
``` object.

   //打开文档
   Document doc = new Document("D:\\Tests\\input.pdf");

   //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

   //接受第一页的吸收器
   doc.getPages().get(1).accept(absorber);

   //查看第一个文本出现的文本和位置信息
   TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1);

   System.out.println("fragment text: " + firstOccurrence.getText()));
   System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent()));
   System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent()));
```
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取 TextFragment 的矩形

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getReplaceOptions() {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```


获取文本替换选项。这些选项定义了将片段文本替换为更短/更长时的行为。

**退货：**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - TextReplaceOptions 实例
### getSegments() {#getSegments--}
```
public TextSegmentCollection getSegments()
```


获取当前 TextFragment 的文本段。

**退货：**
[TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) TextSegmentCollection 值

--------------------

```
The example demonstrates how to navigate all ```
TextSegment
``` objects inside ```
TextFragment
```.

  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");

  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  //接受第一页的吸收器
  doc.getPages().get(1).accept(absorber);

  //导航所有文本段并找出它们的文本和位置信息
  for (TextSegment segment : (```
Iterable
```)absorber.getTextFragments().get_Item(1).getSegments())
  {
      System.out.println("segment text: "+ segment.getText()));
      System.out.println("segment X indent: "+ segment.getPosition().getXIndent()));
      System.out.println("segment Y indent: "+ segment.getPosition().getYIndent()));
  }
```

--------------------

简而言之，TextSegment 对象是 TextFragment 对象的子对象。高级用户可以直接访问段以执行更复杂的文本编辑方案。具体请看TextFragment对象说明。
### getText() {#getText--}
```
public String getText()
```


获取 TextFragment 对象表示的字符串文本对象。

**退货：**
java.lang.String - 字符串值

--------------------

```
The example demonstrates how to search a text and replace first occurrence represented with ```

  TextFragment
``` object .

  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");

  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  //接受第一页的吸收器
  doc.getPages().get(1).accept(absorber);

  //更改第一个文本出现的字体
  absorber.getTextFragments().get_Item(1).setText ( "hi world");

  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```
### getTextState() {#getTextState--}
```
public TextFragmentState getTextState()
```


获取或设置 TextFragment 对象表示的文本的文本状态。

**退货：**
[TextFragmentState](../../com.aspose.pdf/textfragmentstate) - TextFragmentState 对象

--------------------

```
The example demonstrates how to change text color and font size of the text with ```
TextState
``` object.

  //打开文档
  Document doc = new Document("D:\\Tests\\input.pdf");

  //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  //接受第一页的吸收器
  doc.getPages().get(1).accept(absorber);

  //更改第一个文本出现的前景色
  absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED);

  //更改第一个文本出现的字体大小
  absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15);

  //保存文件
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

提供一种方法来更改文本的以下属性：Font FontSize FontStyle ForegroundColor BackgroundColor
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取文本片段的垂直对齐方式。

**退货：**
int - 整数值
### getWrapLinesCount() {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```


获取本段的换行数（仅用于生成 pdf）

**退货：**
int - 整数值
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


获取一个 int 值，该值指示图形的 Z 顺序。具有较大 ZIndex 的图形将被放置在具有较小 ZIndex 的图形之上。 ZIndex 可以是负数。具有负 ZIndex 的图形将放置在页面中文本的后面。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


获取一个段落是内联的。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


获取强制此段落在新页面生成的 bool 值。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isolateTextSegments(int startIndex, int length) {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```


获取表示 TextFragment 文本指定部分的 TextSegment。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 文本中新 TextSegment 开始的位置。 |
| length | int | 将被隔离到 TextSegment (s) 中的文本的长度。 |

**退货：**
[TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) - 包含文本段的 TextSegmentCollection，表示从指定位置开始并具有指定长度的文本子字符串。
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


设置文本的文本位置，用 TextFragment 对象表示。 Position 结构的 YIndent 表示文本片段的基线坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | 位置值 |

### setEndNote(Note value) {#setEndNote-com.aspose.pdf.Note-}
```
public void setEndNote(Note value)
```


设置段落尾注。（仅用于 pdf 生成）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Note](../../com.aspose.pdf/note) | 备注值 |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFootNote(Note value) {#setFootNote-com.aspose.pdf.Note-}
```
public void setFootNote(Note value)
```


设置段落脚注。（仅用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Note](../../com.aspose.pdf/note) | 备注值 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置文本片段的水平对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


设置片段超链接

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) |  |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


设置一个段落是内联的。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


设置一个布尔值，强制此段落在新页面生成。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置段落的外边距（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setMarkedContentProperties(String name, int id) {#setMarkedContentProperties-java.lang.String-int-}
```
public void setMarkedContentProperties(String name, int id)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String |  |
| id | int |  |

### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


设置文本的文本位置，用 TextFragment 对象表示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | 位置值

--------------------

```
The example demonstrates how to view placement of a text, represented by ```

                       TextFragment
```
                       object.

                        // Open document
                        Document doc = new Document("D:\\Tests\\input.pdf");

                        // Create TextFragmentAbsorber object to find all "hello world" text occurrences
                        TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

                        // Accept the absorber for first page
                        doc.getPages().get(1).accept(absorber);

                        // View text and placement info of first text occurrence
                        TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1);

                        System.out.println("fragment text: " + firstOccurrence.getText()));
                        System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent()));
                        System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent()));
``` |

### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(矩形值)
```


Gets rectangle of the TextFragment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle instance |

### setSegments(TextSegmentCollection value) {#setSegments-com.aspose.pdf.TextSegmentCollection-}
```
public void setSegments（TextSegmentCollection 值）
```


Represent setSegments method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) | TextSegmentCollection value |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(字符串值)
```


Sets  string  text object that the  TextFragment  object represents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value

--------------------

```
该示例演示了如何搜索文本并替换用
                       ```
文本片段
``` object .

                       //打开文档
                       Document doc = new Document("D:\\Tests\\input.pdf");

                       //创建 TextFragmentAbsorber 对象以查找所有出现的“hello world”文本
                       TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

                       //接受第一页的吸收器
                       doc.getPages().get(1).accept(absorber);

                       //更改第一个文本出现的字体
                       absorber.getTextFragments().get_Item(1).setText ( "hi world");

                       //保存文件
                       doc.save("D:\\Tests\\output.pdf");
``` |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int 值)
```


Sets a vertical alignment of text fragment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setWrapLinesCount(int value) {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int 值)
```


Sets wrap lines count for this paragraph(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int 值)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toString() {#toString--}
```
公共字符串 toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
公共最终无效等待（）
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
公共最终无效等待（长 arg0，int arg1）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
