---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para una estrategia simple de sustitución de fuentes."
type: docs
weight: 90
url: /es/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

Representa una clase para una estrategia simple de sustitución de fuentes.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase {@code SimpleFontSubstitution}. |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Inicializa una nueva instancia de la clase {@code SimpleFontSubstitution}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Obtiene el nombre de fuente original que debe ser sustituido con {@code SubstitutionFontName} |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | Devuelve la sustitución unicode |
| [getSubstitutionFontName](#getSubstitutionFontName--) | Obtiene el nombre de fuente que debe sustituir al {@code OriginalFontName} |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
Inicializa una nueva instancia de la clase {@code SimpleFontSubstitution}.

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
Inicializa una nueva instancia de la clase {@code SimpleFontSubstitution}.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Obtiene el nombre de fuente original que debe ser sustituido con {@code SubstitutionFontName}

**Returns:**
valor String

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

Devuelve la sustitución unicode

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| unicode |  | valor char |

**Returns:**
valor char

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

Obtiene el nombre de fuente que debe sustituir al {@code OriginalFontName}

**Returns:**
valor String
