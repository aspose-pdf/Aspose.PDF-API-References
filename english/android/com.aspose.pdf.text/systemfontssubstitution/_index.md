---
title: SystemFontsSubstitution
second_title: Aspose.PDF for Java API Reference
description: Represents a class for font substitution strategy that substitutes fonts with system fonts.
type: docs
weight: 20
url: /java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public final class SystemFontsSubstitution extends FontSubstitution
```

Represents a class for font substitution strategy that substitutes fonts with system fonts.
## Constructors

| Constructor | Description |
| --- | --- |
| [SystemFontsSubstitution(int fontCategories)](#SystemFontsSubstitution-int-) | Initializes a new instance of  SystemFontsSubstitution  class. |
## Methods

| Method | Description |
| --- | --- |
| [getFontCategories()](#getFontCategories--) | Gets or sets substitution font categories that should be substituted with system fonts. |
| [setFontCategories(int value)](#setFontCategories-int-) |  |
| [getDefaultFont()](#getDefaultFont--) | Gets or sets default substitution font. |
| [setDefaultFont(Font value)](#setDefaultFont-com.aspose.pdf.Font-) |  |
### SystemFontsSubstitution(int fontCategories) {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```


Initializes a new instance of  SystemFontsSubstitution  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontCategories | int | Target font categories to substitute with system fonts |

### getFontCategories() {#getFontCategories--}
```
public int getFontCategories()
```


Gets or sets substitution font categories that should be substituted with system fonts.

**Returns:**
int
### setFontCategories(int value) {#setFontCategories-int-}
```
public void setFontCategories(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultFont() {#getDefaultFont--}
```
public Font getDefaultFont()
```


Gets or sets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ( FontCategories ).

**Returns:**
[Font](../../com.aspose.pdf/font)
### setDefaultFont(Font value) {#setDefaultFont-com.aspose.pdf.Font-}
```
public void setDefaultFont(Font value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) |  |

