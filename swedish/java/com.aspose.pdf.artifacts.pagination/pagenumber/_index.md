---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett sidnummerformat som inkluderar ett index, totalt antal sidor och en avgränsare."
type: docs
weight: 150
url: /sv/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Representerar ett sidnummerformat som inkluderar ett index, totalt antal sidor och en avgränsare.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Hämtar eller anger avgränsaren som används i sidnumrets format. Den formaterade strängen kommer att uppdateras baserat på den angivna avgränsaren. |
| [getIndex](#getIndex--) | Hämtar eller anger sidindexkomponenten i sidnumrets format. Den formaterade strängen kommer att innehålla en platshållare för sidindexet. |
| [getOffset](#getOffset--) | Hämtar eller anger förskjutningen som ska läggas till sidindexet. |
| [getPageNumberString](#getPageNumberString-int-int-) | Returnerar en formaterad sträng som representerar sidnumret baserat på de aktuella inställningarna. |
| [getTotalNum](#getTotalNum--) | Hämtar eller anger komponenten för totalt antal sidor i sidnumrets format. Den formaterade strängen kommer att innehålla en platshållare för det totala antalet sidor. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Hämtar eller anger avgränsaren som används i sidnumrets format. Den formaterade strängen kommer att uppdateras baserat på den angivna avgränsaren. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Hämtar eller anger sidindexkomponenten i sidnumrets format. |
| [setOffset](#setOffset-int-) | Hämtar eller anger förskjutningen som ska läggas till sidindexet. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Hämtar eller anger komponenten för totalt antal sidor i sidnumrets format. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Hämtar eller anger avgränsaren som används i sidnumrets format. Den formaterade strängen kommer att uppdateras baserat på den angivna avgränsaren.

**Returns:**
String värde

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Hämtar eller anger sidindexkomponenten i sidnumrets format. Den formaterade strängen kommer att innehålla en platshållare för sidindexet.

**Returns:**
PageIndex-instans

### getOffset {#getOffset--}
```
public final int getOffset()
```

Hämtar eller anger förskjutningen som ska läggas till sidindexet.

**Returns:**
int‑värde

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Returnerar en formaterad sträng som representerar sidnumret baserat på de aktuella inställningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber |  | Det aktuella sidnumret. |
| antal |  | Det totala antalet sidor. |

**Returns:**
En formaterad sidnummersträng.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Hämtar eller anger komponenten för totalt antal sidor i sidnumrets format. Den formaterade strängen kommer att innehålla en platshållare för det totala antalet sidor.

**Returns:**
PageTotalNum-instans

### setDelimiter {#setDelimiter-java.lang.String-}
Hämtar eller anger avgränsaren som används i sidnumrets format. Den formaterade strängen kommer att uppdateras baserat på den angivna avgränsaren.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Hämtar eller anger sidindexkomponenten i sidnumrets format.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Hämtar eller anger förskjutningen som ska läggas till sidindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Hämtar eller anger komponenten för totalt antal sidor i sidnumrets format.
