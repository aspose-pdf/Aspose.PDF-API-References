---
title: Font
second_title: Aspose.PDF for Java API Reference
description: Represents font object.
type: docs
weight: 130
url: /java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public final class Font implements Cloneable
```

Represents font object.

--------------------

```
The example demonstrates how to search text on first page and change font of a first search occurrence.
 
  
  // Open document
  Document doc = new Document("input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Create font and mark it to be embedded
  Font font = FontRepository.findFont("Arial");
  font.isEmbedded(true);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFont( font);
  
  
  // Save document
  doc.save("output.pdf");
```
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | The font's type Name |
| [getFontName()](#getFontName--) | Gets font name of the  Font  object. |
| [getActualFontName()](#getActualFontName--) | Gets actual font name of the  Font  object if it is initialized. |
| [getDecodedFontName()](#getDecodedFontName--) | Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. |
| [getBaseFont()](#getBaseFont--) | Gets BaseFont value of PDF font object. |
| [getLastFontEmbeddingError()](#getLastFontEmbeddingError--) | An objective of this method - to return description of error if an attempt to embed font was failed. |
| [isEmbedded()](#isEmbedded--) | Gets a value that indicates whether the font is embedded. |
| [setEmbedded(boolean value)](#setEmbedded-boolean-) | Sets a value that indicates whether the font is embedded. |
| [isSubset()](#isSubset--) | Gets a value that indicates whether the font is a subset. |
| [setSubset(boolean value)](#setSubset-boolean-) | Sets a value that indicates whether the font is a subset. |
| [isAccessible()](#isAccessible--) | Gets indicating whether the font is present (installed) in the system. |
| [getFontOptions()](#getFontOptions--) | Useful properties to tune Font behavior |
| [getIPdfFont()](#getIPdfFont--) | Pdf font object. |
| [getIFont()](#getIFont--) | System font object. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the font into the stream. |
| [measureString(String str, float fontSize)](#measureString-java.lang.String-float-) | Measures the string. |
| [doesFontContainAllCharacters(String value)](#doesFontContainAllCharacters-java.lang.String-) | Determines if the font contains specified chars |
### getType() {#getType--}
```
public String getType()
```


The font's type Name

**Returns:**
java.lang.String - String object
### getFontName() {#getFontName--}
```
public String getFontName()
```


Gets font name of the  Font  object.

**Returns:**
java.lang.String - String value

--------------------

```
The example demonstrates how to search text on first page and view font name of a first text occurrence.
 
  // Open document
  Document doc = new Document(@"D:\Tests\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // View font name of first text occurrence
  System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName());
```
### getActualFontName() {#getActualFontName--}
```
public String getActualFontName()
```


Gets actual font name of the  Font  object if it is initialized. Even when the font is substituted or has internal name for pdf. Or empty string if the font is not initialized.

**Returns:**
java.lang.String - String value

--------------------

```
The example demonstrates how to search text on first page and view actual font name of a first text occurrence.

  // Open document
  Document doc = new Document(@"D:\Tests\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);

  // View actual font name of first text occurrence
  System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName());
```
### getDecodedFontName() {#getDecodedFontName--}
```
public String getDecodedFontName()
```


Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. This name is value of PDF font property "BaseFont" and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in non-readable form. To get readable form it's necessary to decode font's name by rules specifical for this font. This property returns decoded font name, so use it for cases when you meet with a non-readable  FontName . If property  FontName  has readable form this property will be the same as  FontName , so you can use this property for any cases when you need to get font name in a readable form.

**Returns:**
java.lang.String - String value
### getBaseFont() {#getBaseFont--}
```
public final String getBaseFont()
```


Gets BaseFont value of PDF font object. Also known as PostScript name of the font.

**Returns:**
java.lang.String - String value
### getLastFontEmbeddingError() {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```


An objective of this method - to return description of error if an attempt to embed font was failed. If there are no error cases it returns empty string.

**Returns:**
java.lang.String - Error description
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Gets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded

--------------------

```
The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font.
 
	      // Create font and mark it to be embedded
	      com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial");
	      font.isEmbedded ( true);
	      // open document
	      com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\Tests\\input.pdf");
	      // create TextFragmentAbsorber object to find all "hello world" text occurrences
	      com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world");
	      // accept the absorber for first page
	      doc.getPages().get_Item(1).accept(absorber);
	      // change font for the first text occurrence
	      absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
	      // save document
	      doc.save("D:\\Tests\\output.pdf");
```

**Returns:**
boolean - boolean value
### setEmbedded(boolean value) {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```


Sets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isSubset() {#isSubset--}
```
public boolean isSubset()
```


Gets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded

--------------------

```
The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset.
  
	       // Open document
	       Document doc = new Document("D:\\Tests\\input.pdf");
	       // Create TextFragmentAbsorber object to find all "hello world" text occurrences
	       TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
	       
	       // Accept the absorber for first page
	       doc.getPages().get_Item(1).accept(absorber);
	       
	       // View font's IsSubset value of first text occurrence
	       if(absorber.TextFragments[1].TextState.Font.IsSubset)
	          System.out.println("the font is a subset");
```

**Returns:**
boolean - boolean value
### setSubset(boolean value) {#setSubset-boolean-}
```
public void setSubset(boolean value)
```


Sets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isAccessible() {#isAccessible--}
```
public boolean isAccessible()
```


Gets indicating whether the font is present (installed) in the system.

**Returns:**
boolean - boolean value

--------------------

```
The example demonstrates how to search text on first page and get the value that indicates whether the font is installed in the system.
 
 // Open document
 Document doc = new Document("D:\\Tests\\input.pdf");
 // Create TextFragmentAbsorber object to find all "hello world" text occurrences
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 
 // Accept the absorber for first page
 doc.getPages().get_Item(1).accept(absorber);
 
 // View font's IsSubset value of first text occurrence
 if (absorber.getTextFragments().get_Item(1).getTextState().getFont()
 		.isAccessible())
 	System.out.println("the font is installed in the system");
```

--------------------

Some operations are not available with fonts that could not be found in the system.
### getFontOptions() {#getFontOptions--}
```
public IFontOptions getFontOptions()
```


Useful properties to tune Font behavior

**Returns:**
[IFontOptions](../../com.aspose.pdf/ifontoptions) - IFontOptions object
### getIFont() {#getIFont--}
```
public IFont getIFont()
```


System font object.

--------------------

For internal usage only

**Returns:**
com.aspose.font.IFont - IFont object
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves the font into the stream. Note that the font is saved to intermediate TTF format intended to be used in a converted copy of the original document only. The font file is not intended to be used outside the original document context.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream to save the font. |

### measureString(String str, float fontSize) {#measureString-java.lang.String-float-}
```
public double measureString(String str, float fontSize)
```


Measures the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | The string. |
| fontSize | float | Font size. |

**Returns:**
double - Width of the string represented with this font and the specified size.
### doesFontContainAllCharacters(String value) {#doesFontContainAllCharacters-java.lang.String-}
```
public boolean doesFontContainAllCharacters(String value)
```


Determines if the font contains specified chars

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

**Returns:**
boolean - true if all the characters from text are present in the current font.
