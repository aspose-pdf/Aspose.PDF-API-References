---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för enkel teckensnittbytesstrategi."
type: docs
weight: 90
url: /sv/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

Representerar en klass för enkel teckensnittbytesstrategi.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Initierar en ny instans av {@code SimpleFontSubstitution}-klassen. |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Initierar en ny instans av {@code SimpleFontSubstitution}-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Hämtar ursprungligt teckensnittsnamn som ska ersättas med {@code SubstitutionFontName} |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | Returnerar unicode-substitution |
| [getSubstitutionFontName](#getSubstitutionFontName--) | Hämtar teckensnittsnamn som ska ersätta {@code OriginalFontName} |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
Initierar en ny instans av {@code SimpleFontSubstitution}-klassen.

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
Initierar en ny instans av {@code SimpleFontSubstitution}-klassen.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Hämtar ursprungligt teckensnittsnamn som ska ersättas med {@code SubstitutionFontName}

**Returns:**
String värde

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

Returnerar unicode-substitution

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unicode |  | teckenvärde |

**Returns:**
teckenvärde

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

Hämtar teckensnittsnamn som ska ersätta {@code OriginalFontName}

**Returns:**
String värde
