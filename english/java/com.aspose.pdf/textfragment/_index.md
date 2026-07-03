---
title: TextFragment
linktitle: TextFragment
second_title: Aspose.PDF for Java API Reference
description: <p> Represents fragment of Pdf text. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document.
type: docs
weight: 5110
url: /java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> Represents fragment of Pdf text. </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text and it's font. // Open document Document doc = new Document("input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("output.pdf"); </pre> <hr> <pre> In a few words, {@code TextFragment} object contains list of {@code TextSegment} objects. In details: Text of pdf document in {@code com.aspose.pdf} is represented by two basic objects: {@code TextFragment} and {@code TextSegment} The differences between them is mostly context-dependent. Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments. The Aspose.Pdf text model basically establishes that {@code TextFragment} object provides single logic operation set over physical {@code TextSegment} objects set that represent user's query. In text search scenario, {@code TextFragment} is logical "hello world" text representation, and {@code TextSegment} object collection represents all physical segments that construct "hello world" text object. So, {@code TextFragment} is close to logical text representation. And {@code TextSegment} is close to physical text representation. Obviously each {@code TextSegment} object may have it's own font, coloring, positioning properties. {@code TextFragment} provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile {@code TextSegment} objects are accessible and users are able to operate with {@code TextSegment} objects independently. <p> Note that changing TextFragment properties may change inner {@code Segments} collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the {@code Segments} collection unchanged, please change inner segments individually. </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [TextFragment](#TextFragment--) | Initializes new instance of the {@code TextFragment} object. |
| [TextFragment](#TextFragment-java.lang.String-) | Initializes new instance of the {@code TextFragment} object. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | Initializes new instance of the {@code TextFragment} object. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | Initializes new instance of the {@code TextFragment} object. |

## Methods

| Method | Description |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clone the fragment with all segments. |
| [deepClone](#deepClone--) | Clone the fragment. |
| [getBaselinePosition](#getBaselinePosition--) | Gets text position for text, represented with {@code TextFragment} object. The YIndent of the Position structure represents baseline coordinate of the text fragment. |
| [getEndNote](#getEndNote--) | Gets the paragraph end note.(for pdf generation only) |
| [getFootNote](#getFootNote--) | Gets the paragraph foot note.(for pdf generation only) |
| [getForm](#getForm--) | Gets form object that contains the TextFragment The value can be null in case the TextFragment object doesn't belong to a form. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Gets a horizontal alignment of text fragment. |
| [getPage](#getPage--) | Gets page that contains the TextFragment The value can be null in case the TextFragment object doesn't belong to any page. |
| [getPosition](#getPosition--) | <p> Gets text position for text, represented with {@code TextFragment} object. </p> |
| [getRectangle](#getRectangle--) | Gets rectangle of the TextFragment |
| [getReplaceOptions](#getReplaceOptions--) | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [getSegments](#getSegments--) | <p> Gets text segments for current {@code TextFragment}. </p> |
| [getText](#getText--) | <p> Gets {@code string} text object that the {@code TextFragment} object represents. </p> |
| [getTextEditOptions](#getTextEditOptions--) | Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [getTextState](#getTextState--) | <p> Gets or sets text state for the text that {@code TextFragment} object represents. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | Gets a vertical alignment of text fragment. |
| [getWrapLinesCount](#getWrapLinesCount--) | Gets wrap lines count for this paragraph(for pdf generation only) |
| [isolateTextSegments](#isolateTextSegments-int-int-) | Gets {@code TextSegment}(s) representing specified part of the {@code TextFragment} text. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | Sets text position for text, represented with {@code TextFragment} object. The YIndent of the Position structure represents baseline coordinate of the text fragment. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | Sets the paragraph end note.(for pdf generation only) |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | Sets the paragraph foot note.(for pdf generation only) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Sets a horizontal alignment of text fragment. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Sets the fragment hyperlink |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> Sets text position for text, represented with {@code TextFragment} object. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Gets rectangle of the TextFragment |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | Represent setSegments method |
| [setText](#setText-java.lang.String-) | <p> Sets {@code string} text object that the {@code TextFragment} object represents. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Sets a vertical alignment of text fragment. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | Sets wrap lines count for this paragraph(for pdf generation only) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

Initializes new instance of the {@code TextFragment} object.

### TextFragment {#TextFragment-java.lang.String-}
Initializes new instance of the {@code TextFragment} object.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
Initializes new instance of the {@code TextFragment} object.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
Initializes new instance of the {@code TextFragment} object.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clone the fragment with all segments.

**Returns:**
The cloned object

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone the fragment.

**Returns:**
The cloned object

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

Gets text position for text, represented with {@code TextFragment} object. The YIndent of the Position structure represents baseline coordinate of the text fragment.

**Returns:**
Position value

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

Gets the paragraph end note.(for pdf generation only)

**Returns:**
Note value

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

Gets the paragraph foot note.(for pdf generation only)

**Returns:**
Note value

### getForm {#getForm--}
```
public XForm getForm()
```

Gets form object that contains the TextFragment The value can be null in case the TextFragment object doesn't belong to a form.

**Returns:**
XForm value

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Gets a horizontal alignment of text fragment.

**Returns:**
HorizontalAlignment value @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

Gets page that contains the TextFragment The value can be null in case the TextFragment object doesn't belong to any page.

**Returns:**
Page object

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> Gets text position for text, represented with {@code TextFragment} object. </p>

**Returns:**
Position value <hr> <pre> The example demonstrates how to view placement of a text, represented by {@code TextFragment} object. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets rectangle of the TextFragment

**Returns:**
Rectangle object

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

Gets text replace options. The options define behavior when fragment text is replaced to more short/long.

**Returns:**
TextReplaceOptions instance

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> Gets text segments for current {@code TextFragment}. </p>

**Returns:**
TextSegmentCollection value <hr> <pre> The example demonstrates how to navigate all {@code TextSegment} objects inside {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Navigate all text segments and out their text and placement info for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> In a few words, {@code TextSegment} objects are children of {@code TextFragment} object. Advanced users may access segments directly to perform more complex text edit scenarios. For details, please look at {@code TextFragment} object description. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> Gets {@code string} text object that the {@code TextFragment} object represents. </p>

**Returns:**
String value <hr> <pre> The example demonstrates how to search a text and replace first occurrence represented with {@code TextFragment} object . // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font.

**Returns:**
TextEditOptions instance

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> Gets or sets text state for the text that {@code TextFragment} object represents. </p>

**Returns:**
TextFragmentState object <hr> <pre> The example demonstrates how to change text color and font size of the text with {@code TextState} object. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> Provides a way to change following properties of the text: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Gets a vertical alignment of text fragment.

**Returns:**
int value @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

Gets wrap lines count for this paragraph(for pdf generation only)

**Returns:**
int value

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

Gets {@code TextSegment}(s) representing specified part of the {@code TextFragment} text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex |  | Position in text from which new {@code TextSegment}(s) will start. |
| length |  | Length of the text that will isolated into {@code TextSegment}(s). |

**Returns:**
{@code TextSegmentCollection} containing text segments represeting text substring starting at a specifing position and having a specified length.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
Sets text position for text, represented with {@code TextFragment} object. The YIndent of the Position structure represents baseline coordinate of the text fragment.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
Sets the paragraph end note.(for pdf generation only)

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
Sets the paragraph foot note.(for pdf generation only)

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Sets a horizontal alignment of text fragment.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Sets the fragment hyperlink

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> Sets text position for text, represented with {@code TextFragment} object. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Gets rectangle of the TextFragment

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
Represent setSegments method

### setText {#setText-java.lang.String-}
<p> Sets {@code string} text object that the {@code TextFragment} object represents. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Sets a vertical alignment of text fragment.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

Sets wrap lines count for this paragraph(for pdf generation only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
