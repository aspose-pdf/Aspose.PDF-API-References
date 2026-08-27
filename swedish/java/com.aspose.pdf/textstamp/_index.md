---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en textstämpel."
type: docs
weight: 5320
url: /sv/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Representerar en textstämpel.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Initierar en ny instans av {@code TextStamp}-klassen med formattedText-objekt |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Initierar en ny instans av {@code TextStamp}-klassen med formattedText-objekt |
| [TextStamp](#TextStamp-java.lang.String-) | Initierar en ny instans av klassen {@code TextStamp}. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Initierar en ny instans av TextStamp-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Justera automatiskt precisionen för teckenstorlek. Standardvärde: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | Om aktiverat kommer teckenstorleken att automatiskt justeras för att passa stämpelrektangeln med storleken: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) och {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Standardbredd och -höjd hämtas från sidans rektangel. |
| [getDefaultFont](#getDefaultFont--) | Returnerar standardteckensnitt |
| [getDefaultFontSize](#getDefaultFontSize--) | Standardteckenstorlek |
| [getDraw](#getDraw--) | Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om draw = false ritas stämpeln som text. |
| [getFontSize](#getFontSize--) | Faktisk teckenstorlek efter att stämpeln har placerats. (Kan skilja sig från den ursprungliga teckenstorleken som angavs via konstruktorn om alternativet 'AutoAdjustFontSizeToFitStampRectangle' är aktiverat.) |
| [getHeight](#getHeight--) | Önskad höjd för stämpeln på sidan. |
| [getMaxRowWidth](#getMaxRowWidth--) | Maximal radhöjd för WordWrap-alternativet. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Hämtar eller anger läge som definierar beteendet när teckensnitt inte innehåller begärda tecken. |
| [getReplacementFont](#getReplacementFont--) | Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet. |
| [getTextAlignment](#getTextAlignment--) | Justering av texten inom stämpeln. |
| [getTextState](#getTextState--) | Hämtar textegenskaperna för stämpeln. Se {@code TextState} för detaljer. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Definierar koordinatursprunget för placering av text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent‑värdet att behandlas som textbaslinje. Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent‑värdet att behandlas som botten (nedstigningslinje) för text. |
| [getValue](#getValue--) | Hämtar strängvärdet som används som stämpel på sidan. |
| [getWidth](#getWidth--) | Önskad bredd för stämpeln på sidan. |
| [getWordWrapMode](#getWordWrapMode--) | Hämtar eller anger ordbrytningsläget för textrendering. |
| [isJustify](#isJustify--) | Definierar textjustering. Om denna egenskap är satt till true justeras både vänster- och högerranden av texten. Standardvärde: false. |
| [isScale](#isScale--) | Definierar skalning av texten. Om denna egenskap är satt till true och ett breddvärde har angetts, kommer texten att skalas för att passa den angivna bredden. |
| [isWordWrap](#isWordWrap--) | Definierar ordbrytning. Om denna egenskap är satt till true och ett breddvärde har angetts, kommer texten att brytas i flera rader för att passa den angivna bredden. Standardvärde: false. |
| [put](#put-com.aspose.pdf.Page-) | Lägger till en textstämpel på sidan. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Justera automatiskt precisionen för teckenstorlek. Standardvärde: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | Om aktiverat kommer teckenstorleken att automatiskt justeras för att passa stämpelrektangeln med storleken: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) och {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Standardbredd och -höjd hämtas från sidans rektangel. |
| [setDraw](#setDraw-boolean-) | Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om draw = false ritas stämpeln som text. |
| [setHeight](#setHeight-double-) | Önskad höjd för stämpeln på sidan. |
| [setJustify](#setJustify-boolean-) | Definierar textjustering. Om denna egenskap är satt till true justeras både vänster- och högerranden av texten. Standardvärde: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | Maximal radhöjd för WordWrap-alternativet. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Hämtar eller anger läge som definierar beteendet när teckensnitt inte innehåller begärda tecken. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet. |
| [setScale](#setScale-boolean-) | Definierar skalning av texten. Om denna egenskap är satt till true och ett breddvärde har angetts, kommer texten att skalas för att passa den angivna bredden. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Justering av texten inom stämpeln. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Definierar koordinatursprunget för placering av text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent‑värdet att behandlas som textbaslinje. Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent‑värdet att behandlas som botten (nedstigningslinje) för text. |
| [setValue](#setValue-java.lang.String-) | Anger strängvärdet som används som stämpel på sidan. |
| [setWidth](#setWidth-double-) | Önskad bredd för stämpeln på sidan. |
| [setWordWrap](#setWordWrap-boolean-) | Definierar ordbrytning. Om denna egenskap är satt till true och ett breddvärde har angetts, kommer texten att brytas i flera rader för att passa den angivna bredden. Standardvärde: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Hämtar eller anger ordbrytningsläget för textrendering. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Initierar en ny instans av {@code TextStamp}-klassen med formattedText-objekt

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Initierar en ny instans av {@code TextStamp}-klassen med formattedText-objekt

### TextStamp {#TextStamp-java.lang.String-}
Initierar en ny instans av klassen {@code TextStamp}.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Initierar en ny instans av TextStamp-klassen.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Justera automatiskt precisionen för teckenstorlek. Standardvärde: 0.1;

**Returns:**
flyttalsvärde

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

Om aktiverat kommer teckenstorleken att automatiskt justeras för att passa stämpelrektangeln med storleken: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) och {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Standardbredd och -höjd hämtas från sidans rektangel.

**Returns:**
booleskt värde

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Returnerar standardteckensnitt

**Returns:**
com.aspose.pdf.Font-objekt

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Standardteckenstorlek

**Returns:**
flyttalsvärde

### getDraw {#getDraw--}
```
public boolean getDraw()
```

Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om draw = false ritas stämpeln som text.

**Returns:**
booleskt värde

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Faktisk teckenstorlek efter att stämpeln har placerats. (Kan skilja sig från den ursprungliga teckenstorleken som angavs via konstruktorn om alternativet 'AutoAdjustFontSizeToFitStampRectangle' är aktiverat.)

**Returns:**
flyttalsvärde

### getHeight {#getHeight--}
```
public double getHeight()
```

Önskad höjd för stämpeln på sidan.

**Returns:**
double-värde

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

Maximal radhöjd för WordWrap-alternativet.

**Returns:**
double-värde

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Hämtar eller anger läge som definierar beteendet när teckensnitt inte innehåller begärda tecken.

**Returns:**
NoCharacterAction-element

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet.

**Returns:**
Font instans

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Justering av texten inom stämpeln.

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Hämtar textegenskaperna för stämpeln. Se {@code TextState} för detaljer.

**Returns:**
TextState-element

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Definierar koordinatursprunget för placering av text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent‑värdet att behandlas som textbaslinje. Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent‑värdet att behandlas som botten (nedstigningslinje) för text.

**Returns:**
booleskt värde

### getValue {#getValue--}
```
public String getValue()
```

Hämtar strängvärdet som används som stämpel på sidan.

**Returns:**
String värde

### getWidth {#getWidth--}
```
public double getWidth()
```

Önskad bredd för stämpeln på sidan.

**Returns:**
double-värde

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Hämtar eller anger ordbrytningsläget för textrendering.

**Returns:**
WordWrapMode-element

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Definierar textjustering. Om denna egenskap är satt till true justeras både vänster- och högerranden av texten. Standardvärde: false.

**Returns:**
booleskt värde

### isScale {#isScale--}
```
public boolean isScale()
```

Definierar skalning av texten. Om denna egenskap är satt till true och ett breddvärde har angetts, kommer texten att skalas för att passa den angivna bredden.

**Returns:**
booleskt värde

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Definierar ordbrytning. Om denna egenskap är satt till true och ett breddvärde har angetts, kommer texten att brytas i flera rader för att passa den angivna bredden. Standardvärde: false.

**Returns:**
booleskt värde @deprecated "Använd WordWrapMode istället."

### put {#put-com.aspose.pdf.Page-}
Lägger till en textstämpel på sidan.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Justera automatiskt precisionen för teckenstorlek. Standardvärde: 0.1;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

Om aktiverat kommer teckenstorleken att automatiskt justeras för att passa stämpelrektangeln med storleken: {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) och {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}). Standardbredd och -höjd hämtas från sidans rektangel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om draw = false ritas stämpeln som text.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Önskad höjd för stämpeln på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Definierar textjustering. Om denna egenskap är satt till true justeras både vänster- och högerranden av texten. Standardvärde: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

Maximal radhöjd för WordWrap-alternativet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Hämtar eller anger läge som definierar beteendet när teckensnitt inte innehåller begärda tecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | NoCharacterAction-element |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Hämtar eller anger teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Definierar skalning av texten. Om denna egenskap är satt till true och ett breddvärde har angetts, kommer texten att skalas för att passa den angivna bredden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Justering av texten inom stämpeln.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Definierar koordinatursprunget för placering av text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent‑värdet att behandlas som textbaslinje. Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent‑värdet att behandlas som botten (nedstigningslinje) för text.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setValue {#setValue-java.lang.String-}
Anger strängvärdet som används som stämpel på sidan.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Önskad bredd för stämpeln på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Definierar ordbrytning. Om denna egenskap är satt till true och ett breddvärde har angetts, kommer texten att brytas i flera rader för att passa den angivna bredden. Standardvärde: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde @deprecated "Använd WordWrapMode istället." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Hämtar eller anger ordbrytningsläget för textrendering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | WordWrapMode-element @see WordWrapMode |
