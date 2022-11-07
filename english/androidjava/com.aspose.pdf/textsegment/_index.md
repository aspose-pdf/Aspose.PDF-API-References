---
title: TextSegment
second_title: Aspose.PDF for Java API Reference
description: Represents segment of Pdf text.
type: docs
weight: 307
url: /java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object
```
public final class TextSegment
```

Represents segment of Pdf text.

--------------------

> ```
> The example demonstrates how to change text color and font size of the text with ```
> TextState
> ``` object of ```
> TextSegment
> ``` object.
>    
>   // Open document
>   Document doc = new Document("D:\Tests\input.pdf");
>   
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.getPages().get(1).accept(absorber);
>   
>   // Change foreground color of the first text segment of the first text occurrence
>   absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED);
>   // Change font size of the first text segment of the first text occurrence
>   absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15);
>   
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```

--------------------

In a few words,  TextSegment  objects are children of  TextFragment  object. In details: Text of pdf document in  Aspose.Pdf  is represented by two basic objects:  TextFragment  and  TextSegment  The differences between them is mostly context-dependent. Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc.

```
Document doc = new Document(docFile);
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  doc.Pages[1].Accept(absorber);
```

Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments. The Aspose.Pdf text model basically establishes that  TextFragment  object provides single logic operation set over physical  TextSegment  objects set that represent user's query. In text search scenario,  TextFragment  is logical "hello world" text representation, and  TextSegment  object collection represents all physical segments that construct "hello world" text object. So,  TextFragment  is close to logical text representation. And  TextSegment  is close to physical text representation. Obviously each  TextSegment  object may have it's own font, coloring, positioning properties.  TextFragment  provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile  TextSegment  objects are accessible and users are able to operate with  TextSegment  objects independently.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextSegment()](#TextSegment--) | Creates TextSegment object. |
| [TextSegment(String text)](#TextSegment-java.lang.String-) | Creates TextSegment object. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets or sets  string  text object that the  TextSegment  object represents. |
| [setText(String value)](#setText-java.lang.String-) |  |
| [getTextState()](#getTextState--) | Gets or sets text state for the text that  TextSegment  object represents. |
| [setTextState(TextState value)](#setTextState-com.aspose.pdf.TextState-) |  |
| [getPosition()](#getPosition--) | Gets text position for text, represented with  TextSegment  object. |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) |  |
| [getRectangle()](#getRectangle--) | Gets rectangle of the TextSegment |
| [getBaselinePosition()](#getBaselinePosition--) | Gets text position for text, represented with  TextSegment  object. |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) |  |
| [getTextEditOptions()](#getTextEditOptions--) | Gets or sets text edit options. |
| [setTextEditOptions(TextEditOptions value)](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) |  |
| [getCharacters()](#getCharacters--) | Gets collection of CharInfo objects that represent information on characters in the text segment. |
### TextSegment() {#TextSegment--}
```
public TextSegment()
```


Creates TextSegment object.

--------------------

> ```
> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page.
>   
>  Document doc = new Document(inFile);
>  Page page = (Page)doc.Pages[1];
>  // create text fragment
>  TextFragment tf = new TextFragment("main text");
>  tf.Position = new Position(100, 600);
>  // set it's text properties
>  tf.getTextState().setFontSize ( 5);
>  tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman"));
>  tf.getTextState().setBackgroundColor ( Color.GRAY);
>  tf.getTextState().setForegroundColor ( Color.RED);
>  // add one more segment to text fragment's Segments collection
>  TextSegment segment2 = new TextSegment();
>  segment2.setText ( "another segment");
>  tf.getSegments().add(segment2);
>  // create TextBuilder object
>  TextBuilder builder = new TextBuilder(page);
>  // append the text fragment to the Pdf page
>  builder.appendText(tf);
>  //save document
>  doc.save(outFile);
> ```

### TextSegment(String text) {#TextSegment-java.lang.String-}
```
public TextSegment(String text)
```


Creates TextSegment object.

--------------------

> ```
> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page.
>   
>  Document doc = new Document(inFile);
>  Page page = (Page)doc.getPages().get(1);
>  // create text fragment
>  TextFragment tf = new TextFragment("main text");
>  tf.setPosition ( new Position(100, 600));
>  // set it's text properties
>  tf.getTextState().setFontSize ( 5);
>  tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman"));
>  tf.getTextState().setBackgroundColor ( Color.GRAY);
>  tf.getTextState().setForegroundColor ( Color.RED);
>  // add one more segment to text fragment's Segments collection
>  TextSegment segment2 = new TextSegment("another segment");
>  tf.getSegments().add(segment2);
>  // create TextBuilder object
>  TextBuilder builder = new TextBuilder(page);
>  // append the text fragment to the Pdf page
>  builder.appendText(tf);
>  //save document
>  doc.save(outFile);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text segment's text. |

### getText() {#getText--}
```
public String getText()
```


Gets or sets  string  text object that the  TextSegment  object represents.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextState() {#getTextState--}
```
public TextState getTextState()
```


Gets or sets text state for the text that  TextSegment  object represents.

--------------------

Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor

**Returns:**
[TextState](../../com.aspose.pdf/textstate)
### setTextState(TextState value) {#setTextState-com.aspose.pdf.TextState-}
```
public void setTextState(TextState value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) |  |

### getPosition() {#getPosition--}
```
public Position getPosition()
```


Gets text position for text, represented with  TextSegment  object.

**Returns:**
[Position](../../com.aspose.pdf/position)
### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the TextSegment

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### getBaselinePosition() {#getBaselinePosition--}
```
public Position getBaselinePosition()
```


Gets text position for text, represented with  TextSegment  object. The YIndent of the Position structure represents baseline coordinate of the text segment.

**Returns:**
[Position](../../com.aspose.pdf/position)
### setBaselinePosition(Position value) {#setBaselinePosition-com.aspose.pdf.Position-}
```
public void setBaselinePosition(Position value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) |  |

### getTextEditOptions() {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```


Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Returns:**
[TextEditOptions](../../com.aspose.pdf/texteditoptions)
### setTextEditOptions(TextEditOptions value) {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
```
public void setTextEditOptions(TextEditOptions value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextEditOptions](../../com.aspose.pdf/texteditoptions) |  |

### getCharacters() {#getCharacters--}
```
public CharInfoCollection getCharacters()
```


Gets collection of CharInfo objects that represent information on characters in the text segment.

**Returns:**
[CharInfoCollection](../../com.aspose.pdf/charinfocollection)
