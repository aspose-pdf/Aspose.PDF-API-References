---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar sidnumreringsstämpel och används för att numrera sidor."
type: docs
weight: 3440
url: /sv/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Representerar sidnumreringsstämpel och används för att numrera sidor.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | Initierar en ny instans av klassen {@code PageNumberStamp}. Formatet är satt till \"#\". |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Initierar en ny instans av klassen {@code PageNumberStamp}. Formatet är satt till \"#\". |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | Initierar en ny instans av klassen {@code PageNumberStamp}. Formatet är satt till \"#\". |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat](#getFormat--) | Hämtar strängvärde för stämpling av sidnummer. Värdet måste innehålla tecknet '#' som ersätts med sidnumret under stämplingsprocessen. |
| [getNumberingStyle](#getNumberingStyle--) | Numreringsstil som används av detta stämpel. |
| [getStartingNumber](#getStartingNumber--) | Hämtar värdet för startsidans nummer. Övriga sidor kommer att numreras med början från detta värde. |
| [put](#put-com.aspose.pdf.Page-) | Lägger till sidnummer. |
| [setFormat](#setFormat-java.lang.String-) | Ställer in strängvärde för stämpling av sidnummer. Värdet måste innehålla tecknet '#' som ersätts med sidnumret under stämplingsprocessen. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Numreringsstil som används av detta stämpel. |
| [setStartingNumber](#setStartingNumber-int-) | Ställer in värdet för startsidans nummer. Övriga sidor kommer att numreras med början från detta värde. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

Initierar en ny instans av klassen {@code PageNumberStamp}. Formatet är satt till \"#\".

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
Initierar en ny instans av klassen {@code PageNumberStamp}. Formatet är satt till \"#\".

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
Initierar en ny instans av klassen {@code PageNumberStamp}. Formatet är satt till \"#\".

### getFormat {#getFormat--}
```
public String getFormat()
```

Hämtar strängvärde för stämpling av sidnummer. Värdet måste innehålla tecknet '#' som ersätts med sidnumret under stämplingsprocessen.

**Returns:**
String värde

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Numreringsstil som används av detta stämpel.

**Returns:**
NumberingStyle-värde @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Hämtar värdet för startsidans nummer. Övriga sidor kommer att numreras med början från detta värde.

**Returns:**
int‑värde

### put {#put-com.aspose.pdf.Page-}
Lägger till sidnummer.

### setFormat {#setFormat-java.lang.String-}
Ställer in strängvärde för stämpling av sidnummer. Värdet måste innehålla tecknet '#' som ersätts med sidnumret under stämplingsprocessen.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Numreringsstil som används av detta stämpel.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Ställer in värdet för startsidans nummer. Övriga sidor kommer att numreras med början från detta värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
