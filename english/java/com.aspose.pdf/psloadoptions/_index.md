---
title: PsLoadOptions
linktitle: PsLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Represents options for loading/importing of .mht-file into pdf document.
type: docs
weight: 4060
url: /java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

Represents options for loading/importing of .mht-file into pdf document.

## Constructors

| Constructor | Description |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Creates load options for converting PostScript into pdf document with empty base path. |

## Methods

| Method | Description |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Gets fonts folders paths. The folders with additional fonts for conversion. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | Specifies whether to save non-TrueType fonts to TTF. It significantly decreases the volume of the resulting document in PS to PDF conversion and increases the speed of conversion of PS files with a large quantity of text in non-TrueType fonts to any output format. However, there is small vertical shift of text when converting PostSctipt file to image. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | Specifies whether to save non-TrueType fonts to TTF. It significantly decreases the volume of the resulting document in PS to PDF conversion and increases the speed of conversion of PS files with a large quantity of text in non-TrueType fonts to any output format. However, there is small vertical shift of text when converting PostSctipt file to image. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Sets fonts folders paths. The folders with additional fonts for conversion. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Creates load options for converting PostScript into pdf document with empty base path.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Gets fonts folders paths. The folders with additional fonts for conversion.

**Returns:**
array of String values

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

Specifies whether to save non-TrueType fonts to TTF. It significantly decreases the volume of the resulting document in PS to PDF conversion and increases the speed of conversion of PS files with a large quantity of text in non-TrueType fonts to any output format. However, there is small vertical shift of text when converting PostSctipt file to image.

**Returns:**
boolean value

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

Specifies whether to save non-TrueType fonts to TTF. It significantly decreases the volume of the resulting document in PS to PDF conversion and increases the speed of conversion of PS files with a large quantity of text in non-TrueType fonts to any output format. However, there is small vertical shift of text when converting PostSctipt file to image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Sets fonts folders paths. The folders with additional fonts for conversion.
