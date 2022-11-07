---
title: Font
second_title: Aspose.PDF for Java API Reference
description: Represents font object.
type: docs
weight: 12
url: /java/com.aspose.pdf.text/font/
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
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.Pages[1].Accept(absorber);
>   
>   // Create font and mark it to be embedded
>   Font font = FontRepository.FindFont("Arial");
>   font.IsEmbedded = true;
>   
>   // Change font of the first text occurrence
>   absorber.TextFragments[1].TextState.Font = font;
>   
>   
>   // Save document
>   doc.Save(@"D:\Tests\output.pdf");
> ```
## Methods

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | Gets font name of the  Font  object. |
| [isEmbedded()](#isEmbedded--) | Gets or sets a value that indicates whether the font is embedded. |
| [isEmbedded(boolean value)](#isEmbedded-boolean-) |  |
| [isSubset()](#isSubset--) | Gets or sets a value that indicates whether the font is a subset. |
| [isSubset(boolean value)](#isSubset-boolean-) |  |
| [isAccessible()](#isAccessible--) | Gets indicating whether the font is present (installed) in the system. |
| [getIFont()](#getIFont--) | System font object. |
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
>   doc.Pages[1].Accept(absorber);
>   
>   // View font name of first text occurrence
>   Console.Out.WriteLine(absorber.TextFragments[1].TextState.Font.FontName);
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
>  font.IsEmbedded = true;
>  // open document
>  Document doc = new Document(@"D:\Tests\input.pdf");
>  // create TextFragmentAbsorber object to find all "hello world" text occurrences
>  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>  // accept the absorber for first page
>  doc.Pages[1].Accept(absorber);
>  // change font for the first text occurrence
>  absorber.TextFragments[1].TextState.Font = font;
>  // save document
>  doc.Save(@"D:\Tests\output.pdf");
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
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.Pages[1].Accept(absorber);
>   
>   // View font's IsSubset value of first text occurrence
>   if(absorber.TextFragments[1].TextState.Font.IsSubset)
>      Console.Out.WriteLine("the font is a subset");
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
>   doc.Pages[1].Accept(absorber);
>   
>   // View font's IsSubset value of first text occurrence
>   if(absorber.TextFragments[1].TextState.Font.IsAccessible)
>      Console.Out.WriteLine("the font is installed in the system");
> ```

--------------------

Some operations are not available with fonts that could not be found in the system.

**Returns:**
boolean
### getIFont() {#getIFont--}
```
public IFont getIFont()
```


System font object.

--------------------

For internal usage only

**Returns:**
com.aspose.fonts.IFont
