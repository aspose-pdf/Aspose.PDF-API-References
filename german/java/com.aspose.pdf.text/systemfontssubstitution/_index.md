---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse für eine Schriftart‑Ersetzungsstrategie dar, die Schriftarten durch Systemschriftarten ersetzt."
type: docs
weight: 110
url: /de/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Stellt eine Klasse für eine Schriftart‑Ersetzungsstrategie dar, die Schriftarten durch Systemschriftarten ersetzt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | Initialisiert eine neue Instanz der {@code SystemFontsSubstitution}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Liest oder setzt die Standardschriftart für Ersetzungen. Die Schriftart wird verwendet, wenn keine andere gültige Ersetzung gefunden wurde, aber die ursprüngliche Schriftart zur Ziel-Ersetzungskategorie ({@code FontCategories}) gehört. |
| [getFontCategories](#getFontCategories--) | Liest oder setzt Schriftart-Kategorien für Ersetzungen, die durch Systemschriftarten ersetzt werden sollen. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Liest oder setzt die Standardschriftart für Ersetzungen. Die Schriftart wird verwendet, wenn keine andere gültige Ersetzung gefunden wurde, aber die ursprüngliche Schriftart zur Ziel-Ersetzungskategorie ({@code FontCategories}) gehört. |
| [setFontCategories](#setFontCategories-int-) | Liest oder setzt Schriftart-Kategorien für Ersetzungen, die durch Systemschriftarten ersetzt werden sollen. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

Initialisiert eine neue Instanz der {@code SystemFontsSubstitution}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontCategories |  | Ziel-Schriftartkategorien, die durch Systemschriftarten ersetzt werden sollen |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Liest oder setzt die Standardschriftart für Ersetzungen. Die Schriftart wird verwendet, wenn keine andere gültige Ersetzung gefunden wurde, aber die ursprüngliche Schriftart zur Ziel-Ersetzungskategorie ({@code FontCategories}) gehört.

**Returns:**
Schrift-Objekt

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Liest oder setzt Schriftart-Kategorien für Ersetzungen, die durch Systemschriftarten ersetzt werden sollen.

**Returns:**
SubstitutionFontCategories-Element @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Liest oder setzt die Standardschriftart für Ersetzungen. Die Schriftart wird verwendet, wenn keine andere gültige Ersetzung gefunden wurde, aber die ursprüngliche Schriftart zur Ziel-Ersetzungskategorie ({@code FontCategories}) gehört.

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Liest oder setzt Schriftart-Kategorien für Ersetzungen, die durch Systemschriftarten ersetzt werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | SubstitutionFontCategories-Element @see SubstitutionFontCategories |
