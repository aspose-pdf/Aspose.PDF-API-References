---
title: TextSegment
second_title: Aspose.PDF for Java API Reference
description: <p> Represents segment of Pdf text. </p> <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object of {@code.
type: docs
weight: 5300
url: /java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> Represents segment of Pdf text. </p> <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object of {@code TextSegment} object. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> In a few words, {@code TextSegment} objects are children of {@code TextFragment} object. In details: Text of pdf document in {@code Aspose.Pdf} is represented by two basic objects: {@code TextFragment} and {@code TextSegment} The differences between them is mostly context-dependent. Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> Physically pdf text's representation is very complex. The text "hello world" may consist of several physically independent text segments. The Aspose.PDF text model basically establishes that {@code TextFragment} object provides single logic operation set over physical {@code TextSegment} objects set that represent user's query. In text search scenario, {@code TextFragment} is logical "hello world" text representation, and {@code TextSegment} object collection represents all physical segments that construct "hello world" text object. So, {@code TextFragment} is close to logical text representation. And {@code TextSegment} is close to physical text representation. Obviously each {@code TextSegment} object may have it's own font, coloring, positioning properties. {@code TextFragment} provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile {@code TextSegment} objects are accessible and users are able to operate with {@code TextSegment} objects independently. </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> Creates TextSegment object. </p> <hr> <pre> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> Creates TextSegment object. </p> <hr> <pre> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | Gets text position for text, represented with {@code TextSegment} object. The YIndent of the Position structure represents baseline coordinate of the text segment. |
| [getCharacters](#getCharacters--) | Gets collection of CharInfo objects that represent information on characters in the text segment. |
| [getEndCharIndex](#getEndCharIndex--) | Gets ending character index of current segment in the show text operator (Tj, TJ) segment. |
| [getHyperlink](#getHyperlink--) | Gets or sets the segment hyperlink(for pdf generator). |
| [getPosition](#getPosition--) | Gets text position for text, represented with {@code TextSegment} object. |
| [getRectangle](#getRectangle--) | Gets rectangle of the TextSegment |
| [getStartCharIndex](#getStartCharIndex--) | Gets starting character index of current segment in the show text operator (Tj, TJ) segment. |
| [getText](#getText--) | Gets {@code string} text object that the {@code TextSegment} object represents. |
| [getTextEditOptions](#getTextEditOptions--) | Gets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [getTextState](#getTextState--) | <p> Gets or sets text state for the text that {@code TextSegment} object represents. </p> <hr> <p> Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Sets text position for text, represented with {@code TextSegment} object. The YIndent of the Position structure represents baseline coordinate of the text segment. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Gets or sets the segment hyperlink(for pdf generator). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Sets text position for text, represented with {@code TextSegment} object. |
| [setText](#setText-java.lang.String-) | Sets {@code string} text object that the {@code TextSegment} object represents. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> Sets text state for the text that {@code TextSegment} object represents. </p> <hr> <p> Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | Sets {@code string} text object that the {@code TextSegment} object represents wish suppressed update. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> Creates TextSegment object. </p> <hr> <pre> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> Creates TextSegment object. </p> <hr> <pre> The example demonstrates how to create text fragment object, add a text segment to the text fragment collection and append it to the Pdf page. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text fragment TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // set it's text properties tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // add one more segment to text fragment's Segments collection TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // create TextBuilder object TextBuilder builder = new TextBuilder(page); // append the text fragment to the Pdf page builder.appendText(tf); //save document doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Gets text position for text, represented with {@code TextSegment} object. The YIndent of the Position structure represents baseline coordinate of the text segment.

**Returns:**
Position value

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

Gets collection of CharInfo objects that represent information on characters in the text segment.

**Returns:**
CharInfoCollection object

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

Gets ending character index of current segment in the show text operator (Tj, TJ) segment.

**Returns:**
int value

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

Gets or sets the segment hyperlink(for pdf generator).

**Returns:**
Hyperlink object

### getPosition {#getPosition--}
```
public Position getPosition()
```

Gets text position for text, represented with {@code TextSegment} object.

**Returns:**
Position value

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle of the TextSegment

**Returns:**
Rectangle object

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

Gets starting character index of current segment in the show text operator (Tj, TJ) segment.

**Returns:**
int value

### getText {#getText--}
```
public String getText()
```

Gets {@code string} text object that the {@code TextSegment} object represents.

**Returns:**
String value

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Gets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Returns:**
TextEditOptions value

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> Gets or sets text state for the text that {@code TextSegment} object represents. </p> <hr> <p> Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
TextState value

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Sets text position for text, represented with {@code TextSegment} object. The YIndent of the Position structure represents baseline coordinate of the text segment.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Gets or sets the segment hyperlink(for pdf generator).

### setPosition {#setPosition-com.aspose.pdf.Position-}
Sets text position for text, represented with {@code TextSegment} object.

### setText {#setText-java.lang.String-}
Sets {@code string} text object that the {@code TextSegment} object represents.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Sets text edit options. The options define special behavior when requested symbol cannot be written with font.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> Sets text state for the text that {@code TextSegment} object represents. </p> <hr> <p> Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
Sets {@code string} text object that the {@code TextSegment} object represents wish suppressed update.
