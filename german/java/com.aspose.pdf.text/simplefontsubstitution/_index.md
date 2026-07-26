---
title: "SimpleFontSubstitution"
linktitle: "SimpleFontSubstitution"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse für eine einfache Schriftart‑Ersetzungsstrategie dar."
type: docs
weight: 90
url: /de/java/com.aspose.pdf.text/simplefontsubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SimpleFontSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SimpleFontSubstitution

```
public final class SimpleFontSubstitution extends FontSubstitution
```

Stellt eine Klasse für eine einfache Schriftart‑Ersetzungsstrategie dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-) | Initialisiert eine neue Instanz der {@code SimpleFontSubstitution}-Klasse. |
| [SimpleFontSubstitution](#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-) | Initialisiert eine neue Instanz der {@code SimpleFontSubstitution}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Liest den ursprünglichen Schriftartnamen, der durch {@code SubstitutionFontName} ersetzt werden soll |
| [getSubstitutedUnicode](#getSubstitutedUnicode-char-) | Gibt die Unicode-Substitution zurück |
| [getSubstitutionFontName](#getSubstitutionFontName--) | Liest den Schriftartnamen, der {@code OriginalFontName} ersetzen soll |

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-}
Initialisiert eine neue Instanz der {@code SimpleFontSubstitution}-Klasse.

### SimpleFontSubstitution {#SimpleFontSubstitution-java.lang.String-java.lang.String-boolean-}
Initialisiert eine neue Instanz der {@code SimpleFontSubstitution}-Klasse.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Liest den ursprünglichen Schriftartnamen, der durch {@code SubstitutionFontName} ersetzt werden soll

**Returns:**
String Wert

### getSubstitutedUnicode {#getSubstitutedUnicode-char-}
```
public char getSubstitutedUnicode(char unicode)
```

Gibt die Unicode-Substitution zurück

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Unicode |  | Zeichenwert |

**Returns:**
Zeichenwert

### getSubstitutionFontName {#getSubstitutionFontName--}
```
public String getSubstitutionFontName()
```

Liest den Schriftartnamen, der {@code OriginalFontName} ersetzen soll

**Returns:**
String Wert
