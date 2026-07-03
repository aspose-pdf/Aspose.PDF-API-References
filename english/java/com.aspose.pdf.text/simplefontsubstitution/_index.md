---
title: SimpleFontSubstitution
linktitle: SimpleFontSubstitution
second_title: Aspose.PDF for Java API Reference
description: Represents a class for simple font substitution strategy.
type: docs
weight: 90
url: /java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

Represents a class for simple font substitution strategy.

## Constructors

| Constructor | Description |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Initializes a new instance of {@code SimpleFontSubstitution} class. |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Initializes a new instance of {@code SimpleFontSubstitution} class. |

## Methods

| Method | Description |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Gets original font name that should be substituted with {@code SubstitutionFontName} |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | Returns unicode substitution |
| [getSubstitutionFontName](#getSubstitutionFontName--) | Gets font name that should substitute the {@code OriginalFontName} |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
Initializes a new instance of {@code SimpleFontSubstitution} class.

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
Initializes a new instance of {@code SimpleFontSubstitution} class.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Gets original font name that should be substituted with {@code SubstitutionFontName}

**Returns:**
String value

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

Returns unicode substitution

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unicode |  | char value |

**Returns:**
char value

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

Gets font name that should substitute the {@code OriginalFontName}

**Returns:**
String value
