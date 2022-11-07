---
title: Font
second_title: Aspose.PDF for Java API Reference
description: Represents font object.
type: docs
weight: 111
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

> ```
> The example demonstrates how to search text on first page and change font of a first search occurrence.
>   
>   // Open document
>   Document doc = new Document("D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
> 
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1).accept(absorber);
> 
>   // Create font and mark it to be embedded
>   Font font = FontRepository.findFont("Arial");
>   font.isEmbedded(true);
> 
>   // Change font of the first text occurrence
>   absorber.getTextFragments().get_Item(1).getTextState().setFont( font);
> 
> 
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Font(IFont font)](#Font-com.aspose.fonts.IFont-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Gets font name of the  Font  object. |
| [isEmbedded()](#isEmbedded--) | Gets or sets a value that indicates whether the font is embedded. |
| [isEmbedded(boolean value)](#isEmbedded-boolean-) |  |
| [isSubset()](#isSubset--) | Gets or sets a value that indicates whether the font is a subset. |
| [isSubset(boolean value)](#isSubset-boolean-) |  |
| [isAccessible()](#isAccessible--) | Gets indicating whether the font is present (installed) in the system. |
| [getFontOptions()](#getFontOptions--) | Useful properties to tune Font behavior |
| [getIPdfFont()](#getIPdfFont--) | Pdf font object. |
| [getIFont()](#getIFont--) | System font object. |
| [addFontPropertiesChanged(System.EventHandler eventHandler)](#addFontPropertiesChanged-com.aspose.ms.System.EventHandler-) |  |
| [removeFontPropertiesChanged(System.EventHandler eventHandler)](#removeFontPropertiesChanged-com.aspose.ms.System.EventHandler-) |  |
### Font(IFont font) {#Font-com.aspose.fonts.IFont-}
```
public Font(IFont font)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | com.aspose.fonts.IFont |  |

### getFontName() {#getFontName--}
```
public String getFontName()
```


Gets font name of the  Font  object.

--------------------

> ```
> The example demonstrates how to search text on first page and view font name of a first text occurrence.
>   
>   // Open document
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
> 
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1).accept(absorber);
> 
>   // View font name of first text occurrence
>   System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName());
> ```

**Returns:**
java.lang.String
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Gets or sets a value that indicates whether the font is embedded.

--------------------

> ```
> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font.
>  
>  // Create font and mark it to be embedded
>  Font font = FontRepository.FindFont("Arial");
>  font.isEmbedded ( true);
>  // open document
>  Document doc = new Document("D:\Tests\input.pdf");
>  // create TextFragmentAbsorber object to find all "hello world" text occurrences
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>  // accept the absorber for first page
>  doc.getPages().get_Item(1).accept(absorber);
>  // change font for the first text occurrence
>  absorber.getTextFragments(1).getTextState().setFont(font);
>  // save document
>  doc.save(@"D:\Tests\output.pdf");
> ```

**Returns:**
boolean
### isEmbedded(boolean value) {#isEmbedded-boolean-}
```
public void isEmbedded(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isSubset() {#isSubset--}
```
public boolean isSubset()
```


Gets or sets a value that indicates whether the font is a subset.

--------------------

> ```
> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset.
>   
>   // Open document
>   Document doc = new Document("D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
> 
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1).accept(absorber);
> 
>   // View font's IsSubset value of first text occurrence
>   if(absorber.TextFragments[1].TextState.Font.IsSubset)
>      System.out.println("the font is a subset");
> ```

**Returns:**
boolean
### isSubset(boolean value) {#isSubset-boolean-}
```
public void isSubset(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAccessible() {#isAccessible--}
```
public boolean isAccessible()
```


Gets indicating whether the font is present (installed) in the system.

--------------------

> ```
> The example demonstrates how to search text on first page and get the value that indicates whether the font is installed in the system.
>   
>   // Open document
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
> 
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1)].accept(absorber);
> 
>   // View font's IsSubset value of first text occurrence
>   if(absorber.getTextFragments().get_Item(1).getTextState().getFont().isAccessible())
>      System.out.println("the font is installed in the system");
> ```

--------------------

Some operations are not available with fonts that could not be found in the system.

**Returns:**
boolean
### getFontOptions() {#getFontOptions--}
```
public IFontOptions getFontOptions()
```


Useful properties to tune Font behavior

**Returns:**
[IFontOptions](../../com.aspose.pdf/ifontoptions) - IFontOptions object
### getIPdfFont() {#getIPdfFont--}
```
public IPdfFont getIPdfFont()
```


Pdf font object.

--------------------

For internal usage only

**Returns:**
[IPdfFont](../../com.aspose.pdf.engine.commondata.text.fonts/ipdffont)
### getIFont() {#getIFont--}
```
public IFont getIFont()
```


System font object.

--------------------

For internal usage only

**Returns:**
com.aspose.fonts.IFont
### addFontPropertiesChanged(System.EventHandler eventHandler) {#addFontPropertiesChanged-com.aspose.ms.System.EventHandler-}
```
public void addFontPropertiesChanged(System.EventHandler eventHandler)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventHandler | com.aspose.ms.System.EventHandler |  |

### removeFontPropertiesChanged(System.EventHandler eventHandler) {#removeFontPropertiesChanged-com.aspose.ms.System.EventHandler-}
```
public void removeFontPropertiesChanged(System.EventHandler eventHandler)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventHandler | com.aspose.ms.System.EventHandler |  |

