---
title: SystemFontsSubstitution
linktitle: SystemFontsSubstitution
second_title: Aspose.PDF for Java API Reference
description: Represents a class for font substitution strategy that substitutes fonts with system fonts.
type: docs
weight: 110
url: /java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Represents a class for font substitution strategy that substitutes fonts with system fonts.

## Constructors

| Constructor | Description |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | Initializes a new instance of {@code SystemFontsSubstitution} class. |

## Methods

| Method | Description |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Gets or sets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ({@code FontCategories}). |
| [getFontCategories](#getFontCategories--) | Gets or sets substitution font categories that should be substituted with system fonts. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Gets or sets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ({@code FontCategories}). |
| [setFontCategories](#setFontCategories-int-) | Gets or sets substitution font categories that should be substituted with system fonts. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

Initializes a new instance of {@code SystemFontsSubstitution} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontCategories |  | Target font categories to substitute with system fonts |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Gets or sets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ({@code FontCategories}).

**Returns:**
Font object

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Gets or sets substitution font categories that should be substituted with system fonts.

**Returns:**
SubstitutionFontCategories element @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Gets or sets default substitution font. The font is used when no other valid substitution were found but initial font belongs to target substitution category ({@code FontCategories}).

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Gets or sets substitution font categories that should be substituted with system fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | SubstitutionFontCategories element @see SubstitutionFontCategories |
