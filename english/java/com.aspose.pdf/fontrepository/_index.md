---
title: FontRepository
second_title: Aspose.PDF for Java API Reference
description: Performs font search.
type: docs
weight: 134
url: /java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object
```
public final class FontRepository
```

Performs font search. Searches in system installed fonts and standard Pdf fonts. Also provides functionality to open custom fonts.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  
  // Find font
  Font font = FontRepository.findFont("Arial");
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FontRepository()](#FontRepository--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSubstitutions()](#getSubstitutions--) | Gets font substitution strategies collection. |
| [getSources()](#getSources--) | Gets font sources collection. |
| [findFont(String fontName)](#findFont-java.lang.String-) | Searches and returns font with specified font name. |
| [findFont(String fontName, boolean ignoreCase)](#findFont-java.lang.String-boolean-) | Searches and returns font with specified font name ignoring or honoring case sensitivity. |
| [findFont(String fontFamilyName, int stl)](#findFont-java.lang.String-int-) | Searches and returns font with specified font name and font style. |
| [findFont(String fontFamilyName, int stl, boolean ignoreCase)](#findFont-java.lang.String-int-boolean-) | Searches and returns font with specified font name and font style ignoring or honoring case sensitivity. |
| [openFont(InputStream fontStream, int fontType)](#openFont-java.io.InputStream-int-) | Opens font with specified font stream. |
| [openFont(String fontFilePath)](#openFont-java.lang.String-) | Opens font with specified font file path. |
| [openFont(String fontFilePath, String metricsFilePath)](#openFont-java.lang.String-java.lang.String-) | Opens font with specified font file path and metrics file path. |
| [reloadFonts()](#reloadFonts--) | Reloads all fonts specified by property  Sources (\#getSources\#getSources) |
| [loadFonts()](#loadFonts--) | Loads system installed fonts and standard Pdf fonts. |
| [isReplaceNotFoundFonts()](#isReplaceNotFoundFonts--) | Is not found fonts will be replaced by standard font. |
| [setReplaceNotFoundFonts(boolean value)](#setReplaceNotFoundFonts-boolean-) | Set TRUE if need to replace not found fonts with the default font. |
| [clear()](#clear--) |  |
| [getLocalFontPaths()](#getLocalFontPaths--) | Copy of the list with actual font directories. |
| [isThreadStaticConfigEnabled()](#isThreadStaticConfigEnabled--) | Returns status of Font Sources storage configuration. |
| [setThreadStaticConfigEnabled(boolean isTheadLocal)](#setThreadStaticConfigEnabled-boolean-) | Option for setting Font Sources storage configuration. |
| [addLocalFontPath(String path)](#addLocalFontPath-java.lang.String-) | Add one more path to fonts. |
| [setLocalFontPaths(List<String> newFontPathsList)](#setLocalFontPaths-java.util.List-java.lang.String--) | Sets user list with font paths |
| [restoreLocalFontPath()](#restoreLocalFontPath--) | Restores list for standard font directories by default. |
| [addSystemFont(Font font)](#addSystemFont-com.aspose.pdf.Font-) | Add system font with specified font. |
### FontRepository() {#FontRepository--}
```
public FontRepository()
```


### getSubstitutions() {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```


Gets font substitution strategies collection.

**Returns:**
[FontSubstitutionCollection](../../com.aspose.pdf.text/fontsubstitutioncollection) - FontSubstitutionCollection object
### getSources() {#getSources--}
```
public static FontSourceCollection getSources()
```


Gets font sources collection.

**Returns:**
[FontSourceCollection](../../com.aspose.pdf.text/fontsourcecollection) - FontSourceCollection object
### findFont(String fontName) {#findFont-java.lang.String-}
```
public static Font findFont(String fontName)
```


Searches and returns font with specified font name.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  // Find font
  Font font = FontRepository.findFont("Arial");
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font name. |

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object.
### findFont(String fontName, boolean ignoreCase) {#findFont-java.lang.String-boolean-}
```
public static Font findFont(String fontName, boolean ignoreCase)
```


Searches and returns font with specified font name ignoring or honoring case sensitivity.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  // Find font
  Font font = FontRepository.findFont("Arial", FontStyles.Italic);
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurence
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Font name. |
| ignoreCase | boolean | case sensitivity |

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object.
### findFont(String fontFamilyName, int stl) {#findFont-java.lang.String-int-}
```
public static Font findFont(String fontFamilyName, int stl)
```


Searches and returns font with specified font name and font style.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  // Find font
  Font font = FontRepository.findFont("Arial", FontStyles.Italic);
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurence
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Font family name. |
| stl | int | Font style value. |

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object corresponding to search request parameters.
### findFont(String fontFamilyName, int stl, boolean ignoreCase) {#findFont-java.lang.String-int-boolean-}
```
public static Font findFont(String fontFamilyName, int stl, boolean ignoreCase)
```


Searches and returns font with specified font name and font style ignoring or honoring case sensitivity.

--------------------

```
The example demonstrates how to find font and replace the font of text of first page.
 
  // Find font
  
  Font font = FontRepository.findFont("Arial", FontStyles.Italic, true);
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurence
  absorber.getTextFragments().get_Item(1).getTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Font family name. |
| stl | int | Font style value. |
| ignoreCase | boolean | case sensitivity |

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object corresponding to search request parameters.
### openFont(InputStream fontStream, int fontType) {#openFont-java.io.InputStream-int-}
```
public static Font openFont(InputStream fontStream, int fontType)
```


Opens font with specified font stream.

--------------------

```
The example demonstrates how to open font and replace the font of text of first page.
  
  // Open font
  InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf"))
  {
      Font font = FontRepository.openFont(fontStream, , FontTypes.TTF);
  
      // Open document
      Document doc = new Document("D:\\Tests\\input.pdf");
      // Create TextFragmentAbsorber object to find all "hello world" text occurrences
      TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
      // Accept the absorber for first page
      doc.getPages().get_Item(1).accept(absorber);
  
      // Change font of the first text occurrence
      absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
      // Save document
      doc.save("D:\\Tests\\output.pdf"); 
  }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontStream | java.io.InputStream | Font stream. |
| fontType | int | Font type value. |

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object.
### openFont(String fontFilePath) {#openFont-java.lang.String-}
```
public static Font openFont(String fontFilePath)
```


Opens font with specified font file path.

--------------------

```
The example demonstrates how to open font and replace the font of text of first page.
 
  // Open font
  Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf");
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).getTextState().setFont ( font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | java.lang.String | Font file path. |

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object.
### openFont(String fontFilePath, String metricsFilePath) {#openFont-java.lang.String-java.lang.String-}
```
public static Font openFont(String fontFilePath, String metricsFilePath)
```


Opens font with specified font file path and metrics file path.

--------------------

```
The example demonstrates how to open Type1 font with metrics and replace the font of text of first page.
  
  // Open font
  Font font = FontRepository.openFont("courier.pfb", "courier.afm");
  
  // Open document
  Document doc = new Document("D:\\Tests\\input.pdf");
  // Create TextFragmentAbsorber object to find all "hello world" text occurrences
  TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
  
  // Accept the absorber for first page
  doc.getPages().get_Item(1).accept(absorber);
  
  // Change font of the first text occurrence
  absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font);
  
  // Save document
  doc.save("D:\\Tests\\output.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFilePath | java.lang.String | Font file path. |
| metricsFilePath | java.lang.String | Font metrics file patrh. |

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object.
### reloadFonts() {#reloadFonts--}
```
public static void reloadFonts()
```


Reloads all fonts specified by property  Sources (\#getSources\#getSources)

### loadFonts() {#loadFonts--}
```
public static void loadFonts()
```


Loads system installed fonts and standard Pdf fonts. This method was designed to speed up font loading process. By default fonts are loaded on first request for any font. Use of this method loads system and standard Pdf fonts immediately before any Pdf document was open.

### isReplaceNotFoundFonts() {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```


Is not found fonts will be replaced by standard font.

**Returns:**
boolean - boolean value
### setReplaceNotFoundFonts(boolean value) {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```


Set TRUE if need to replace not found fonts with the default font. The default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean |

### clear() {#clear--}
```
public static void clear()
```




### getLocalFontPaths() {#getLocalFontPaths--}
```
public static List<String> getLocalFontPaths()
```


Copy of the list with actual font directories.

**Returns:**
java.util.List<java.lang.String> - list of String
### isThreadStaticConfigEnabled() {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```


Returns status of Font Sources storage configuration.
If true, used ThreadStatic and every thread has own Font Sources.
If false, used global static configuration for all the threads.

--------------------

Default value is True.

**Returns:**
boolean - boolean value
### setThreadStaticConfigEnabled(boolean isTheadLocal) {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```


Option for setting Font Sources storage configuration.
If true, used ThreadStatic and every thread has own Font Sources.
If false, used global static configuration for all the threads.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isTheadLocal | boolean | boolean value |

### addLocalFontPath(String path) {#addLocalFontPath-java.lang.String-}
```
public static void addLocalFontPath(String path)
```


Add one more path to fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | String value |

### setLocalFontPaths(List<String> newFontPathsList) {#setLocalFontPaths-java.util.List-java.lang.String--}
```
public static void setLocalFontPaths(List<String> newFontPathsList)
```


Sets user list with font paths

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newFontPathsList | java.util.List<java.lang.String> |  List  object |

### restoreLocalFontPath() {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```


Restores list for standard font directories by default.

### addSystemFont(Font font) {#addSystemFont-com.aspose.pdf.Font-}
```
public static void addSystemFont(Font font)
```


Add system font with specified font.

--------------------

```
The example demonstrates how to add system font.

  InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf"))

  Font font = FontRepository.openFont(fontStream, FontTypes.TTF);

  FontRepository.addSystemFont(font);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| font | [Font](../../com.aspose.pdf/font) | Font instance |

