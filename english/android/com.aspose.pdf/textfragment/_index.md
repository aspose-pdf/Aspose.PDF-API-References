---
title: TextFragment
second_title: Aspose.PDF for Java API Reference
description: Represents fragment of Pdf text.
type: docs
weight: 295
url: /java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public class TextFragment extends BaseParagraph
```

Represents fragment of Pdf text.

--------------------

> ```
> The example demonstrates how to find text on the first PDF document page and replace the text and it's font.
>   
>   // Open document
>   Document doc = new Document("D:\Tests\input.pdf");
> 
>   // Find font that will be used to change document text font
>   Font font = FontRepository.findFont("Arial");
> 
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
> 
>   // Accept the absorber for first page
>   doc.getPages().get(1).accept(absorber);
> 
>   // Change text and font of the first text occurrence
>   absorber.getTextFragments().get_Item(1).setText ( "hi world");
>   absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
> 
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```

--------------------

In a few words,  TextFragment  object contains list of  TextSegment  objects. In details: Text of pdf document in  Aspose.Pdf  is represented by two basic objects:  TextFragment  and  TextSegment  The differences between them is mostly context-dependent. Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc.

```
Document doc = new Document(docFile);
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  doc.getPages().get(1).accept(absorber);
```

Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments. The Aspose.Pdf text model basically establishes that  TextFragment  object provides single logic operation set over physical  TextSegment  objects set that represent user's query. In text search scenario,  TextFragment  is logical "hello world" text representation, and  TextSegment  object collection represents all physical segments that construct "hello world" text object. So,  TextFragment  is close to logical text representation. And  TextSegment  is close to physical text representation. Obviously each  TextSegment  object may have it's own font, coloring, positioning properties.  TextFragment  provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile  TextSegment  objects are accessible and users are able to operate with  TextSegment  objects independently. Note that changing TextFragment properties may change inner  Segments  collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the  Segments  collection unchanged, please change inner segments individually.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragment()](#TextFragment--) | Initializes new instance of the  TextFragment  object. |
| [TextFragment(String text)](#TextFragment-java.lang.String-) | Creates  TextFragment  object with single  TextSegment  object inside. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gets or sets  string  text object that the  TextFragment  object represents. |
| [setText(String value)](#setText-java.lang.String-) |  |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) |  |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | Gets or sets a horizontal alignment of text fragment. |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) |  |
| [getTextState()](#getTextState--) | Gets or sets text state for the text that  TextFragment  object represents. |
| [getSegments()](#getSegments--) | Gets text segments for current  TextFragment . |
| [setSegments(TextSegmentCollection value)](#setSegments-com.aspose.pdf.TextSegmentCollection-) |  |
| [getPosition()](#getPosition--) | Gets text position for text, represented with  TextFragment  object. |
| [setPosition(Position value)](#setPosition-com.aspose.pdf.Position-) |  |
| [getBaselinePosition()](#getBaselinePosition--) | Gets text position for text, represented with  TextFragment  object. |
| [setBaselinePosition(Position value)](#setBaselinePosition-com.aspose.pdf.Position-) |  |
| [getRectangle()](#getRectangle--) | returns rectangle of the TextFragment |
| [getPage()](#getPage--) | Gets page that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to any page. |
| [getForm()](#getForm--) | Gets form object that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to a form. |
| [getPlacementInfo()](#getPlacementInfo--) | Gets placement info |
| [setPlacementInfo(NewParagraphPlacementInfo value)](#setPlacementInfo-com.aspose.pdf.NewParagraphPlacementInfo-) | Sets placement info |
| [deepClone()](#deepClone--) | Clone the fragment. |
| [getWrapLinesCount()](#getWrapLinesCount--) | Gets wrap lines count for this paragraph(for pdf generation only) |
| [setWrapLinesCount(int value)](#setWrapLinesCount-int-) | Sets wrap lines count for this paragraph(for pdf generation only) |
### TextFragment() {#TextFragment--}
```
public TextFragment()
```


Initializes new instance of the  TextFragment  object.

### TextFragment(String text) {#TextFragment-java.lang.String-}
```
public TextFragment(String text)
```


Creates  TextFragment  object with single  TextSegment  object inside. Specifies text string inside the segment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text fragment's text. |

### getText() {#getText--}
```
public String getText()
```


Gets or sets  string  text object that the  TextFragment  object represents.

--------------------

> ```
> The example demonstrates how to search a text and replace first occurrence represented with ```
> TextFragment
> ``` object .
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
>   // Change font of the first text occurrence
>   absorber.getTextFragments().get_Item(1).setText ( "hi world");
> 
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```

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

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


Sets a vertical alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


Gets or sets a horizontal alignment of text fragment.

**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


Sets a horizontal alignment of paragraph

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTextState() {#getTextState--}
```
public TextFragmentState getTextState()
```


Gets or sets text state for the text that  TextFragment  object represents.

--------------------

> ```
> The example demonstrates how to change text color and font size of the text with ```
> TextState
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
>   // Change foreground color of the first text occurrence
>   absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED);
> 
>   // Change font size of the first text occurrence
>   absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15);
> 
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```

