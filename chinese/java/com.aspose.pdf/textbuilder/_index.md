---
title: "TextBuilder"
linktitle: "TextBuilder"
second_title: "Aspose.PDF for Java API 参考"
description: "将文本对象追加到 Pdf 页面。"
type: docs
weight: 4940
url: /zh/java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextBuilder

```
public final class TextBuilder extends Object
```

将文本对象追加到 Pdf 页面。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-) | <p> 为 PDF 页面初始化 {@code TextBuilder} 类的新实例。 </p> |
| [TextBuilder](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | 为 PDF 页面初始化 {@code TextBuilder} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-) | <p> 将文本段落追加到 PDF 页面。 </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine(\"the quick brown fox jumps over the lazy dog\"); paragraph.appendLine(\"line2\"); paragraph.appendLine(\"line3\"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre> |
| [appendParagraph](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | 追加带旋转的段落 |
| [appendText](#appendText-java.util.List-) | 将文本片段列表追加到 PDF 页面。 |
| [appendText](#appendText-com.aspose.pdf.TextFragment-) | <p> 将文本片段追加到 PDF 页面 </p> <hr> <pre> The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [getSegmenter](#getSegmenter--) | 获取 TextSegmenter 对象 |

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-}
<p> 为 PDF 页面初始化 {@code TextBuilder} 类的新实例。 </p>

### TextBuilder {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
为 PDF 页面初始化 {@code TextBuilder} 类的新实例。

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-}
<p> 将文本段落追加到 PDF 页面。 </p> <hr> <pre> The example demonstrates how to create text paragraph object and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine(\"the quick brown fox jumps over the lazy dog\"); paragraph.appendLine(\"line2\"); paragraph.appendLine(\"line3\"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

### appendParagraph {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
追加带旋转的段落

### appendText {#appendText-java.util.List-}
将文本片段列表追加到 PDF 页面。

### appendText {#appendText-com.aspose.pdf.TextFragment-}
<p> 将文本片段追加到 PDF 页面 </p> <hr> <pre> The example demonstrates how to create text fragment object, customize it's text segments and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment(\"main text\"); tf.Position = new Position(100, 600); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont(\"TimesNewRoman\")); tf.getTextState().setBackgroundColor ( Color.GREY); tf.getTextState().setForegroundColor ( Color.Red); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( \"another segment\"); tf.getSegments.add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getSegmenter {#getSegmenter--}
```
public com.aspose.pdf.engine.commondata.text.segmenting.TextSegmenter getSegmenter()
```

获取 TextSegmenter 对象

**Returns:**
TextSegmenter 对象
