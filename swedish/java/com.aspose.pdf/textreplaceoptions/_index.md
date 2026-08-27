---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för textersättning"
type: docs
weight: 5250
url: /sv/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Representerar alternativ för textersättning

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Initierar en ny instans av {@code TextReplaceOptions}-objektet för standardjustering och -omfång: ReplaceAdjustment.None och Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Initierar en ny instans av {@code TextReplaceOptions}-objektet för den specificerade åtgärden efter ersättning. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Initierar en ny instans av {@code TextReplaceOptions}-objektet för standardjustering och -omfång: ReplaceAdjustment.None och Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Initierar en ny instans av {@code TextReplaceOptions}-objektet för standardjustering och -omfång: ReplaceAdjustment.None och Scope.REPLACE_FIRST |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Hämtar eller ställer in värdet för radavstånd som används om ersättningsjustering tvingas skapa en ny textrad. Det förväntade värdet är en multiplikator av teckenstorleken för den ersatta texten. Standard är 1,2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | Hämtar eller ställer in policyn för att justera teckenstorleken så att den passar inom gränserna som definieras av {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}). |
| [getLeftAdjustment](#getLeftAdjustment--) | Hämtar justering av vänster position för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | Hämtar eller ställer in rektangeln för att passa texten efter ersättning. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Hämtar en åtgärd som kommer att utföras efter att ett textfragment har ersatts med en kortare version. |
| [getReplaceScope](#getReplaceScope--) | Hämtar ett område där ersättningsoperationen för text tillämpas |
| [getRightAdjustment](#getRightAdjustment--) | Ställer in eller hämtar justering av högra positionen för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Hämtar eller anger ett värde som indikerar om separata stycken ska ignoreras när text på sidan justeras efter textersättning. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Hämtar eller ställer in värdet för radavstånd som används om ersättningsjustering tvingas skapa en ny textrad. Det förväntade värdet är en multiplikator av teckenstorleken för den ersatta texten. Standard är 1,2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | Hämtar eller anger policyn för att justera teckenstorleken så att den passar inom gränserna som definieras av TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Hämtar eller anger ett värde som indikerar om separata stycken ska ignoreras när text på sidan justeras efter textersättning. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | Ställer in eller hämtar justering av vänstra positionen för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Hämtar eller ställer in rektangeln för att passa texten efter ersättning. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Ställer in en åtgärd som kommer att utföras efter att ett textfragment har ersatts med en kortare version. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Ställer in ett område där ersättningsoperationen för text tillämpas |
| [setRightAdjustment](#setRightAdjustment-double-) | Ställer in justering av högra positionen för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Initierar en ny instans av {@code TextReplaceOptions}-objektet för standardjustering och -omfång: ReplaceAdjustment.None och Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Initierar en ny instans av {@code TextReplaceOptions}-objektet för den specificerade åtgärden efter ersättning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| justering |  | ReplaceAdjustment-objekt. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Initierar en ny instans av {@code TextReplaceOptions}-objektet för standardjustering och -omfång: ReplaceAdjustment.None och Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Initierar en ny instans av {@code TextReplaceOptions}-objektet för standardjustering och -omfång: ReplaceAdjustment.None och Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Hämtar eller ställer in värdet för radavstånd som används om ersättningsjustering tvingas skapa en ny textrad. Det förväntade värdet är en multiplikator av teckenstorleken för den ersatta texten. Standard är 1,2.

**Returns:**
double-värde

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

Hämtar eller ställer in policyn för att justera teckenstorleken så att den passar inom gränserna som definieras av {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}).

**Returns:**
FontSizeAdjustment-element

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

Hämtar justering av vänster position för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double-värde

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Hämtar eller ställer in rektangeln för att passa texten efter ersättning.

**Returns:**
Rektangelinstans

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Hämtar en åtgärd som kommer att utföras efter att ett textfragment har ersatts med en kortare version.

**Returns:**
ReplaceAdjustment-element @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Hämtar ett område där ersättningsoperationen för text tillämpas

**Returns:**
int-värde @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

Ställer in eller hämtar justering av högra positionen för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double-värde

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Hämtar eller anger ett värde som indikerar om separata stycken ska ignoreras när text på sidan justeras efter textersättning.

**Returns:**
boolean-värde

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Hämtar eller ställer in värdet för radavstånd som används om ersättningsjustering tvingas skapa en ny textrad. Det förväntade värdet är en multiplikator av teckenstorleken för den ersatta texten. Standard är 1,2.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
Hämtar eller anger policyn för att justera teckenstorleken så att den passar inom gränserna som definieras av TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Hämtar eller anger ett värde som indikerar om separata stycken ska ignoreras när text på sidan justeras efter textersättning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

Ställer in eller hämtar justering av vänstra positionen för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Hämtar eller ställer in rektangeln för att passa texten efter ersättning.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Ställer in en åtgärd som kommer att utföras efter att ett textfragment har ersatts med en kortare version.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ReplaceAdjustment-element @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Ställer in ett område där ersättningsoperationen för text tillämpas

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

Ställer in justering av högra positionen för ersatt text när TextReplaceOptions används: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |
