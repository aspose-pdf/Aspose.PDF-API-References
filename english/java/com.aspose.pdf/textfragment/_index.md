---
title: TextFragment
second_title: Aspose.PDF for Java API Reference
description: Represents fragment of Pdf text.
type: docs
weight: 376
url: /java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public class TextFragment extends BaseParagraph
```

Represents fragment of Pdf text.

--------------------

```
The example demonstrates how to find text on the first PDF document page and replace the text and it's font.


  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");

  // Find font that will be used to change document text font
  Font font = FontRepository.findFont("Arial");

  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get(1).accept(absorber);

  // Change text and font of the first text occurrence
  absorber.getTextFragments().get_Item(1).setText ( "hi world");
  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);

  // Save document
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
TextFragment
``` and ```
TextSegment
``` The differences between them is mostly
 context-dependent.

 Let's consider following scenario. User searches text "hello world" to operate with it, change
 it's properties, look etc.


  Document doc = new Document(docFile);
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  doc.getPages().get(1).accept(absorber);
```

Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments. The Aspose.Pdf text model basically establishes that  TextFragment  object provides single logic operation set over physical  TextSegment  objects set that represent user's query. In text search scenario,  TextFragment  is logical "hello world" text representation, and  TextSegment  object collection represents all physical segments that construct "hello world" text object. So,  TextFragment  is close to logical text representation. And  TextSegment  is close to physical text representation. Obviously each  TextSegment  object may have it's own font, coloring, positioning properties.  TextFragment  provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile  TextSegment  objects are accessible and users are able to operate with  TextSegment  objects independently.

