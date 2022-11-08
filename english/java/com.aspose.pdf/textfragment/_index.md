---
title: TextFragment
second_title: Aspose.PDF for Java API Reference
description: Represents fragment of Pdf text.
type: docs
weight: 372
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
| [cloneWithSegments()](#cloneWithSegments--) | Clone the fragment with all segments. |
| [deepClone()](#deepClone--) | Clone the fragment. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaselinePosition()](#getBaselinePosition--) | Gets text position for text, represented with  TextFragment  object. |
| [getClass()](#getClass--) |  |
| [getEndNote()](#getEndNote--) | Gets the paragraph end note. |
| [getFootNote()](#getFootNote--) | Gets the paragraph foot note. |
| [getForm()](#getForm--) | Gets form object that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to a form. |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets a horizontal alignment of text fragment. |
| [getHyperlink()](#getHyperlink--) | Gets the fragment hyperlink(for pdf generator). |
| [getMargin()](#getMargin--) | Gets a outer margin for paragraph (for pdf generation) |
| [getPage()](#getPage--) | Gets page that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to any page. |
| [getPosition()](#getPosition--) | Gets text position for text, represented with  TextFragment  object. |
| [getRectangle()](#getRectangle--) | Gets rectangle of the TextFragment |
| [getReplaceOptions()](#getReplaceOptions--) | Gets text replace options. |
| [getSegments()](#getSegments--) | Gets text segments for current  TextFragment . |
| [getText()](#getText--) | Gets  string  text object that the  TextFragment  object represents. |
| [getTextState()](#getTextState--) | Gets or sets text state for the text that  TextFragment  object represents. |
| [getVerticalAlignment()](#getVerticalAlignment--) | Gets a vertical alignment of text fragment. |
| [getWrapLinesCount()](#getWrapLinesCount--) | Gets wrap lines count for this paragraph(for pdf generation only) |
| [getZIndex()](#getZIndex--) | Gets an int value that indicates the Z-order of the graph. |
| [hashCode()](#hashCode--) |  |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [isInLineParagraph()](#isInLineParagraph--) | Gets a paragraph is inline. |
| [isInNewPage()](#isInNewPage--) | Gets a bool value that force this paragraph generates at new page. |
| [isKeptWithNext()](#isKeptWithNext--) | Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [isolateTextSegments(int startIndex, int length)](#isolateTextSegments-int-int-) | Gets  TextSegment (s) representing specified part of the  TextFragment  text. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) | Sets text position for text, represented with  TextFragment  object. |
| [setEndNote(Note value)](#setEndNote-com.aspose.pdf.Note-) | Sets the paragraph end note. |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | Gets or sets a bool value that indicates whether this paragraph will be at next column. |
| [setFootNote(Note value)](#setFootNote-com.aspose.pdf.Note-) | Sets the paragraph foot note. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | Sets a horizontal alignment of text fragment. |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets the fragment hyperlink |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | Sets a paragraph is inline. |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | Sets a boolean value that force this paragraph generates at new page. |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | Sets a outer margin for paragraph (for pdf generation) |
| [setMarkedContentProperties(String name, int id)](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) | Sets text position for text, represented with  TextFragment  object. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.pdf.Rectangle-) | Gets rectangle of the TextFragment |
| [setSegments(TextSegmentCollection value)](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Represent setSegments method |
| [setText(String value)](#setText-java.lang.String-) | Sets  string  text object that the  TextFragment  object represents. |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | Sets a vertical alignment of text fragment. |
| [setWrapLinesCount(int value)](#setWrapLinesCount-int-) | Sets wrap lines count for this paragraph(for pdf generation only) |
| [setZIndex(int value)](#setZIndex-int-) | Sets a int value that indicates the Z-order of the graph. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### cloneWithSegments() {#cloneWithSegments--}
```
public Object cloneWithSegments()
```


Clone the fragment with all segments.

**Returns:**
java.lang.Object - The cloned object
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the fragment.

**Returns:**
java.lang.Object - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBaselinePosition() {#getBaselinePosition--}
```
public Position getBaselinePosition()
```


Gets text position for text, represented with  TextFragment  object. The YIndent of the Position structure represents baseline coordinate of the text fragment.

**Returns:**
[Position](../../com.aspose.pdf/position) - Position value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEndNote() {#getEndNote--}
```
public Note getEndNote()
```


Gets the paragraph end note.(for pdf generation only)

**Returns:**
[Note](../../com.aspose.pdf/note) - Note value
### getFootNote() {#getFootNote--}
```
public Note getFootNote()
```


Gets the paragraph foot note.(for pdf generation only)

**Returns:**
[Note](../../com.aspose.pdf/note) - Note value
### getForm() {#getForm--}
```
public XForm getForm()
```


Gets form object that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to a form.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm value
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets a horizontal alignment of text fragment.

**Returns:**
int - HorizontalAlignment value
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


Gets the fragment hyperlink(for pdf generator).

**Returns:**
[Hyperlink](../../com.aspose.pdf/hyperlink) - the fragment hyperlink(for pdf generator).
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


Gets a outer margin for paragraph (for pdf generation)

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo value
### getPage() {#getPage--}
```
public Page getPage()
```


Gets page that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to any page.

**Returns:**
[Page](../../com.aspose.pdf/page) - Page object
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
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets rectangle of the TextFragment

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getReplaceOptions() {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```


Gets text replace options. The options define behavior when fragment text is replaced to more short/long.

**Returns:**
[TextReplaceOptions](../../com.aspose.pdf/textreplaceoptions) - TextReplaceOptions instance
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
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


Gets a vertical alignment of text fragment.

**Returns:**
int - int value
### getWrapLinesCount() {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```


Gets wrap lines count for this paragraph(for pdf generation only)

**Returns:**
int - int value
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


Gets an int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


Gets a paragraph is inline. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


Gets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Returns:**
boolean - boolean value
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


Sets text position for text, represented with  TextFragment  object. The YIndent of the Position structure represents baseline coordinate of the text fragment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Position](../../com.aspose.pdf/position) | Position value |

### setEndNote(Note value) {#setEndNote-com.aspose.pdf.Note-}
```
public void setEndNote(Note value)
```


Sets the paragraph end note.(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Note](../../com.aspose.pdf/note) | Note value |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFootNote(Note value) {#setFootNote-com.aspose.pdf.Note-}
```
public void setFootNote(Note value)
```


Sets the paragraph foot note.(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Note](../../com.aspose.pdf/note) | Note value |

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

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


Sets a paragraph is inline. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


Sets a boolean value that force this paragraph generates at new page. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


Sets a boolean value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


Sets a outer margin for paragraph (for pdf generation)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo object |

### setMarkedContentProperties(String name, int id) {#setMarkedContentProperties-java.lang.String-int-}
```
public void setMarkedContentProperties(String name, int id)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| id | int |  |

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

### setRectangle(Rectangle value) {#setRectangle-com.aspose.pdf.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Gets rectangle of the TextFragment

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle instance |

### setSegments(TextSegmentCollection value) {#setSegments-com.aspose.pdf.TextSegmentCollection-}
```
public void setSegments(TextSegmentCollection value)
```


Represent setSegments method

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) | TextSegmentCollection value |

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

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of text fragment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setWrapLinesCount(int value) {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```


Sets wrap lines count for this paragraph(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
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
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

