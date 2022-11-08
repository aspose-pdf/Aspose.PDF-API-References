---
title: SimpleFontSubstitution
second_title: Aspose.PDF for Java API Reference
description: Represents a class for simple font substitution strategy.
type: docs
weight: 17
url: /java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public final class SimpleFontSubstitution extends FontSubstitution
```

Represents a class for simple font substitution strategy.
## Constructors

| Constructor | Description |
| --- | --- |
| [SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption)](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Initializes a new instance of  SimpleFontSubstitution  class. |
| [SimpleFontSubstitution(String originalFontName, String substitutionFontName)](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Initializes a new instance of  SimpleFontSubstitution  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOriginalFontName()](#getOriginalFontName--) | Gets original font name that should be substituted with  SubstitutionFontName  |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | Returns unicode substitution |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | Get Substitution Font Definition |
| [getSubstitutionFontName()](#getSubstitutionFontName--) | Gets font name that should substitute the  OriginalFontName  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | Set Substitution Font Definition |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption) {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
```
public SimpleFontSubstitution(String originalFontName, String substitutionFontName, boolean isForcedBySaveOption)
```


Initializes a new instance of  SimpleFontSubstitution  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalFontName | java.lang.String | Original font name. |
| substitutionFontName | java.lang.String | Substitution font name. |
| isForcedBySaveOption | boolean | Substitution forced by DefaultFontName save option. |

### SimpleFontSubstitution(String originalFontName, String substitutionFontName) {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
```
public SimpleFontSubstitution(String originalFontName, String substitutionFontName)
```


Initializes a new instance of  SimpleFontSubstitution  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalFontName | java.lang.String | Original font name. |
| substitutionFontName | java.lang.String | Substitution font name. |

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
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Gets original font name that should be substituted with  SubstitutionFontName 

**Returns:**
java.lang.String - String value
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
### getSubstitutionFontName() {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```


Gets font name that should substitute the  OriginalFontName 

**Returns:**
java.lang.String - String value
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

