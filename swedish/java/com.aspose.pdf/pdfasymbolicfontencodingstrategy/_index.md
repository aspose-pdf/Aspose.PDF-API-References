---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass beskriver regler som kan användas för att finjustera processen för att kopiera kodningsdata i fall då TrueType‑symboliska teckensnitt har mer än en kodning. Vissa PDF‑dokument efter."
type: docs
weight: 3690
url: /sv/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

Denna klass beskriver regler som kan användas för att finjustera processen för att kopiera kodningsdata i fall då TrueType-symboliska teckensnitt har mer än en kodning. Vissa PDF-dokument efter konvertering till PDF/A-format kan ge ett fel \"More than one encoding in symbolic TrueType font's cmap\". Vad är orsaken till detta fel? Alla TrueType-symboliska teckensnitt har en speciell tabell \"cmap\" i sin interna data. Denna tabell mappar teckenkoder till glyfindex. Och denna tabell kan innehålla olika kodningsundertabeller som beskriver de använda kodningarna. Se avancerad information om cmap-tabeller på https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Vanligtvis innehåller cmap-tabellen flera kodningsundertabeller, men PDF/A-standarden kräver att antingen endast en kodningsundertabell får finnas kvar för detta teckensnitt i PDF/A-dokumentet eller att det måste finnas en (3,0) kodningsundertabell bland teckensnittets undertabeller. Och den centrala frågan här – vilken data måste tas från andra undertabeller för att kopieras till destinationskodningstabellen (3,0)? Majoriteten av teckensnitten har 'välformade' cmap-tabeller där varje kodningsundertabell är fullt konsistent med en annan undertabell. Men vissa teckensnitt har cmap-tabeller med kollisioner – där till exempel en undertabell har glyfindex 100 för unicode 100, men en annan undertabell har glyfindex 200 för samma unicode 100. För att lösa dessa problem behövs en speciell strategi. Som standard används följande strategi: mac-undertabell(1,0) söks. Om denna tabell hittas används endast denna data för att fylla destinationstabellen (3,0). Om mac-undertabellen inte hittas itereras alla undertabeller förutom (3,0) och används för att kopiera data till destinationsundertabellen (3,0). Dessutom kopieras mappning för varje unicode (unicode, glyfindex) till destinationstabellen endast om destinationstabellen för närvarande inte har denna unicode. Så, till exempel om den första undertabellen har glyfindex 100 för unicode 100, och nästa undertabell har glyfindex 200 för samma unicode 100, kommer endast data från den första undertabellen (unicode=100, glyfindex = 100) att kopieras. Så varje föregående undertabell har företräde framför den nästa. Egenskaper i denna klass { PdfASymbolicFontEncodingStrategy} hjälper till att finjustera standardbeteendet. Om egenskapen {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) av typen { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} är satt, kommer relevant undertabell att användas med företräde framför mac-undertabell(1,0). Värdet 'MacTable' från uppräkningen {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} har ingen mening i detta fall, eftersom det pekar på samma mac-undertabell (1,0) som används som standard. Egenskapen {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) förkastar alla prioriteringar för någon undertabell. Om denna egenskap är satt, kommer endast undertabeller från den deklarerade kön att användas i angiven ordning. Om de specificerade undertabellerna inte hittas används standarditeration av alla undertabeller och kopieringsstrategin som beskrivits ovan. Objektet { PdfASymbolicFontEncodingStrategy.QueueItem} specificerar den använda kodningsundertabellen. Denna undertabell kan sättas via en kombination av medlemmar(PlatformID, PlatformSpecificId) eller via uppräkningen { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. Om teckensnittet saknar (3,0) undertabell kommer någon annan undertabell att användas för att upprätthålla PDF/A-kompatibiliteten. Valet av vilken undertabell som ska användas görs enligt samma regler som beskrivits tidigare, så att {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) och {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) egenskaper används för att bestämma den resulterande undertabellen, och om teckensnittet inte har den begärda undertabellen/undertabellerna kommer någon befintlig undertabell att användas.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | Konstruktor. Ställer in standard‑subtabell (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | Konstruktor. Ställer in standard‑subtabell (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | Anger kö av kodningssubtabeller som ska bearbetas. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | Anger subtabell som kommer att användas i företräde framför mac‑subtabell(1,0). Värdet 'MacTable' från uppräkning {@code QueueItem.CMapEncodingTableType} har ingen mening i detta fall. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | Anger kö av kodningssubtabeller som ska bearbetas. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | Anger subtabell som kommer att användas i företräde framför mac‑subtabell(1,0). Värdet 'MacTable' från uppräkning {@code QueueItem.CMapEncodingTableType} har ingen mening i detta fall. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

Konstruktor. Ställer in standard‑subtabell (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
Konstruktor. Ställer in standard‑subtabell (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

Konstruktör

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| preferredEncodingTable |  | kodningssubtabell som kommer att användas i prioritet framför mac-subtabell(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

Anger kö av kodningssubtabeller som ska bearbetas.

**Returns:**
Kö av QueueItem

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

Anger subtabell som kommer att användas i företräde framför mac‑subtabell(1,0). Värdet 'MacTable' från uppräkning {@code QueueItem.CMapEncodingTableType} har ingen mening i detta fall.

**Returns:**
CMapEncodingTableType-element @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
Anger kö av kodningssubtabeller som ska bearbetas.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

Anger subtabell som kommer att användas i företräde framför mac‑subtabell(1,0). Värdet 'MacTable' från uppräkning {@code QueueItem.CMapEncodingTableType} har ingen mening i detta fall.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | preferredEncodingTable kodningssubtabell som kommer att användas i prioritet framför mac-subtabell(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
