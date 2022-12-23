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
| [getOriginalFontName()](#getOriginalFontName--) | Gets original font name. |
| [isEmbedded()](#isEmbedded--) | Gets a value that indicates whether the font is embedded. |
| [isSubstitutionUnavoidable()](#isSubstitutionUnavoidable--) | Gets a value that indicates that the substitution is unavoidable. |
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

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Gets original font name.

**Returns:**
java.lang.String - String value
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
