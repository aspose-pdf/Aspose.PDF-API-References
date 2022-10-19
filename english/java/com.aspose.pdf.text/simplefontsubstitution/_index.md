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
| [getOriginalFontName()](#getOriginalFontName--) | Gets original font name that should be substituted with  SubstitutionFontName  |
| [getSubstitutionFontName()](#getSubstitutionFontName--) | Gets font name that should substitute the  OriginalFontName  |
| [getSubstitutedUnicode(char unicode)](#getSubstitutedUnicode-char-) | Returns unicode substitution |
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

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Gets original font name that should be substituted with  SubstitutionFontName 

**Returns:**
java.lang.String - String value
### getSubstitutionFontName() {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```


Gets font name that should substitute the  OriginalFontName 

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
