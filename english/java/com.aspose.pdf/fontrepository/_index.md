---
title: FontRepository
linktitle: FontRepository
second_title: Aspose.PDF for Java API Reference
description: <p> Performs font search. Searches in system installed fonts and standard Pdf fonts. Also provides functionality to open custom fonts. </p> <hr> <pre> The example demonstrates.
type: docs
weight: 1690
url: /java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Performs font search. Searches in system installed fonts and standard Pdf fonts. Also provides functionality to open custom fonts. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## Constructors

| Constructor | Description |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Methods

| Method | Description |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Add one more path to fonts. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Add system font with specified font. </p> <hr> <pre> The example demonstrates how to add system font. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Searches and returns font with specified font name. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Searches and returns font with specified font name ignoring or honoring case sensitivity. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Searches and returns font with specified font name and font style. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Searches and returns font with specified font name and font style ignoring or honoring case sensitivity. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Copy of the list with actual font directories. |
| [getSources](#getSources--) | Gets font sources collection. |
| [getSubstitutions](#getSubstitutions--) | Gets font substitution strategies collection. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | Is not found fonts will be replaced by standard font. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Returns status of Font Sources storage configuration. <br> If true, used ThreadStatic and every thread has own Font Sources. <br> If false, used global static configuration for all the threads. </p> <hr> Default value is True. |
| [loadFonts](#loadFonts--) | Loads system installed fonts and standard Pdf fonts. This method was designed to speed up font loading process. By default fonts are loaded on first request for any font. Use of this method loads system and standard Pdf fonts immediately before any Pdf document was open. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Opens font with specified font stream. </p> <hr> <pre> The example demonstrates how to open font and replace the font of text of first page. // Open font InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Opens font with specified font file path. </p> <hr> <pre> The example demonstrates how to open font and replace the font of text of first page. // Open font Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Opens font with specified font file path and metrics file path. </p> <hr> <pre> The example demonstrates how to open Type1 font with metrics and replace the font of text of first page. // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | Reloads all fonts specified by property {@code Sources}({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Restores list for standard font directories by default. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Sets user list with font paths |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Set TRUE if need to replace not found fonts with the default font. The default value is false. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Option for setting Font Sources storage configuration. If true, used ThreadStatic and every thread has own Font Sources. If false, used global static configuration for all the threads. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Add one more path to fonts.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Add system font with specified font. </p> <hr> <pre> The example demonstrates how to add system font. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Searches and returns font with specified font name. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Searches and returns font with specified font name ignoring or honoring case sensitivity. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Searches and returns font with specified font name and font style. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Searches and returns font with specified font name and font style ignoring or honoring case sensitivity. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Copy of the list with actual font directories.

**Returns:**
list of String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Gets font sources collection.

**Returns:**
FontSourceCollection object

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Gets font substitution strategies collection.

**Returns:**
FontSubstitutionCollection object

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

Is not found fonts will be replaced by standard font.

**Returns:**
boolean value

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Returns status of Font Sources storage configuration. <br> If true, used ThreadStatic and every thread has own Font Sources. <br> If false, used global static configuration for all the threads. </p> <hr> Default value is True.

**Returns:**
boolean value

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Loads system installed fonts and standard Pdf fonts. This method was designed to speed up font loading process. By default fonts are loaded on first request for any font. Use of this method loads system and standard Pdf fonts immediately before any Pdf document was open.

### openFont {#openFont-java.io.InputStream-int-}
<p> Opens font with specified font stream. </p> <hr> <pre> The example demonstrates how to open font and replace the font of text of first page. // Open font InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Opens font with specified font file path. </p> <hr> <pre> The example demonstrates how to open font and replace the font of text of first page. // Open font Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Opens font with specified font file path and metrics file path. </p> <hr> <pre> The example demonstrates how to open Type1 font with metrics and replace the font of text of first page. // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

Reloads all fonts specified by property {@code Sources}({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Restores list for standard font directories by default.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Sets user list with font paths

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Set TRUE if need to replace not found fonts with the default font. The default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Option for setting Font Sources storage configuration. If true, used ThreadStatic and every thread has own Font Sources. If false, used global static configuration for all the threads.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isTheadLocal |  | boolean value |
