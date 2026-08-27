---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 表示 PDF 文本的片段。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象的 {@code 来更改文本的颜色和字体大小。"
type: docs
weight: 5300
url: /zh/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> 表示 PDF 文本的片段。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象的 {@code TextSegment} 对象来更改文本的颜色和字体大小。 // 打开文档 Document doc = new Document("D:\\Tests\\input.pdf"); // 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 接受吸收器以处理第一页 doc.getPages().get(1).accept(absorber); // 将第一次文本出现的第一个文本段的前景颜色更改为 absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // 将第一次文本出现的第一个文本段的字体大小更改为 absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // 保存文档 doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> 简而言之，{@code TextSegment} 对象是 {@code TextFragment} 对象的子对象。详细来说，{@code Aspose.Pdf} 中的 PDF 文本由两个基本对象表示：{@code TextFragment} 和 {@code TextSegment}。它们之间的差异主要取决于上下文。让我们考虑以下场景。用户搜索文本 "hello world" 以对其进行操作、更改其属性、查看等。 Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> PDF 文本的物理表示非常复杂。文本 "hello world" 可能由多个物理上独立的文本段组成。Aspose.PDF 文本模型基本上规定，{@code TextFragment} 对象在表示用户查询的物理 {@code TextSegment} 对象集合之上提供单一的逻辑操作集合。在文本搜索场景中，{@code TextFragment} 是逻辑上的 "hello world" 文本表示，而 {@code TextSegment} 对象集合表示构成 "hello world" 文本对象的所有物理段。因此，{@code TextFragment} 接近逻辑文本表示，而 {@code TextSegment} 接近物理文本表示。显然，每个 {@code TextSegment} 对象可能拥有其自己的字体、颜色、定位属性。{@code TextFragment} 提供了简单的方法来更改文本及其属性：设置字体、设置字体大小、设置字体颜色等。与此同时，{@code TextSegment} 对象是可访问的，用户可以独立地操作 {@code TextSegment} 对象。 </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> 创建 TextSegment 对象。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象的 {@code TextSegment} 对象来更改文本的颜色和字体大小。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // 创建文本片段 TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // 设置其文本属性 tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // 向文本片段的 Segments 集合添加另一个段 TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // 创建 TextBuilder 对象 TextBuilder builder = new TextBuilder(page); // 将文本片段附加到 PDF 页面 builder.appendText(tf); // 保存文档 doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> 创建 TextSegment 对象。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象的 {@code TextSegment} 对象来更改文本的颜色和字体大小。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // 创建文本片段 TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // 设置其文本属性 tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // 向文本片段的 Segments 集合添加另一个段 TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // 创建 TextBuilder 对象 TextBuilder builder = new TextBuilder(page); // 将文本片段附加到 PDF 页面 builder.appendText(tf); // 保存文档 doc.save(outFile); </pre> |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | 获取文本位置，文本由 {@code TextSegment} 对象表示。Position 结构体的 YIndent 表示文本段的基线坐标。 |
| [getCharacters](#getCharacters--) | 获取 CharInfo 对象的集合，这些对象表示文本段中字符的信息。 |
| [getEndCharIndex](#getEndCharIndex--) | 获取当前段在显示文本操作符 (Tj, TJ) 段中的结束字符索引。 |
| [getHyperlink](#getHyperlink--) | 获取或设置段超链接（用于 PDF 生成器）。 |
| [getPosition](#getPosition--) | 获取文本的位置，由 {@code TextSegment} 对象表示。 |
| [getRectangle](#getRectangle--) | 获取 TextSegment 的矩形。 |
| [getStartCharIndex](#getStartCharIndex--) | 获取当前段在显示文本操作符 (Tj, TJ) 段中的起始字符索引。 |
| [getText](#getText--) | 获取 {@code string} 文本对象，该对象由 {@code TextSegment} 对象表示。 |
| [getTextEditOptions](#getTextEditOptions--) | 获取文本编辑选项。这些选项定义当请求的符号无法使用字体写入时的特殊行为。 |
| [getTextState](#getTextState--) | <p> 获取或设置 {@code TextSegment} 对象所表示的文本的文本状态。 </p> <hr> <p> 提供一种更改文本以下属性的方法： Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | 设置文本的位置，由 {@code TextSegment} 对象表示。Position 结构的 YIndent 表示文本段的基线坐标。 |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | 获取或设置段超链接（用于 PDF 生成器）。 |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | 设置文本的位置，由 {@code TextSegment} 对象表示。 |
| [setText](#setText-java.lang.String-) | 设置 {@code string} 文本对象，该对象由 {@code TextSegment} 对象表示。 |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | 设置文本编辑选项。该选项定义当请求的字符无法使用字体写入时的特殊行为。 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> 设置 {@code TextSegment} 对象所表示的文本的文本状态。 </p> <hr> <p> 提供一种更改文本以下属性的方法： Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | 设置 {@code string} 文本对象，该对象由 {@code TextSegment} 对象表示，且抑制更新。 |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> 创建 TextSegment 对象。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象的 {@code TextSegment} 对象来更改文本的颜色和字体大小。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // 创建文本片段 TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // 设置其文本属性 tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // 向文本片段的 Segments 集合添加另一个段 TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // 创建 TextBuilder 对象 TextBuilder builder = new TextBuilder(page); // 将文本片段附加到 PDF 页面 builder.appendText(tf); // 保存文档 doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> 创建 TextSegment 对象。 </p> <hr> <pre> 示例演示如何使用 {@code TextState} 对象的 {@code TextSegment} 对象来更改文本的颜色和字体大小。 Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // 创建文本片段 TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // 设置其文本属性 tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // 向文本片段的 Segments 集合添加另一个段 TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // 创建 TextBuilder 对象 TextBuilder builder = new TextBuilder(page); // 将文本片段附加到 PDF 页面 builder.appendText(tf); // 保存文档 doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

获取文本位置，文本由 {@code TextSegment} 对象表示。Position 结构体的 YIndent 表示文本段的基线坐标。

**Returns:**
位置值

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

获取 CharInfo 对象的集合，这些对象表示文本段中字符的信息。

**Returns:**
CharInfoCollection 对象

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

获取当前段在显示文本操作符 (Tj, TJ) 段中的结束字符索引。

**Returns:**
int 值

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

获取或设置段超链接（用于 PDF 生成器）。

**Returns:**
Hyperlink 对象

### getPosition {#getPosition--}
```
public Position getPosition()
```

获取文本的位置，由 {@code TextSegment} 对象表示。

**Returns:**
位置值

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取 TextSegment 的矩形。

**Returns:**
Rectangle 对象

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

获取当前段在显示文本操作符 (Tj, TJ) 段中的起始字符索引。

**Returns:**
int 值

### getText {#getText--}
```
public String getText()
```

获取 {@code string} 文本对象，该对象由 {@code TextSegment} 对象表示。

**Returns:**
字符串值

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

获取文本编辑选项。这些选项定义当请求的符号无法使用字体写入时的特殊行为。

**Returns:**
TextEditOptions 值

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> 获取或设置 {@code TextSegment} 对象所表示的文本的文本状态。 </p> <hr> <p> 提供一种更改文本以下属性的方法： Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
TextState 值

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
设置文本的位置，由 {@code TextSegment} 对象表示。Position 结构的 YIndent 表示文本段的基线坐标。

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
获取或设置段超链接（用于 PDF 生成器）。

### setPosition {#setPosition-com.aspose.pdf.Position-}
设置文本的位置，由 {@code TextSegment} 对象表示。

### setText {#setText-java.lang.String-}
设置 {@code string} 文本对象，该对象由 {@code TextSegment} 对象表示。

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
设置文本编辑选项。该选项定义当请求的字符无法使用字体写入时的特殊行为。

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> 设置 {@code TextSegment} 对象所表示的文本的文本状态。 </p> <hr> <p> 提供一种更改文本以下属性的方法： Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
设置 {@code string} 文本对象，该对象由 {@code TextSegment} 对象表示，且抑制更新。
