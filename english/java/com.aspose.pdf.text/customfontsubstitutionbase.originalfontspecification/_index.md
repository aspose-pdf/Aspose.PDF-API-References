---
title: CustomFontSubstitutionBase.OriginalFontSpecification
second_title: Aspose.PDF for Java API Reference
description: <p> Represents original font specification. </p> <hr> <p> Provides info related to original font such as , flag. Also provides flag that helps to check is the substitution will.
type: docs
weight: 20
url: /java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Represents original font specification. </p> <hr> <p> Provides info related to original font such as , flag. Also provides flag that helps to check is the substitution will anyway happen with the font and the user may override the default substitution logic. </p>

## Constructors

| Constructor | Description |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Initializes new OriginalFontSpecification object. |

## Methods

| Method | Description |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Gets original font name. |
| [isEmbedded](#isEmbedded--) | Gets a value that indicates whether the font is embedded. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Gets a value that indicates that the substitution is unavoidable. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Initializes new OriginalFontSpecification object.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Gets original font name.

**Returns:**
String value

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Gets a value that indicates whether the font is embedded.

**Returns:**
boolean value

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Gets a value that indicates that the substitution is unavoidable. </p>

**Returns:**
boolean value <hr> <p> Returns true in case substitution was requested because of absence of the original font or in case original font cannot be used in context of some task. In case user ignores the flag and doesn't substitute the font - default font substitution procedure is performed. But it provides opportunity for the user to alternate standard font substitution procedure and set better font to the system. Returns false in case original font is present, valid, but it is allowed for the user to substitute it. </p>
