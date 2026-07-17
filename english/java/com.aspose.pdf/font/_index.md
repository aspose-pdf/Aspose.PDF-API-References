---
title: Font
linktitle: Font
second_title: Aspose.PDF for Java API Reference
description: <p> Represents font object. </p> <hr> <pre> The example demonstrates how to search text on first page and change font of a first search occurrence. // Open document Document doc.
type: docs
weight: 1650
url: /java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> Represents font object. </p> <hr> <pre> The example demonstrates how to search text on first page and change font of a first search occurrence. // Open document Document doc = new Document("input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Methods

| Method | Description |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Determines if the font contains specified chars |
| [getActualFontName](#getActualFontName--) | <p> Gets actual font name of the {@code Font} object if it is initialized. Even when the font is substituted or has internal name for pdf. Or empty string if the font is not initialized. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Measures the max Ascent Point. |
| [getBaseFont](#getBaseFont--) | Gets BaseFont value of PDF font object. Also known as PostScript name of the font. |
| [getDecodedFontName](#getDecodedFontName--) | Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. This name is value of PDF font property "BaseFont" and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in non-readable form. To get readable form it's necessary to decode font's name by rules specifical for this font. This property returns decoded font name, so use it for cases when you meet with a non-readable {@code FontName}. If property {@code FontName} has readable form this property will be the same as {@code FontName}, so you can use this property for any cases when you need to get font name in a readable form. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Measures the max Descent Point. |
| [getFontName](#getFontName--) | <p> Gets font name of the {@code Font} object. </p> |
| [getFontOptions](#getFontOptions--) | Useful properties to tune Font behavior |
| [getIFont](#getIFont--) | <p> System font object. </p> <hr> <p> For internal usage only </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Pdf font object. </p> <hr> <p> For internal usage only </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | An objective of this method - to return description of error if an attempt to embed font was failed. If there are no error cases it returns empty string. |
| [getType](#getType--) | The font's type Name |
| [isAccessible](#isAccessible--) | <p> Gets indicating whether the font is present (installed) in the system. </p> |
| [isEmbedded](#isEmbedded--) | <p> Gets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Gets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Measures the string. |
| [save](#save-java.io.OutputStream-) | Saves the font into the stream. Note that the font is saved to intermediate TTF format intended to be used in a converted copy of the original document only. The font file is not intended to be used outside the original document context. |
| [setEmbedded](#setEmbedded-boolean-) | Sets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded |
| [setSubset](#setSubset-boolean-) | Sets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Determines if the font contains specified chars

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> Gets actual font name of the {@code Font} object if it is initialized. Even when the font is substituted or has internal name for pdf. Or empty string if the font is not initialized. </p>

**Returns:**
String value <hr> <pre> The example demonstrates how to search text on first page and view actual font name of a first text occurrence. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Measures the max Ascent Point.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

Gets BaseFont value of PDF font object. Also known as PostScript name of the font.

**Returns:**
String value

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. This name is value of PDF font property "BaseFont" and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in non-readable form. To get readable form it's necessary to decode font's name by rules specifical for this font. This property returns decoded font name, so use it for cases when you meet with a non-readable {@code FontName}. If property {@code FontName} has readable form this property will be the same as {@code FontName}, so you can use this property for any cases when you need to get font name in a readable form.

**Returns:**
String value

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Measures the max Descent Point.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> Gets font name of the {@code Font} object. </p>

**Returns:**
String value <hr> <pre> The example demonstrates how to search text on first page and view font name of a first text occurrence. // Open document Document doc = new Document(@"D:\Tests\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Useful properties to tune Font behavior

**Returns:**
IFontOptions object

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> System font object. </p> <hr> <p> For internal usage only </p>

**Returns:**
IFont object

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Pdf font object. </p> <hr> <p> For internal usage only </p>

**Returns:**
IPdfFont object

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

An objective of this method - to return description of error if an attempt to embed font was failed. If there are no error cases it returns empty string.

**Returns:**
Error description

### getType {#getType--}
```
public String getType()
```

The font's type Name

**Returns:**
String object

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Gets indicating whether the font is present (installed) in the system. </p>

**Returns:**
boolean value <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is installed in the system. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println("the font is installed in the system"); </pre> <hr> <p> Some operations are not available with fonts that could not be found in the system. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Gets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\Tests\\output.pdf"); </pre>

**Returns:**
boolean value @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Gets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre>

**Returns:**
boolean value @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Measures the string.

### save {#save-java.io.OutputStream-}
Saves the font into the stream. Note that the font is saved to intermediate TTF format intended to be used in a converted copy of the original document only. The font file is not intended to be used outside the original document context.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Sets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Sets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