Note that changing TextFragment properties may change inner  Segments  collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the  Segments  collection unchanged, please change inner segments individually.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragment()](#TextFragment--) | Initializes new instance of the  TextFragment  object. |
| [TextFragment(TabStops tabStops)](#TextFragment-com.aspose.pdf.TabStops-) | Initializes new instance of the  TextFragment  object with predefined  TabStops  positions. |
| [TextFragment(String text)](#TextFragment-java.lang.String-) | Creates  TextFragment  object with single  TextSegment  object inside. |
| [TextFragment(String text, TabStops tabStops)](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Creates  TextFragment  object with single  TextSegment  object inside and predefined  TabStops  positions. |
## Methods

| Method | Description |
| --- | --- |
| [getReplaceOptions()](#getReplaceOptions--) | Gets text replace options. |
| [getText()](#getText--) | Gets  string  text object that the  TextFragment  object represents. |
| [setText(String value)](#setText-java.lang.String-) | Sets  string  text object that the  TextFragment  object represents. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of text fragment. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of text fragment. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of text fragment. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of text fragment. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets the fragment hyperlink |
| [getTextState()](#getTextState--) | Gets or sets text state for the text that  TextFragment  object represents. |
| [getSegments()](#getSegments--) | Gets text segments for current  TextFragment . |
| [setSegments(TextSegmentCollection value)](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Represent setSegments method |
| [getPosition()](#getPosition--) | Gets text position for text, represented with  TextFragment  object. |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | Sets text position for text, represented with  TextFragment  object. |
| [getBaselinePosition()](#getBaselinePosition--) | Gets text position for text, represented with  TextFragment  object. |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) | Sets text position for text, represented with  TextFragment  object. |
| [getRectangle()](#getRectangle--) | Gets rectangle of the TextFragment |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Gets rectangle of the TextFragment |
| [getPage()](#getPage--) | Gets page that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to any page. |
| [getForm()](#getForm--) | Gets form object that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to a form. |
| [getWrapLinesCount()](#getWrapLinesCount--) | Gets wrap lines count for this paragraph(for pdf generation only) |
| [setWrapLinesCount(int value)](#setWrapLinesCount-int-) | Sets wrap lines count for this paragraph(for pdf generation only) |
| [getEndNote()](#getEndNote--) | Gets the paragraph end note.(for pdf generation only) |
| [setEndNote(Note value)](#setEndNote-com.aspose.pdf.Note-) | Sets the paragraph end note.(for pdf generation only) |
| [getFootNote()](#getFootNote--) | Gets the paragraph foot note.(for pdf generation only) |
| [setFootNote(Note value)](#setFootNote-com.aspose.pdf.Note-) | Sets the paragraph foot note.(for pdf generation only) |
| [isolateTextSegments(int startIndex, int length)](#isolateTextSegments-int-int-) | Gets  TextSegment (s) representing specified part of the  TextFragment  text. |
| [setMarkedContentProperties(String name, int id)](#setMarkedContentProperties-java.lang.String-int-) |  |
| [deepClone()](#deepClone--) | Clone the fragment. |
| [cloneWithSegments()](#cloneWithSegments--) | Clone the fragment with all segments. |
### TextFragment() {#TextFragment--}
```
public TextFragment()
```


Initializes new instance of the  TextFragment  object.

### TextFragment(TabStops tabStops) {#TextFragment-com.aspose.pdf.TabStops-}
```
public TextFragment(TabStops tabStops)
```


Initializes new instance of the  TextFragment  object with predefined  TabStops  positions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tabStops | [TabStops](../../com.aspose.pdf/tabstops) | Tabulation positions |

### TextFragment(String text) {#TextFragment-java.lang.String-}
```
public TextFragment(String text)
```


Creates  TextFragment  object with single  TextSegment  object inside. Specifies text string inside the segment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text fragment's text. |

### TextFragment(String text, TabStops tabStops) {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
```
public TextFragment(String text, TabStops tabStops)
```


Creates  TextFragment  object with single  TextSegment  object inside and predefined  TabStops  positions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text fragment's text. |
| tabStops | [TabStops](../../com.aspose.pdf/tabstops) | Tabulation positions |

### getReplaceOptions() {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```


Gets text replace options. The options define behavior when fragment text is replaced to more short/long.

**Returns:**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - TextReplaceOptions instance
### getText() {#getText--}
```
public String getText()
```


Gets  string  text object that the  TextFragment  object represents.

**Returns:**
java.lang.String - String value

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
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Sets  string  text object that the  TextFragment  object represents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value

--------------------

```
The example demonstrates how to search a text and replace first occurrence represented with
                       ```
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
``` |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a vertical alignment of text fragment.

**Returns:**
int - int value
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of text fragment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a horizontal alignment of text fragment.

**Returns:**
int - HorizontalAlignment value
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a horizontal alignment of text fragment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | HorizontalAlignment value |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


Sets the fragment hyperlink

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) |  |

### getTextState() {#getTextState--}
```
public TextFragmentState getTextState()
```


Gets or sets text state for the text that  TextFragment  object represents.

**Returns:**
[TextFragmentState](../../com.aspose.pdf/textfragmentstate) - TextFragmentState object

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

Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor
### getSegments() {#getSegments--}
```
public TextSegmentCollection getSegments()
```


Gets text segments for current  TextFragment .

**Returns:**
[TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) - TextSegmentCollection value

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

In a few words,  TextSegment  objects are children of  TextFragment  object. Advanced users may access segments directly to perform more complex text edit scenarios. For details, please look at  TextFragment  object description.
### setSegments(TextSegmentCollection value) {#setSegments-com.aspose.pdf.TextSegmentCollection-}
```
public void setSegments(TextSegmentCollection value)
```


Represent setSegments method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) | TextSegmentCollection value |

### getPosition() {#getPosition--}
```
public Position getPosition()
```


Gets text position for text, represented with  TextFragment  object.

**Returns:**
[Position](../../com.aspose.pdf/position) - Position value

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
### setPosition(Position value) {#setPosition-com.aspose.pdf.Position-}
```
public void setPosition(Position value)
```


Sets text position for text, represented with  TextFragment  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Position value

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

### getBaselinePosition() {#getBaselinePosition--}
```
public Position getBaselinePosition()
```


Gets text position for text, represented with  TextFragment  object. The YIndent of the Position structure represents baseline coordinate of the text fragment.

**Returns:**
[Position](../../com.aspose.pdf/position) - Position value
### setBaselinePosition(Position value) {#setBaselinePosition-com.aspose.pdf.Position-}
```
public void setBaselinePosition(Position value)
```


Sets text position for text, represented with  TextFragment  object. The YIndent of the Position structure represents baseline coordinate of the text fragment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Position value |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the TextFragment

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Gets rectangle of the TextFragment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle instance |

### getPage() {#getPage--}
```
public Page getPage()
```


Gets page that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to any page.

**Returns:**
[Page](../../com.aspose.pdf/page) - Page object
### getForm() {#getForm--}
```
public XForm getForm()
```


Gets form object that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to a form.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm value
### getWrapLinesCount() {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```


Gets wrap lines count for this paragraph(for pdf generation only)

**Returns:**
int - int value
### setWrapLinesCount(int value) {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```


Sets wrap lines count for this paragraph(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getEndNote() {#getEndNote--}
```
public Note getEndNote()
```


Gets the paragraph end note.(for pdf generation only)

**Returns:**
[Note](../../com.aspose.pdf/note) - Note value
### setEndNote(Note value) {#setEndNote-com.aspose.pdf.Note-}
```
public void setEndNote(Note value)
```


Sets the paragraph end note.(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Note](../../com.aspose.pdf/note) | Note value |

### getFootNote() {#getFootNote--}
```
public Note getFootNote()
```


Gets the paragraph foot note.(for pdf generation only)

**Returns:**
[Note](../../com.aspose.pdf/note) - Note value
### setFootNote(Note value) {#setFootNote-com.aspose.pdf.Note-}
```
public void setFootNote(Note value)
```


Sets the paragraph foot note.(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Note](../../com.aspose.pdf/note) | Note value |

### isolateTextSegments(int startIndex, int length) {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```


Gets  TextSegment (s) representing specified part of the  TextFragment  text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Position in text from which new  TextSegment (s) will start. |
| length | int | Length of the text that will isolated into  TextSegment (s). |

**Returns:**
[TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) -  TextSegmentCollection  containing text segments represeting text substring starting at a specifing position and having a specified length.
### setMarkedContentProperties(String name, int id) {#setMarkedContentProperties-java.lang.String-int-}
```
public void setMarkedContentProperties(String name, int id)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| id | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the fragment.

**Returns:**
java.lang.Object - The cloned object
### cloneWithSegments() {#cloneWithSegments--}
```
public Object cloneWithSegments()
```


Clone the fragment with all segments.

**Returns:**
java.lang.Object - The cloned object
