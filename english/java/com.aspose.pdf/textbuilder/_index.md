---
title: TextBuilder
second_title: Aspose.PDF for Java API Reference
description: Appends text object to Pdf page.
type: docs
weight: 365
url: /java/com.aspose.pdf/textbuilder/
---
**Inheritance:**
java.lang.Object
```
public final class TextBuilder
```

Appends text object to Pdf page.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextBuilder(Page page)](#TextBuilder-com.aspose.pdf.Page-) | Initializes a new instance of  TextBuilder  class for the Pdf page. |
| [TextBuilder(Page page, BaseOperatorCollection operatorCollection)](#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-) | Initializes a new instance of  TextBuilder  class for the Pdf page. |
## Methods

| Method | Description |
| --- | --- |
| [getSegmenter()](#getSegmenter--) | Gets TextSegmenter object |
| [appendParagraph(TextParagraph textParagraph)](#appendParagraph-com.aspose.pdf.TextParagraph-) | Appends text paragraph to Pdf page. |
| [appendText(TextFragment textFragment)](#appendText-com.aspose.pdf.TextFragment-) | Appends text fragment to Pdf page |
| [appendText(List<TextFragment> textFragments)](#appendText-java.util.List-com.aspose.pdf.TextFragment--) |  |
| [appendParagraph(TextParagraph textParagraph, int rotation)](#appendParagraph-com.aspose.pdf.TextParagraph-int-) | Appends paragraph with rotation |
### TextBuilder(Page page) {#TextBuilder-com.aspose.pdf.Page-}
```
public TextBuilder(Page page)
```


Initializes a new instance of  TextBuilder  class for the Pdf page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object.

--------------------

The TextBuilder allows to append text objects to Pdf pages. |

### TextBuilder(Page page, BaseOperatorCollection operatorCollection) {#TextBuilder-com.aspose.pdf.Page-com.aspose.pdf.BaseOperatorCollection-}
```
public TextBuilder(Page page, BaseOperatorCollection operatorCollection)
```


Initializes a new instance of  TextBuilder  class for the Pdf page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object. |
| operatorCollection | [BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection) | Operator collection. |

### getSegmenter() {#getSegmenter--}
```
public TextSegmenter getSegmenter()
```


Gets TextSegmenter object

**Returns:**
[TextSegmenter](../../com.aspose.pdf.engine.commondata.text.segmenting/textsegmenter) - TextSegmenter object
### appendParagraph(TextParagraph textParagraph) {#appendParagraph-com.aspose.pdf.TextParagraph-}
```
public void appendParagraph(TextParagraph textParagraph)
```


Appends text paragraph to Pdf page.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textParagraph | [TextParagraph](../../com.aspose.pdf/textparagraph) | Text paragraph object. |

### appendText(TextFragment textFragment) {#appendText-com.aspose.pdf.TextFragment-}
```
public void appendText(TextFragment textFragment)
```


Appends text fragment to Pdf page

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFragment | [TextFragment](../../com.aspose.pdf/textfragment) | Text fragment object. |

### appendText(List<TextFragment> textFragments) {#appendText-java.util.List-com.aspose.pdf.TextFragment--}
```
public final void appendText(List<TextFragment> textFragments)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFragments | java.util.List<com.aspose.pdf.TextFragment> |  |

### appendParagraph(TextParagraph textParagraph, int rotation) {#appendParagraph-com.aspose.pdf.TextParagraph-int-}
```
public void appendParagraph(TextParagraph textParagraph, int rotation)
```


Appends paragraph with rotation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textParagraph | [TextParagraph](../../com.aspose.pdf/textparagraph) | TextParagraph object |
| rotation | int | int value |

