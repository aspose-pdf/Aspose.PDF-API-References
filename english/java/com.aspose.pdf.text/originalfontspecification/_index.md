---
title: CustomFontSubstitutionBase.OriginalFontSpecification
second_title: Aspose.PDF for Java API Reference
description: Represents original font specification.
type: docs
weight: 10
url: /java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object
```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification
```

Represents original font specification.

--------------------

Provides info related to original font such as , flag. Also provides flag that helps to check is the substitution will anyway happen with the font and the user may override the default substitution logic.
## Constructors

| Constructor | Description |
| --- | --- |
| [OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable)](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Initializes new OriginalFontSpecification object. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOriginalFontName()](#getOriginalFontName--) | Gets original font name. |
| [hashCode()](#hashCode--) |  |
| [isEmbedded()](#isEmbedded--) | Gets a value that indicates whether the font is embedded. |
| [isSubstitutionUnavoidable()](#isSubstitutionUnavoidable--) | Gets a value that indicates that the substitution is unavoidable. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable) {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
```
public OriginalFontSpecification(String originalFontName, boolean isEmbedded, boolean isUnavoidable)
```


Initializes new OriginalFontSpecification object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalFontName | java.lang.String | String object |
| isEmbedded | boolean | boolean value |
| isUnavoidable | boolean | boolean value |

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


Gets original font name.

**Returns:**
java.lang.String - String value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Gets a value that indicates whether the font is embedded.

**Returns:**
boolean - boolean value
### isSubstitutionUnavoidable() {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```


Gets a value that indicates that the substitution is unavoidable.

**Returns:**
boolean - boolean value

--------------------

Returns true in case substitution was requested because of absence of the original font or in case original font cannot be used in context of some task. In case user ignores the flag and doesn't substitute the font - default font substitution procedure is performed. But it provides opportunity for the user to alternate standard font substitution procedure and set better font to the system. Returns false in case original font is present, valid, but it is allowed for the user to substitute it.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

