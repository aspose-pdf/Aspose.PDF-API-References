---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för teckensnittbytesstrategi som ersätter teckensnitt med systemteckensnitt."
type: docs
weight: 110
url: /sv/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Representerar en klass för teckensnittbytesstrategi som ersätter teckensnitt med systemteckensnitt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | Initierar en ny instans av {@code SystemFontsSubstitution}-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Hämtar eller anger standardteckensnitt för ersättning. Teckensnittet används när ingen annan giltig ersättning hittades men det ursprungliga teckensnittet tillhör mål-ersättningskategorin ({@code FontCategories}). |
| [getFontCategories](#getFontCategories--) | Hämtar eller anger teckensnittskategorier för ersättning som ska ersättas med systemteckensnitt. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Hämtar eller anger standardteckensnitt för ersättning. Teckensnittet används när ingen annan giltig ersättning hittades men det ursprungliga teckensnittet tillhör mål-ersättningskategorin ({@code FontCategories}). |
| [setFontCategories](#setFontCategories-int-) | Hämtar eller anger teckensnittskategorier för ersättning som ska ersättas med systemteckensnitt. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

Initierar en ny instans av {@code SystemFontsSubstitution}-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontCategories |  | Målkategorier för teckensnitt att ersätta med systemteckensnitt |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Hämtar eller anger standardteckensnitt för ersättning. Teckensnittet används när ingen annan giltig ersättning hittades men det ursprungliga teckensnittet tillhör mål-ersättningskategorin ({@code FontCategories}).

**Returns:**
Font‑objekt

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Hämtar eller anger teckensnittskategorier för ersättning som ska ersättas med systemteckensnitt.

**Returns:**
SubstitutionFontCategories-element @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Hämtar eller anger standardteckensnitt för ersättning. Teckensnittet används när ingen annan giltig ersättning hittades men det ursprungliga teckensnittet tillhör mål-ersättningskategorin ({@code FontCategories}).

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Hämtar eller anger teckensnittskategorier för ersättning som ska ersättas med systemteckensnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | SubstitutionFontCategories-element @see SubstitutionFontCategories |
