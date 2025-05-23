---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategy-klassen. Denna klass beskriver de regler som kan användas för att justera processen att kopiera kodningsdata i de fall en TrueType-symbolisk font har mer än en kodning.
type: docs
weight: 8330
url: /sv/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## PdfASymbolicFontEncodingStrategy-klassen

Denna klass beskriver de regler som kan användas för att justera kopieringsprocessen av kodningsdata i de fall en TrueType-symbolisk font har mer än en kodning. Vissa PDF-dokument kan efter konvertering till PDF/A-format ge ett felmeddelande "More than one encoding in symbolic TrueType font's cmap". Vad är orsaken till detta fel? Alla TrueType-symboliska typsnitt har en speciell tabell "cmap" i sina interna data. Denna tabell mappar teckenkoder till glyfindikatorer. Och tabellen kan innehålla olika kodningstabeller som beskriver de använda kodningarna. Se avancerad information om cmap-tabeller på https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Vanligtvis innehåller cmap-tabellen flera kodningstabeller, men PDF/A-standarden kräver att antingen ska endast en kodningstabell finnas kvar för detta typsnitt i PDF/A-dokumentet eller så måste det finnas en (3,0)-kodningstabell bland typsnittets tabeller. Och den centrala frågan är – vilken data måste hämtas från de andra tabellerna för att kopieras till destinationskodningstabellen (3,0)? De flesta typsnitt har "välformade" cmap-tabeller där varje kodningstabell är helt konsekvent med de andra tabellerna. Men vissa typsnitt har cmap-tabeller med kollisioner – där en tabell till exempel har glyfindex 100 för unicode 100, medan en annan tabell har glyfindex 200 för samma unicode 100. För att lösa dessa problem krävs en särskild strategi. Som standard används följande strategi: mac-undertabellen (1,0) söks efter. Om denna tabell hittas används endast dess data för att fylla destinations-tabellen (3,0). Om mac-undertabellen inte hittas, itereras alla tabeller utom (3,0) och används för att kopiera data till destinations-undertabellen (3,0). Dessutom kopieras mappningen för varje unicode (unicode, glyfindex) till destinations-tabellen endast om den aktuella destinations-tabellen inte redan innehåller detta unicode. Så, till exempel, om den första undertabellen har glyfindex 100 för unicode 100, och nästa tabell har glyfindex 200 för samma unicode 100, kopieras endast data från den första tabellen (unicode=100, glyfindex = 100). Så att varje tidigare undertabell har företräde framför den senare. Egenskaperna för denna klass `PdfASymbolicFontEncodingStrategy` hjälper till att justera standardbeteendet. Om egenskapen [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) av typen [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) är satt, kommer den relevanta undertabellen att användas före mac-undertabellen (1,0). Värdet 'MacTable' från uppräkningen [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) är meningslöst i detta fall, eftersom det pekar på samma mac-undertabell (1,0) som annars används som standard. Egenskapen [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) tar bort alla prioriteringar för någon undertabell. Om denna egenskap är inställd används endast undertabellerna från den deklarerade kön i angiven ordning. Om de angivna undertabellerna inte hittas, kommer standarditerationen över alla undertabeller samt kopieringsstrategin som beskrivits ovan att användas. Objektet [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) specificerar vilken kodningstabell som används. Denna undertabell kan ställas in via en kombination av medlemmarna (PlatformID, PlatformSpecificId) eller via uppräkningen [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/). Om typsnittet saknar undertabellen (3,0) kommer en annan undertabell att användas för att bibehålla PDF/A-kompatibiliteten. Valet av vilken undertabell som ska användas görs enligt samma regler som beskrivits tidigare, så att egenskaperna [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) och [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) används för att bestämma den resulterande undertabellen, och om typsnittet inte har de begärda undertabellerna används istället en befintlig undertabell.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | Konstruktör. Sätter standardundertabellen (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | Konstruktör |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | Konstruktör |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | Anger kön av kodningstabeller som ska bearbetas. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | Anger den kodningstabell som kommer att användas före mac-undertabellen (1,0). Värdet 'MacTable' från uppräkningen [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) är meningslöst i detta fall. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)