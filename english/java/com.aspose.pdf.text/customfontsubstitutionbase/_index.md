---
title: CustomFontSubstitutionBase
second_title: Aspose.PDF for Java API Reference
description: Represents a base class for custom font substitution strategy.
type: docs
weight: 10
url: /java/com.aspose.pdf.text/customfontsubstitutionbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.text.FontSubstitution](../../com.aspose.pdf.text/fontsubstitution)
```
public class CustomFontSubstitutionBase extends FontSubstitution
```

Represents a base class for custom font substitution strategy.
## Constructors

| Constructor | Description |
| --- | --- |
| [CustomFontSubstitutionBase()](#CustomFontSubstitutionBase--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | Returns unicode substitution |
| [getSubstitutionFontDefinition()](#getSubstitutionFontDefinition--) | Get Substitution Font Definition |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSubstitutionFontDefinition(FontDefinition value)](#setSubstitutionFontDefinition-com.aspose.font.FontDefinition-) | Set Substitution Font Definition |
| [toString()](#toString--) |  |
| [trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)](#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.Font---) | Substitutes original font with another font. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomFontSubstitutionBase() {#CustomFontSubstitutionBase--}
```
public CustomFontSubstitutionBase()
```


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
### trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont) {#trySubstitute-com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification-com.aspose.pdf.Font---}
```
public boolean trySubstitute(CustomFontSubstitutionBase.OriginalFontSpecification originalFontSpecification, Font[] substitutionFont)
```


Substitutes original font with another font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalFontSpecification | [OriginalFontSpecification](../../com.aspose.pdf.text/originalfontspecification) | Original font specification. |
| substitutionFont | [Font\[\]](../../com.aspose.pdf/font) | Substitution font.

--------------------

The class CustomFontSubstitutionBase should be inherited to implement custom font substitution logic. TrySubstitute method should be overridden properly: Must return true in case substitution is required. substitutionFont must be set to valid Font object. Must return false in case no substitution is required. substitutionFont may be set to null. |

**Returns:**
boolean - True in case substitution was successful.
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

