---
title: Heading
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表标题。
type: docs
weight: 151
url: /zh/java/com.aspose.pdf/heading/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.TextFragment](../../com.aspose.pdf/textfragment)
```
public final class Heading extends TextFragment
```

代表标题。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Heading()](#Heading--) | 仅供内部使用 |
| [Heading(int level)](#Heading-int-) | 初始化 Cell 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [cloneWithSegments()](#cloneWithSegments--) | 克隆包含所有段的标题。 |
| [deepClone()](#deepClone--) | 克隆标题。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaselinePosition()](#getBaselinePosition--) | 获取文本的文本位置，用 TextFragment 对象表示。 |
| [getClass()](#getClass--) |  |
| [getDestinationPage()](#getDestinationPage--) | 获取目标页面。 |
| [getEndNote()](#getEndNote--) | 获取段落尾注。 |
| [getFootNote()](#getFootNote--) | 获取段落脚注。 |
| [getForm()](#getForm--) | 获取包含 TextFragment 的表单对象
如果 TextFragment 对象不属于表单，则该值可以为 null。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取文本片段的水平对齐方式。 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getLevel()](#getLevel--) | 获得水平。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getPage()](#getPage--) | 获取包含 TextFragment 的页面
如果 TextFragment 对象不属于任何页面，则该值可以为 null。 |
| [getPosition()](#getPosition--) | 获取文本的文本位置，用 TextFragment 对象表示。 |
| [getRectangle()](#getRectangle--) | 获取 TextFragment 的矩形 |
| [getReplaceOptions()](#getReplaceOptions--) | 获取文本替换选项。 |
| [getSegments()](#getSegments--) | 获取当前 TextFragment 的文本段。 |
| [getStartNumber()](#getStartNumber--) | 获取标题起始编号。 |
| [getStyle()](#getStyle--) | 获取或设置样式。 |
| [getText()](#getText--) | 获取 TextFragment 对象表示的字符串文本对象。 |
| [getTextState()](#getTextState--) | 获取或设置 TextFragment 对象表示的文本的文本状态。 |
| [getTocPage()](#getTocPage--) | 获取包含此标题的页面。 |
| [getTop()](#getTop--) | 获取此标题的前 Y（供内部使用）。 |
| [getUserLabel()](#getUserLabel--) | 获取或设置用户标签。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取文本片段的垂直对齐方式。 |
| [getWrapLinesCount()](#getWrapLinesCount--) | 获取本段的换行数（仅用于生成 pdf） |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [isAutoSequence()](#isAutoSequence--) | 获取标题应自动编号。 |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInList()](#isInList--) | 获取标题应该在 toc 列表中。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [isolateTextSegments(int startIndex, int length)](#isolateTextSegments-int-int-) | 获取表示 TextFragment 文本指定部分的 TextSegment。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSequence(boolean value)](#setAutoSequence-boolean-) | 设置标题应自动编号。 |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) | 设置文本的文本位置，用 TextFragment 对象表示。 |
| [setDestinationPage(Page value)](#setDestinationPage-com.aspose.pdf.Page-) | 设置目标页面。 |
| [setEndNote(Note value)](#setEndNote-com.aspose.pdf.Note-) | 设置段落尾注。 |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setFootNote(Note value)](#setFootNote-com.aspose.pdf.Note-) | 设置段落脚注。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置文本片段的水平对齐方式。 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置片段超链接 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInList(boolean value)](#setInList-boolean-) | 设置标题应该在 toc 列表中。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setLevel(int value)](#setLevel-int-) | 设置电平。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setMarkedContentProperties(String name, int id)](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | 设置文本的文本位置，用 TextFragment 对象表示。 |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | 获取 TextFragment 的矩形 |
| [setSegments(TextSegmentCollection value)](#setSegments-com.aspose.pdf.TextSegmentCollection-) | 表示 setSegments 方法 |
| [setStartNumber(int value)](#setStartNumber-int-) | 获取标题起始编号。 |
| [setStyle(int value)](#setStyle-int-) | 设置或设置样式。 |
| [setText(String value)](#setText-java.lang.String-) | 设置 TextFragment 对象表示的字符串文本对象。 |
| [setTocPage(Page value)](#setTocPage-com.aspose.pdf.Page-) | 设置包含此标题的页面。 |
| [setTop(double value)](#setTop-double-) | 设置此标题的顶部 Y（供内部使用）。 |
| [setUserLabel(TextSegment value)](#setUserLabel-com.aspose.pdf.TextSegment-) | 获取或设置用户标签。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置文本片段的垂直对齐方式。 |
| [setWrapLinesCount(int value)](#setWrapLinesCount-int-) | 设置此段落的换行数（仅用于生成 pdf） |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Heading() {#Heading--}
```
public Heading()
```


仅供内部使用

### Heading(int level) {#Heading-int-}
```
public Heading(int level)
```


初始化 Cell 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| level | int | 标题级别。 |

### cloneWithSegments() {#cloneWithSegments--}
```
public Object cloneWithSegments()
```


克隆包含所有段的标题。

**退货：**
java.lang.Object - 克隆的对象
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆标题。

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
### getDestinationPage() {#getDestinationPage--}
```
public Page getDestinationPage()
```


获取目标页面。

**退货：**
[Page](../../com.aspose.pdf/page) - 目标页面。
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
### getLevel() {#getLevel--}
```
public int getLevel()
```


获得水平。

**退货：**
int - 标题级别。
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

  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);

  // Navigate all text segments and out their text and placement info
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
### getStartNumber() {#getStartNumber--}
```
public int getStartNumber()
```


获取标题起始编号。

**退货：**
int - 值：startNumber。
### getStyle() {#getStyle--}
```
public int getStyle()
```


获取或设置样式。

**退货：**
int - 标题样式。
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

  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);

  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).setText ( "hi world");

  // Save document
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

  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);

  // Change foreground color of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED);

  // Change font size of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15);

  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

--------------------

提供一种方法来更改文本的以下属性：Font FontSize FontStyle ForegroundColor BackgroundColor
### getTocPage() {#getTocPage--}
```
public Page getTocPage()
```


获取包含此标题的页面。

**退货：**
[Page](../../com.aspose.pdf/page) - 这页纸。
### getTop() {#getTop--}
```
public double getTop()
```


获取此标题的前 Y（供内部使用）。

**退货：**
double - 最高 Y 值
### getUserLabel() {#getUserLabel--}
```
public TextSegment getUserLabel()
```


获取或设置用户标签。

**退货：**
[TextSegment](../../com.aspose.pdf/textsegment) TextSegment 对象
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
### isAutoSequence() {#isAutoSequence--}
```
public boolean isAutoSequence()
```


获取标题应自动编号。

**退货：**
布尔值 - IsAutoSequens。
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
### isInList() {#isInList--}
```
public boolean isInList()
```


获取标题应该在 toc 列表中。

**退货：**
布尔值 - IsInList。
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




### setAutoSequence(boolean value) {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```


设置标题应自动编号。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | IsAutoSequens。 |

### setBaselinePosition(Position value) {#setBaselinePosition-com.aspose.pdf.Position-}
```
public void setBaselinePosition(Position value)
```


设置文本的文本位置，用 TextFragment 对象表示。 Position 结构的 YIndent 表示文本片段的基线坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | 位置值 |

### setDestinationPage(Page value) {#setDestinationPage-com.aspose.pdf.Page-}
```
public void setDestinationPage(Page value)
```


设置目标页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | 目标页面。 |

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

### setInList(boolean value) {#setInList-boolean-}
```
public void setInList(boolean value)
```


设置标题应该在 toc 列表中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | IsInList。 |

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

### setLevel(int value) {#setLevel-int-}
```
public void setLevel(int value)
```


设置电平。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 标题级别。 |

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

### setStartNumber(int value) {#setStartNumber-int-}
```
public void setStartNumber(int 值)
```


Gets the heading start number.

Value: The startNumber.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The startNumber. |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int 值)
```


sets or sets style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The heading style. |

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

                       // Open document
                       Document doc = new Document("D:\\Tests\\input.pdf");

                       // Create TextFragmentAbsorber object to find all "hello world" text occurrences
                       TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

                       // Accept the absorber for first page
                       doc.getPages().get(1).accept(absorber);

                       // Change font of the first text occurrence
                       absorber.getTextFragments().get_Item(1).setText ( "hi world");

                       // Save document
                       doc.save("D:\\Tests\\output.pdf");
``` |

### setTocPage(Page value) {#setTocPage-com.aspose.pdf.Page-}
```
public void setTocPage(页面值)
```


Sets the page that contains this heading.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | The page. |

### setTop(double value) {#setTop-double-}
```
public void setTop(双值)
```


sets the top Y of this headings(for internal use).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | The top Y value |

### setUserLabel(TextSegment value) {#setUserLabel-com.aspose.pdf.TextSegment-}
```
public void setUserLabel(TextSegment 值)
```


Gets or sets user label.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSegment](../../com.aspose.pdf/textsegment) | TextSegment object |

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
