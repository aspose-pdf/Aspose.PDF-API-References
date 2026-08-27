---
title: "Klass PdfFileEditor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileEditor-klass. Implementerar operationer med PDF-filkonkatenering, delning, extrahering av sidor, skapande av häften etc."
type: docs
weight: 4580
url: /sv/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Implementerar operationer med PDF file: sammanslagning, delning, extrahering av sidor, skapa häfte, etc.

```csharp
public sealed class PdfFileEditor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Om den är satt till true stängs strömmar efter operationen. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Antal dokument som konkateneras innan en ny inkrementell uppdatering gjordes under konkateneringen när UseDiskBuffer är satt till true. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Hämtar logg för konverteringsprocessen. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Ställer in PDF-filformat. Resultatfilen sparas i angivet filformat. Om denna egenskap inte anges sparas filen i standard PDF-format utan konvertering. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Om true kopieras den logiska strukturen i filen när konkatenering utförs. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Om true kopieras konturerna. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Denna egenskap definierar beteendet när konkateneringsprocessen stöter på en korrupt fil. Möjliga värden är: StopWithError och ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Array av påträffade problem när konkatenering utfördes. För varje korrupt dokument som skickas till Concatenate()-funktionen skapas en ny CorruptedItem-post. Denna egenskap kan endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Om true görs inkrementella uppdateringar under konkateneringen. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Om true kopieras åtgärder från källdokumenten. Standardvärde: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Om true görs fältnamn unika när formulär konkateneras. Suffix läggs till fältnamnen, suffixmall kan specificeras i egenskapen UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Hämtar det senaste undantaget. Kan användas för att kontrollera orsaken till felet. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | Valfritt innehåll i konkatenerade dokument med samma namn kommer att slås ihop till ett lager i det resulterande dokumentet om denna egenskap är true. Annars sparas lager med samma namn som olika lager i det resulterande dokumentet. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Om true slås dubblettkonturer ihop. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Hämtar eller anger optimeringsflagga. Likadana resursströmmar i den resulterande filen slås ihop till ett PDF‑objekt om flaggan är satt. Detta minskar filens storlek men kan leda till långsammare körning och högre minneskrav. Standardvärde: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Ställer in ägarens lösenord om käll-Pdf-filen är krypterad. Denna egenskap är ännu inte implementerad. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Om true tillämpas användarrättigheterna från det första dokumentet på det konkatenerade dokumentet. Användarrättigheterna för alla andra dokument ignoreras. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Om true tas alla signaturer bort från fält (fälten kvarstår); annars kan du få ogiltiga signaturer. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Formatet för suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla %NUM%-delsträngen som kommer att ersättas med siffror. Till exempel om UniqueSuffix = \"ABC%NUM%\" så blir fältnamnen för \"fieldName\": fieldNameABC1, fieldNameABC2, fieldNameABC3 osv. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Om detta alternativ används sparas destinationsdokumentet på disken periodiskt och vidare sammanslagning kommer att tillämpas på det som inkrementella uppdateringar. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna specificeras i standardenheterna för utrymme. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna specificeras i standardenheterna för utrymme. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna specificeras i procent av den ursprungliga sidstorleken. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Ändrar storlek på sidinnehållet och lägger till angivna marginaler. Marginalerna specificeras i procent av den ursprungliga sidstorleken. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Lägger till sidbrytningar i dokumentets sidor. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Lägger till sidbrytningar i dokumentets sidor. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Lägger till sidbrytningar i dokumentets sidor. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Lägger till sidor, som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Lägger till sidor, som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams-dokumentens sidor i intervallet startPage till endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Lägger till sidor, som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Lägger till sidor, som väljs från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentens sidor i intervallet startPage till endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Sammanfogar dokument. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Sammanfogar filer |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Sammanfogar filer till en fil. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Sammanfogar två filer. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Sammanfogar två filer. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: document1 har 5 sidor: p1, p2, p3, p4, p5. document2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten ger resultatdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: document1 har 5 sidor: p1, p2, p3, p4, p5. document2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten ger resultatdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Tar bort sidor som anges av en nummerarray från inmatningsfilen och sparar som en ny Pdf-fil. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Tar bort sidor som anges av en nummerarray från inmatningsfilen och sparar som en ny Pdf-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Extraherar sidor som anges av en nummerarray och sparar som en ny Pdf-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Extraherar sidor som anges av en nummerarray och sparar som en ny PDF-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Extraherar sidor från inmatningsfilen och sparar som en ny Pdf-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Extraherar sidor från inmatningsfilen och sparar som en ny Pdf-fil. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Infogar sidor från en annan fil i inmatnings-Pdf-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Infogar sidor från en annan fil i inmatnings-Pdf-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Infogar sidor från en annan fil i inmatnings-Pdf-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Infogar sidor från en annan fil i Pdf-filen på en position. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Skapar häfte från InputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Skapar häfte från indatafilen till utdatafilen. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Skapar häfte från indataströmmen och sparar resultatet i output stream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Skapar häfte från inputFile till outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Skapar anpassat häfte från firstInputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Skapar anpassad häfte från firstInputFile till outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Skapar häfte från firstInputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Skapar anpassad häfte från firstInputFile till outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Skapar N-Up-dokument från de två inmatade PDF-strömmarna till outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Skapar N-Up-dokument från de flera inmatade PDF-strömmarna till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, vilka är en kombination av sidor i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Skapar N-Up-dokument från de två inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida från den första inmatningsfilen och en annan från den andra inmatningsfilen. De två sidorna staplas horisontellt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Skapar N-Up-dokument från de flera inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, vilka är en kombination av sidor i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Skapar N-Up-dokument från firstInputFile till outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Skapar N-Up-dokument från den första inmatningsströmmen till output stream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Skapar N-Up-dokument från inmatningsfilen till outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Ändrar storlek på dokumentets sidor. Tomma marginaler läggs till runt den krympade sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Ändrar storlek på dokumentets sidor. Tomma marginaler läggs till runt den krympade sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Ändrar storlek på innehållet i dokumentets sidor. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Ändrar storlek på innehållet i dokumentets sidor. Om en sida är krympad läggs tomma marginaler till runt sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny innehållsstorlek anges i procent. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny innehållsstorlek anges i procent. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Delar från början till angiven plats och sparar den främre delen i output Stream. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Delar Pdf-filen från första sidan till angiven plats och sparar den främre delen som en ny fil. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Delar Pdf-filen i flera dokument. Dokumenten kan vara enkelsidiga eller flersidiga. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Delar Pdf-filen i flera dokument. Dokumenten kan vara enkelsidiga eller flersidiga. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Delar från angiven plats och sparar den bakre delen som en ny fil Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Delar från plats och sparar den bakre delen som en ny fil. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Delar Pdf-filen i enkelsidiga dokument. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Delar PDF-filen i enkelsidiga dokument. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Dela Pdf-filen i enkelsidiga dokument och spara den i angiven sökväg. Sökvägen anges av fältet namn temaplate. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Dela Pdf-filen i enkelsidiga dokument och spara den i angiven sökväg. Sökvägen anges av fältet namn temaplate. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Lägger till sidor, som väljs från en array av dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams-dokumentens sidor i intervallet startPage till endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Lägger till sidor, som väljs från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentens sidor i intervallet startPage till endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Sammanfogar dokument. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Sammanfogar filer |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Sammanfogar filer till en fil. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Sammanfogar två filer. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: document1 har 5 sidor: p1, p2, p3, p4, p5. document2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten ger resultatdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor i alternerande ordning och fyller de tomma platserna med tomma sidor. t.ex.: document1 har 5 sidor: p1, p2, p3, p4, p5. document2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två Pdf-dokumenten ger resultatdokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Tar bort sidor som anges av en nummerarray från inmatningsfilen och sparar som en ny Pdf-fil. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Tar bort sidor som anges av en nummerarray från inmatningsfilen och sparar som en ny Pdf-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Extraherar sidor som anges av en nummerarray och sparar som en ny Pdf-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Extraherar sidor som anges av en nummerarray och sparar som en ny PDF-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Extraherar sidor från inmatningsfilen och sparar som en ny Pdf-fil. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Infogar sidor från en annan fil i inmatnings-Pdf-filen. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Infogar sidor från en annan fil i inmatnings-Pdf-filen. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Skapar häfte från InputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Skapar häfte från indatafilen till utdatafilen. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Skapar häfte från indataströmmen och sparar resultatet i output stream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Skapar häfte från inputFile till outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Skapar anpassat häfte från firstInputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Skapar anpassad häfte från firstInputFile till outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Skapar häfte från firstInputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Skapar anpassad häfte från firstInputFile till outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Skapar N-Up-dokument från de två inmatade PDF-strömmarna till outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Skapar N-Up-dokument från de flera inmatade PDF-strömmarna till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, vilka är en kombination av sidor i inmatningsströmmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Skapar N-Up-dokument från de två inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida från den första inmatningsfilen och en annan från den andra inmatningsfilen. De två sidorna staplas horisontellt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Skapar N-Up-dokument från de flera inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, vilka är en kombination av sidor i inmatningsfilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är sant och staplas vertikalt om isSidewise är falskt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i output stream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Skapar N-Up-dokument från firstInputFile till outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Skapar N-Up-dokument från den första inmatningsströmmen till output stream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Skapar N-Up-dokument från inmatningsfilen till outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Ändrar storlek på innehållet i dokumentets sidor. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Ändrar storlek på innehållet i dokumentets sidor. Om en sida är krympad läggs tomma marginaler till runt sidan. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Ändrar storlek på dokumentets sidinnehåll. Krymper sidinnehållet och lägger till marginaler. Ny storlek på innehållet anges i standardenhetsmått. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Delar från början till angiven plats och sparar den främre delen i output Stream. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Delar Pdf-filen från första sidan till angiven plats och sparar den främre delen som en ny fil. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Delar från angiven plats och sparar den bakre delen som en ny fil Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Delar från plats och sparar den bakre delen som en ny fil. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Åtgärd som utförs när en korrupt fil påträffas i sammanslagningsprocessen. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Klass för att specificera sidändringsparametrar. Tillåter att ange följande parametrar: Storlek på resultatsidan (bredd, höjd) i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vänster, topp, botten och höger marginaler i standardenhetsmått eller i procent av den ursprungliga sidans storlek; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden beräknas från återstående sidstorlek efter att uttryckligen angivna värden har beräknats. Till exempel: om sidbredd = 100 och ny sidbredd anges till 60 enheter, beräknas vänster- och högermarginalerna automatiskt: (100 - 60) / 2 = 15. Denna klass används i metoden ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Värde för marginal eller innehållsstorlek angivet i procent av standardrymdsenheter. Denna klass används i ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Klass som tillhandahåller information om korrupta filer vid sammanslagning. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Data för sidbrytningsposition. |

### Se även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


