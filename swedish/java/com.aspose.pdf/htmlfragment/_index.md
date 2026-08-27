---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar HTML‑fragment."
type: docs
weight: 1950
url: /sv/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

Representerar HTML‑fragment.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | Initierar en ny instans av klassen HtmlFragment. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klonar html-fragment. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Hämtar HtmlLoadOptions som kommer att användas för inläsning (och rendering) av HTML i detta klassinstans. Använd den när det är nödvändigt att använda specifika inställningar för import av HTML för denna eller den andra instansen (t.ex. när denna eller den andra instansen ska använda en specifik BasePath för importerad HTML eller en specifik laddare för externa resurser). Om parametern är standard (null) används standardalternativ för HTML-inläsning. |
| [getRectangle](#getRectangle--) | Hämtar rektangeln för HtmlFragment |
| [getTextState](#getTextState--) | Hämtar eller anger teckensnitt |
| [isBreakWords](#isBreakWords--) | Hämtar eller anger ordbrytning |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Hämtar eller anger om stycket har standardmarginal, annars är marginalen 0 |
| [setBreakWords](#setBreakWords-boolean-) | Hämtar eller anger ordbrytning |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Anger HtmlLoadOptions som kommer att användas för inläsning (och rendering) av HTML i detta klassinstans. Använd den när det är nödvändigt att använda specifika inställningar för import av HTML för denna eller den andra instansen (t.ex. när denna eller den andra instansen ska använda en specifik BasePath för importerad HTML eller en specifik laddare för externa resurser). Om parametern är standard (null) används standardalternativ för HTML-inläsning. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Hämtar eller anger om stycket har standardmarginal, annars är marginalen 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Hämtar eller anger teckensnitt |

### HtmlFragment {#HtmlFragment-java.lang.String-}
Initierar en ny instans av klassen HtmlFragment.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klonar html-fragment.

**Returns:**
Klonat html-fragmentobjekt.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Hämtar HtmlLoadOptions som kommer att användas för inläsning (och rendering) av HTML i detta klassinstans. Använd den när det är nödvändigt att använda specifika inställningar för import av HTML för denna eller den andra instansen (t.ex. när denna eller den andra instansen ska använda en specifik BasePath för importerad HTML eller en specifik laddare för externa resurser). Om parametern är standard (null) används standardalternativ för HTML-inläsning.

**Returns:**
HtmlLoadOptions-värde

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Hämtar rektangeln för HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float-instans

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Hämtar eller anger teckensnitt

**Returns:**
TextState-objekt

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Hämtar eller anger ordbrytning

**Returns:**
booleskt värde

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Hämtar eller anger om stycket har standardmarginal, annars är marginalen 0

**Returns:**
booleskt värde

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Hämtar eller anger ordbrytning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Anger HtmlLoadOptions som kommer att användas för inläsning (och rendering) av HTML i detta klassinstans. Använd den när det är nödvändigt att använda specifika inställningar för import av HTML för denna eller den andra instansen (t.ex. när denna eller den andra instansen ska använda en specifik BasePath för importerad HTML eller en specifik laddare för externa resurser). Om parametern är standard (null) används standardalternativ för HTML-inläsning.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Hämtar eller anger om stycket har standardmarginal, annars är marginalen 0

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Hämtar eller anger teckensnitt
