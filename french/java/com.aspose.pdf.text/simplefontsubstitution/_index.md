---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour une stratégie simple de substitution de police."
type: docs
weight: 90
url: /fr/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

Représente une classe pour une stratégie simple de substitution de police.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe {@code SimpleFontSubstitution}. |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Initialise une nouvelle instance de la classe {@code SimpleFontSubstitution}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Obtient le nom de police original qui doit être substitué par {@code SubstitutionFontName} |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | Renvoie la substitution unicode |
| [getSubstitutionFontName](#getSubstitutionFontName--) | Obtient le nom de police qui doit substituer le {@code OriginalFontName} |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
Initialise une nouvelle instance de la classe {@code SimpleFontSubstitution}.

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
Initialise une nouvelle instance de la classe {@code SimpleFontSubstitution}.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Obtient le nom de police original qui doit être substitué par {@code SubstitutionFontName}

**Returns:**
valeur String

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

Renvoie la substitution unicode

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| unicode |  | valeur char |

**Returns:**
valeur char

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

Obtient le nom de police qui doit substituer le {@code OriginalFontName}

**Returns:**
valeur String