--------------------

Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor

**Returns:**
[TextFragmentState](../../com.aspose.pdf/textfragmentstate)
### getSegments() {#getSegments--}
```
public TextSegmentCollection getSegments()
```


Gets text segments for current  TextFragment .

--------------------

> ```
> The example demonstrates how to navigate all ```
> TextSegment
> ``` objects inside ```
> TextFragment
> ```.
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
>   // Navigate all text segments and out their text and placement info
>   for (TextSegment segment : absorber.getTextFragments().get_Item(1).getSegments())
>   {
>       System.out.println(string.Format("segment text: {0}", segment.Text));
>       System.out.println(string.Format("segment X indent: {0}", segment.Position.XIndent));
>       System.out.println(string.Format("segment Y indent: {0}", segment.Position.YIndent));
>   }
> ```

--------------------

In a few words,  TextSegment  objects are children of  TextFragment  object. Advanced users may access segments directly to perform more complex text edit scenarios. For details, please look at  TextFragment  object description.

**Returns:**
[TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection)
### setSegments(TextSegmentCollection value) {#setSegments-com.aspose.pdf.TextSegmentCollection-}
```
public void setSegments(TextSegmentCollection value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextSegmentCollection](../../com.aspose.pdf/textsegmentcollection) |  |

### getPosition() {#getPosition--}
```
public Position getPosition()
```


Gets text position for text, represented with  TextFragment  object.

--------------------

> ```
> The example demonstrates how to view placement of a text, represented by ```
> TextFragment
> ``` object.
>   
>    // Open document
>    Document doc = new Document("D:\Tests\input.pdf");
> 
>    // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
> 
>    // Accept the absorber for first page
>    doc.getPages().get(1).accept(absorber);
> 
>    // View text and placement info of first text occurrence
>    TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1);
> 
>    System.out.println(string.Format("fragment text: {0}", firstOccurrence.Text));
>    System.out.println(string.Format("fragment X indent: {0}", firstOccurrence.Position.XIndent));
>    System.out.println(string.Format("fragment Y indent: {0}", firstOccurrence.Position.YIndent));
> ```

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

### getBaselinePosition() {#getBaselinePosition--}
```
public Position getBaselinePosition()
```


Gets text position for text, represented with  TextFragment  object. The YIndent of the Position structure represents baseline coordinate of the text fragment.

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

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


returns rectangle of the TextFragment

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### getPage() {#getPage--}
```
public Page getPage()
```


Gets page that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to any page.

**Returns:**
[Page](../../com.aspose.pdf/page) - 
### getForm() {#getForm--}
```
public XForm getForm()
```


Gets form object that contains the TextFragment
The value can be null in case the TextFragment object doesn't belong to a form.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - 
### getPlacementInfo() {#getPlacementInfo--}
```
public NewParagraphPlacementInfo getPlacementInfo()
```


Gets placement info

**Returns:**
[NewParagraphPlacementInfo](../../com.aspose.pdf/newparagraphplacementinfo) - 
### setPlacementInfo(NewParagraphPlacementInfo value) {#setPlacementInfo-com.aspose.pdf.NewParagraphPlacementInfo-}
```
public void setPlacementInfo(NewParagraphPlacementInfo value)
```


Sets placement info

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [NewParagraphPlacementInfo](../../com.aspose.pdf/newparagraphplacementinfo) |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the fragment.

**Returns:**
java.lang.Object - The cloned object
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

