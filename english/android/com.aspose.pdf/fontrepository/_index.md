---
title: FontRepository
second_title: Aspose.PDF for Java API Reference
description: Performs font search.
type: docs
weight: 114
url: /java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object
```
public final class FontRepository
```

Performs font search. Searches in system installed fonts and standard Pdf fonts. Also provides functionality to open custom fonts.

--------------------

> ```
> The example demonstrates how to find font and replace the font of text of first page.
>    
>   // Find font
>   Font font = FontRepository.FindFont("Arial");
>   
>   // Open document
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1).accept(absorber);
>   
>   // Change font of the first text occurrence
>   absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
>   
>   // Save document
>   doc.save(@"D:\Tests\output.pdf");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [FontRepository()](#FontRepository--) |  |
## Methods

| Method | Description |
| --- | --- |
| [findFont(String fontName)](#findFont-java.lang.String-) | Searches and returns font with specified font name. |
| [findFont(String fontFamilyName, int style)](#findFont-java.lang.String-int-) | Searches and returns font with specified font name and font style. |
| [openFont(String fontFilePath)](#openFont-java.lang.String-) | Opens font with specified font file path. |
| [openFont(String fontFilePath, String metricsFilePath)](#openFont-java.lang.String-java.lang.String-) | Opens font with specified font file path and metrics file path. |
### FontRepository() {#FontRepository--}
```
public FontRepository()
```


### findFont(String fontName) {#findFont-java.lang.String-}
```
public static Font findFont(String fontName)
```


Searches and returns font with specified font name.

--------------------

> ```
> The example demonstrates how to find font and replace the font of text of first page.
>    
>   // Find font
>   Font font = FontRepository.findFont("Arial");
>   
>   // Open document
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1).accept(absorber);
>   
>   // Change font of the first text occurrence
>   absorber.getTextFragments().get_Item(1)].getTextState().setFont ( font);
>   
>   // Save document
>   doc.save(@"D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String |  |

**Returns:**
[Font](../../com.aspose.pdf/font)
### findFont(String fontFamilyName, int style) {#findFont-java.lang.String-int-}
```
public static Font findFont(String fontFamilyName, int style)
```


Searches and returns font with specified font name and font style.

--------------------

> ```
> The example demonstrates how to find font and replace the font of text of first page.
>    
>   // Find font
>   Font font = FontRepository.FindFont("Arial", FontStyle.Italic);
>   
>   // Open document
>   Document doc = new Document("D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1).accept(absorber);
>   
>   // Change font of the first text occurence
>   absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
>   
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| style | int |  |

**Returns:**
[Font](../../com.aspose.pdf/font)
### openFont(String fontFilePath) {#openFont-java.lang.String-}
```
public static Font openFont(String fontFilePath)
```


Opens font with specified font file path.

--------------------

> ```
> The example demonstrates how to open font and replace the font of text of first page.
>    
>   // Open font
>   Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");
>   
>   // Open document
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1).accept(absorber);
>   
>   // Change font of the first text occurrence
>   absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
>   
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | java.lang.String |  |

**Returns:**
[Font](../../com.aspose.pdf/font)
### openFont(String fontFilePath, String metricsFilePath) {#openFont-java.lang.String-java.lang.String-}
```
public static Font openFont(String fontFilePath, String metricsFilePath)
```


Opens font with specified font file path and metrics file path.

--------------------

> ```
> The example demonstrates how to open Type1 font with metrics and replace the font of text of first page.
>    
>   // Open font
>   Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");
>   
>   // Open document
>   Document doc = new Document(@"D:\Tests\input.pdf");
>   // Create TextFragmentAbsorber object to find all "hello world" text occurrences
>   TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
>   
>   // Accept the absorber for first page
>   doc.getPages().get_Item(1).accept(absorber);
>   
>   // Change font of the first text occurrence
>   absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font);
>   
>   // Save document
>   doc.save("D:\Tests\output.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | java.lang.String |  |
| metricsFilePath | java.lang.String |  |

**Returns:**
[Font](../../com.aspose.pdf/font)
