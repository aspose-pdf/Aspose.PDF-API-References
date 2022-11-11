---
title: SystemFontsSubstitution
second_title: Aspose.PDF for Java API Reference
description: Represents a class for font substitution strategy that substitutes fonts with system fonts.
type: docs
weight: 19
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefaultFont()](#getDefaultFont--) | Gets or sets default substitution font. |
| [getFontCategories()](#getFontCategories--) | Gets or sets substitution font categories that should be substituted with system fonts. |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | Returns unicode substitution |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | Get Substitution Font Definition |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDefaultFont(Font value)](#setDefaultFont-com.aspose.pdf.Font-) | Gets or sets default substitution font. |
| [setFontCategories(int value)](#setFontCategories-int-) | Gets or sets substitution font categories that should be substituted with system fonts. |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | Set Substitution Font Definition |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SystemFontsSubstitution(int fontCategories) {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```


Initializes a new instance of  SystemFontsSubstitution  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontCategories | int | Target font categories to substitute with system fonts |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFont() {#getDefaultFont--}
```
public Font getDefaultFont()
```


Gets or sets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ( FontCategories ).

**Returns:**
[Font](../../com.aspose.pdf/font) - Font object
### getFontCategories() {#getFontCategories--}
```
public int getFontCategories()
```


Gets or sets substitution font categories that should be substituted with system fonts.

**Returns:**
int - SubstitutionFontCategories element
### getSubstitutedUnicode(char unicode) {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```


Returns unicode substitution

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unicode | char | char value |

**Returns:**
char - char value
### getSubstitutionFontDefinition() {#getSubstitutionFontDefinition--}
```
public FontDefinition getSubstitutionFontDefinition()
```


Get Substitution Font Definition

**Returns:**
com.aspose.font.FontDefinition - FontDefinition object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDefaultFont(Font value) {#setDefaultFont-com.aspose.pdf.Font-}
```
public void setDefaultFont(Font value)
```


Gets or sets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ( FontCategories ).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Font](../../com.aspose.pdf/font) | Font object |

### setFontCategories(int value) {#setFontCategories-int-}
```
public void setFontCategories(int value)
```


Gets or sets substitution font categories that should be substituted with system fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | SubstitutionFontCategories element |

### setSubstitutionFontDefinition(FontDefinition value) {#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-}
```
public void setSubstitutionFontDefinition(FontDefinition value)
```


Set Substitution Font Definition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.font.FontDefinition | FontDefinition object |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

