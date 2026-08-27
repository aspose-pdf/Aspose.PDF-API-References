---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en FloatingBox i ett PDF-dokument. FloatingBox är anpassat placerad."
type: docs
weight: 1610
url: /sv/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Representerar en FloatingBox i ett PDF-dokument. FloatingBox är anpassat placerad.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Initierar en ny instans av klassen {@code FloatingBox}. |
| [FloatingBox](#FloatingBox-float-float-) | Initierar en ny instans av klassen {@code FloatingBox} med angiven bredd och höjd. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [deepClone](#deepClone--) | Klonar ett nytt {@code FloatingBox}-objekt. Paragrafer i den flytande rutan klonas inte. |
| [getBackgroundColor](#getBackgroundColor--) | Hämtar ett objekt som anger bakgrundsfärgen för den flytande rutan. |
| [getBackgroundImage](#getBackgroundImage--) | Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokument). |
| [getBorder](#getBorder--) | Hämtar ett objekt som anger kantinformationen för den flytande rutan. |
| [getColumnInfo](#getColumnInfo--) | Hämtar kolumninformation |
| [getHeight](#getHeight--) | Hämtar ett flyttal som anger höjden på den flytande rutan. |
| [getLeft](#getLeft--) | Hämtar tabellens vänstra koordinat. |
| [getPadding](#getPadding--) | Hämtar ett objekt som anger utfyllnaden för den flytande rutan. |
| [getParagraphs](#getParagraphs--) | Hämtar en samling som visar alla paragrafer i cellen. |
| [getPositioningMode](#getPositioningMode--) | Anger variant för att bestämma placeringen av FloatingBox på sidan. |
| [getTop](#getTop--) | Hämtar tabellens övre koordinat. |
| [getWidth](#getWidth--) | Hämtar ett flyttal som anger bredden på den flytande rutan. |
| [isNeedRepeating](#isNeedRepeating--) | Hämtar ett booleskt värde som anger om paragrafen behöver upprepas på nästa sida. Standardvärdet är true. Attributet är endast giltigt när paragrafen själv och objektet som dess ReferenceParagraphID refererar till båda ingår i RepeatingRows. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Anger ett objekt som anger bakgrundsfärgen för den flytande rutan. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokument). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Anger ett objekt som anger kantinformationen för den flytande rutan. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Anger kolumninformation |
| [setHeight](#setHeight-double-) | Ställer in ett flyttal som indikerar höjden på den flytande rutan. |
| [setLeft](#setLeft-double-) | Ställer in tabellens vänstra koordinat. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Ställer in ett booleskt värde som indikerar om stycket ska upprepas på nästa sida. Standardvärdet är true. Attributet är endast giltigt när själva stycket och objektet som dess ReferenceParagraphID refererar till båda är inkluderade i RepeatingRows. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Ställer in ett objekt som anger utfyllnaden för den flytande rutan. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Ställer in en samling som indikerar alla stycken i cellen. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Anger variant för att bestämma placeringen av FloatingBox på sidan. |
| [setTop](#setTop-double-) | Ställer in tabellens övre koordinat. |
| [setWidth](#setWidth-double-) | Ställer in ett flyttal som indikerar bredden på den flytande rutan. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Initierar en ny instans av klassen {@code FloatingBox}.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Initierar en ny instans av klassen {@code FloatingBox} med angiven bredd och höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Bredden på rutan. |
| höjd |  | Höjden på rutan. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klonar ett nytt {@code FloatingBox}-objekt. Paragrafer i den flytande rutan klonas inte.

**Returns:**
Det nya {@code FloatingBox} objektet.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Hämtar ett objekt som anger bakgrundsfärgen för den flytande rutan.

**Returns:**
objekt som anger bakgrundsfärgen.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokument).

**Returns:**
Bildinstans

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Hämtar ett objekt som anger kantinformationen för den flytande rutan.

**Returns:**
objekt som anger kantinformation.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Hämtar kolumninformation

**Returns:**
ColumnInfo-objekt

### getHeight {#getHeight--}
```
public double getHeight()
```

Hämtar ett flyttal som anger höjden på den flytande rutan.

**Returns:**
värde som indikerar höjden.

### getLeft {#getLeft--}
```
public double getLeft()
```

Hämtar tabellens vänstra koordinat.

**Returns:**
tabellens vänstra koordinat.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Hämtar ett objekt som anger utfyllnaden för den flytande rutan.

**Returns:**
objekt som anger utfyllnaden.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Hämtar en samling som visar alla paragrafer i cellen.

**Returns:**
samling som indikerar alla stycken.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Anger variant för att bestämma placeringen av FloatingBox på sidan.

**Returns:**
ParagraphPositioningMode-element

### getTop {#getTop--}
```
public double getTop()
```

Hämtar tabellens övre koordinat.

**Returns:**
tabellens övre koordinat.

### getWidth {#getWidth--}
```
public double getWidth()
```

Hämtar ett flyttal som anger bredden på den flytande rutan.

**Returns:**
double-värde

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Hämtar ett booleskt värde som anger om paragrafen behöver upprepas på nästa sida. Standardvärdet är true. Attributet är endast giltigt när paragrafen själv och objektet som dess ReferenceParagraphID refererar till båda ingår i RepeatingRows.

**Returns:**
booleskt värde

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Anger ett objekt som anger bakgrundsfärgen för den flytande rutan.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokument).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Anger ett objekt som anger kantinformationen för den flytande rutan.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Anger kolumninformation

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Ställer in ett flyttal som indikerar höjden på den flytande rutan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | värde som indikerar höjden. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Ställer in tabellens vänstra koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | tabellens vänstra koordinat. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Ställer in ett booleskt värde som indikerar om stycket ska upprepas på nästa sida. Standardvärdet är true. Attributet är endast giltigt när själva stycket och objektet som dess ReferenceParagraphID refererar till båda är inkluderade i RepeatingRows.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Ställer in ett objekt som anger utfyllnaden för den flytande rutan.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Ställer in en samling som indikerar alla stycken i cellen.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Anger variant för att bestämma placeringen av FloatingBox på sidan.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Ställer in tabellens övre koordinat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | tabellens övre koordinat. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Ställer in ett flyttal som indikerar bredden på den flytande rutan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |
