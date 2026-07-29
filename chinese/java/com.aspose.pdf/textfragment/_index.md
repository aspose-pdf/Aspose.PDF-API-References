---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示 PDF 文本的片段。 </p> <hr> <pre> 示例演示如何在第一个 PDF 文档页面上查找文本并替换文本及其字体。 // Open document."
type: docs
weight: 5110
url: /zh/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> 表示 PDF 文本的片段。 </p> <hr> <pre> 示例演示如何在 PDF 文档的第一页查找文本并替换该文本及其字体。 // Open document Document doc = new Document("input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("output.pdf"); </pre> <hr> <pre> 简而言之，{@code TextFragment} 对象包含 {@code TextSegment} 对象的列表。详细说明：{@code com.aspose.pdf} 中的 PDF 文本由两种基本对象表示：{@code TextFragment} 和 {@code TextSegment}。它们之间的差异主要取决于上下文。我们考虑以下场景。用户搜索文本 "hello world" 以进行操作、修改其属性等。 Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> PDF 文本的物理表示非常复杂。文本 "hello world" 可能由多个物理上独立的文本段组成。Aspose.Pdf 文本模型基本上规定 {@code TextFragment} 对象在表示用户查询的物理 {@code TextSegment} 对象集合之上提供单一的逻辑操作集。在文本搜索场景中，{@code TextFragment} 是逻辑上的 "hello world" 文本表示，而 {@code TextSegment} 对象集合则表示构成 "hello world" 文本对象的所有物理段。因此，{@code TextFragment} 接近逻辑文本表示，{@code TextSegment} 接近物理文本表示。显然，每个 {@code TextSegment} 对象可能拥有自己的字体、颜色、定位属性。{@code TextFragment} 提供了一种简便的方法来更改文本及其属性：设置字体、设置字体大小、设置字体颜色等。同时，{@code TextSegment} 对象是可访问的，用户能够独立操作 {@code TextSegment} 对象。 <p> 请注意，修改 TextFragment 属性可能会更改内部 {@code Segments} 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部段或将它们合并为单个段。如果您的需求是保持 {@code Segments} 集合不变，请单独修改内部段。 </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFragment](#TextFragment--) | 初始化 {@code TextFragment} 对象的新实例。 |
| [TextFragment](#TextFragment-java.lang.String-) | 初始化 {@code TextFragment} 对象的新实例。 |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | 初始化 {@code TextFragment} 对象的新实例。 |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | 初始化 {@code TextFragment} 对象的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | 克隆包含所有段的片段。 |
| [deepClone](#deepClone--) | 克隆片段。 |
| [getBaselinePosition](#getBaselinePosition--) | 获取使用 {@code TextFragment} 对象表示的文本的位置。Position 结构的 YIndent 表示文本片段的基线坐标。 |
| [getEndNote](#getEndNote--) | 获取段落尾注。（仅用于 PDF 生成） |
| [getFootNote](#getFootNote--) | 获取段落脚注。（仅用于 PDF 生成） |
| [getForm](#getForm--) | 获取包含 TextFragment 的表单对象。如果 TextFragment 对象不属于任何表单，则该值可能为 null。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 获取文本片段的水平对齐方式。 |
| [getPage](#getPage--) | 获取包含 TextFragment 的页面。如果 TextFragment 对象不属于任何页面，则该值可能为 null。 |
| [getPosition](#getPosition--) | <p> 获取使用 {@code TextFragment} 对象表示的文本的位置。 </p> |
| [getRectangle](#getRectangle--) | 获取 TextFragment 的矩形。 |
| [getReplaceOptions](#getReplaceOptions--) | 获取文本替换选项。该选项定义当片段文本被替换为更短或更长时的行为。 |
| [getSegments](#getSegments--) | <p> 获取当前 {@code TextFragment} 的文本段。 </p> |
| [getText](#getText--) | <p> 获取 {@code TextFragment} 对象表示的 {@code string} 文本对象。 </p> |
| [getTextEditOptions](#getTextEditOptions--) | 获取或设置文本编辑选项。当请求的符号无法使用字体写入时，该选项定义特殊行为。 |
| [getTextState](#getTextState--) | <p> 获取或设置 {@code TextFragment} 对象表示的文本的文本状态。 </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | 获取文本片段的垂直对齐方式。 |
| [getWrapLinesCount](#getWrapLinesCount--) | 获取此段落的换行行数。（仅用于 PDF 生成） |
| [isolateTextSegments](#isolateTextSegments-int-int-) | 获取表示 {@code TextFragment} 文本指定部分的 {@code TextSegment}。 |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | 设置文本的位置，使用 {@code TextFragment} 对象表示。Position 结构的 YIndent 表示文本片段的基线坐标。 |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | 设置段落的尾注。（仅用于 PDF 生成） |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | 设置段落的脚注。（仅用于 PDF 生成） |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 设置文本片段的水平对齐方式。 |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置片段的超链接 |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> 设置文本的位置，使用 {@code TextFragment} 对象表示。 </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | 获取 TextFragment 的矩形。 |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | 表示 setSegments 方法 |
| [setText](#setText-java.lang.String-) | <p> 设置 {@code string} 文本对象，由 {@code TextFragment} 对象表示。 </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | 获取或设置文本编辑选项。当请求的符号无法使用字体写入时，该选项定义特殊行为。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 设置文本片段的垂直对齐方式。 |
| [setWrapLinesCount](#setWrapLinesCount-int-) | 设置此段落的换行行数（仅用于 PDF 生成） |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

初始化 {@code TextFragment} 对象的新实例。

### TextFragment {#TextFragment-java.lang.String-}
初始化 {@code TextFragment} 对象的新实例。

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
初始化 {@code TextFragment} 对象的新实例。

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
初始化 {@code TextFragment} 对象的新实例。

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

克隆包含所有段的片段。

**Returns:**
克隆的对象。

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆片段。

**Returns:**
克隆的对象。

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

获取使用 {@code TextFragment} 对象表示的文本的位置。Position 结构的 YIndent 表示文本片段的基线坐标。

**Returns:**
位置值

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

获取段落尾注。（仅用于 PDF 生成）

**Returns:**
注释值

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

获取段落脚注。（仅用于 PDF 生成）

**Returns:**
注释值

### getForm {#getForm--}
```
public XForm getForm()
```

获取包含 TextFragment 的表单对象。如果 TextFragment 对象不属于任何表单，则该值可能为 null。

**Returns:**
XForm 值

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

获取文本片段的水平对齐方式。

**Returns:**
HorizontalAlignment 值 @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

获取包含 TextFragment 的页面。如果 TextFragment 对象不属于任何页面，则该值可能为 null。

**Returns:**
Page 对象

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> 获取使用 {@code TextFragment} 对象表示的文本的位置。 </p>

**Returns:**
Position 值 <hr> <pre> 示例演示如何查看由 {@code TextFragment} 对象表示的文本的放置位置。 // 打开文档 Document doc = new Document("D:\\Tests\\input.pdf"); // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 接受第一页的吸收器 doc.getPages().get(1).accept(absorber); // 查看第一处文本出现的文本和位置信息 TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取 TextFragment 的矩形。

**Returns:**
Rectangle 对象

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

获取文本替换选项。该选项定义当片段文本被替换为更短或更长时的行为。

**Returns:**
TextReplaceOptions 实例

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> 获取当前 {@code TextFragment} 的文本段。 </p>

**Returns:**
TextSegmentCollection 值 <hr> <pre> 示例演示如何遍历 {@code TextFragment} 内的所有 {@code TextSegment} 对象。 // 打开文档 Document doc = new Document("D:\\Tests\\input.pdf"); // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 接受第一页的吸收器 doc.getPages().get(1).accept(absorber); // 遍历所有文本段并输出它们的文本和位置信息 for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> 简而言之，{@code TextSegment} 对象是 {@code TextFragment} 对象的子对象。高级用户可以直接访问段以执行更复杂的文本编辑场景。有关详细信息，请参阅 {@code TextFragment} 对象描述。 </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> 获取 {@code TextFragment} 对象表示的 {@code string} 文本对象。 </p>

**Returns:**
String 值 <hr> <pre> 示例演示如何搜索文本并替换由 {@code TextFragment} 对象表示的第一次出现。 // 打开文档 Document doc = new Document("D:\\Tests\\input.pdf"); // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 接受第一页的吸收器 doc.getPages().get(1).accept(absorber); // 更改第一次文本出现的字体 absorber.getTextFragments().get_Item(1).setText ( "hi world"); // 保存文档 doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

获取或设置文本编辑选项。当请求的符号无法使用字体写入时，该选项定义特殊行为。

**Returns:**
TextEditOptions 实例

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> 获取或设置 {@code TextFragment} 对象表示的文本的文本状态。 </p>

**Returns:**
TextFragmentState 对象 <hr> <pre> 示例演示如何使用 {@code TextState} 对象更改文本的颜色和字体大小。 // 打开文档 Document doc = new Document("D:\\Tests\\input.pdf"); // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 接受第一页的吸收器 doc.getPages().get(1).accept(absorber); // 更改第一次文本出现的前景色 absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // 更改第一次文本出现的字体大小 absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // 保存文档 doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> 提供一种更改文本以下属性的方法：Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

获取文本片段的垂直对齐方式。

**Returns:**
int 值 @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

获取此段落的换行行数。（仅用于 PDF 生成）

**Returns:**
int 值

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

获取表示 {@code TextFragment} 文本指定部分的 {@code TextSegment}。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex |  | 文本中新的 {@code TextSegment} 将开始的位置。 |
| length |  | 将被隔离为 {@code TextSegment} 的文本长度。 |

**Returns:**
{@code TextSegmentCollection} 包含从指定位置开始、具有指定长度的文本子串的文本段。

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
设置文本的位置，使用 {@code TextFragment} 对象表示。Position 结构的 YIndent 表示文本片段的基线坐标。

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
设置段落的尾注。（仅用于 PDF 生成）

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
设置段落的脚注。（仅用于 PDF 生成）

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
设置文本片段的水平对齐方式。

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
设置片段的超链接

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> 设置文本的位置，使用 {@code TextFragment} 对象表示。 </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
获取 TextFragment 的矩形。

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
表示 setSegments 方法

### setText {#setText-java.lang.String-}
<p> 设置 {@code string} 文本对象，由 {@code TextFragment} 对象表示。 </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
获取或设置文本编辑选项。当请求的符号无法使用字体写入时，该选项定义特殊行为。

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
设置文本片段的垂直对齐方式。

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

设置此段落的换行行数（仅用于 PDF 生成）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
