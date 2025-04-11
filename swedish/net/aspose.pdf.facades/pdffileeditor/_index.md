---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditor klass. Implementerar operationer med PDF-fil sammanfogning, uppdelning, extrahering av sidor, skapande av häfte etc.
type: docs
weight: 4460
url: /sv/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor klass

Implementerar operationer med PDF-fil: sammanfogning, uppdelning, extrahering av sidor, skapande av häfte, etc.

```csharp
public sealed class PdfFileEditor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | Standardkonstruktör. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Om den är inställd på true, stängs strömmarna efter operationen. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Antal dokument som sammanfogades innan en ny inkrementell uppdatering gjordes under sammanfogning när UseDiskBuffer är inställt på true. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Hämtar logg över konverteringsprocessen. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Ställer in PDF-filformat. Resultatfilen kommer att sparas i angivet filformat. Om denna egenskap inte anges kommer filen att sparas i standard PDF-format utan konvertering. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Om true, kopieras den logiska strukturen av filen när sammanfogning utförs. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Om true, kommer konturer att kopieras. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Denna egenskap definierar beteendet när sammanfogningen stöter på en korrupt fil. Möjliga värden är: StopWithError och ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Array av problem som uppstod när sammanfogningen utfördes. För varje korrupt dokument från den som passerades till Concatenate() funktionen skapas en ny CorruptedItem post. Denna egenskap kan endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Om true, görs inkrementella uppdateringar under sammanfogning. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Om true kommer åtgärder att kopieras från källdokument. Standardvärde: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Om true kommer fältnamn att göras unika när formulär sammanfogas. Suffix kommer att läggas till fältnamn, suffixmall kan specificeras i egenskapen UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Hämtar den senaste inträffade undantaget. Kan användas för att kontrollera orsaken till felet. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | Valfritt innehåll av sammanfogade dokument med lika namn kommer att slås samman till ett lager i den resulterande dokumentet om denna egenskap är true. Annars kommer lager med lika namn att sparas som olika lager i den resulterande dokumentet. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Om true, slås dubblettkonturer samman. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Hämtar eller ställer in optimeringsflagga. Lika resursströmmar i den resulterande filen slås samman till ett PDF-objekt om denna flagga är inställd. Detta gör att den resulterande filstorleken kan minskas men kan orsaka långsammare exekvering och större minneskrav. Standardvärde: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Ställer in ägarens lösenord om den källinmatade PDF-filen är krypterad. Denna egenskap är ännu inte implementerad. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Om true, tillämpas användarrättigheterna för det första dokumentet på det sammanfogade dokumentet. Användarrättigheterna för alla andra dokument ignoreras. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Om true, kommer alla signaturer att tas bort från fälten (fälten kommer att förbli); annars kan du få ogiltiga signaturer. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Formatet på suffixet som läggs till fältnamnet för att göra det unikt när formulär sammanfogas. Denna sträng måste innehålla %NUM% delsträngen som kommer att ersättas med siffror. Till exempel, om UniqueSuffix = "ABC%NUM%" så kommer fältet "fieldName" namnen att vara: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Om detta alternativ används kommer destinationsdokumentet att sparas på disk periodiskt och vidare sammanfogning kommer att tillämpas på det som inkrementella uppdateringar. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i standard rumsenheter. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i standard rumsenheter. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i procent av den initiala sidstorleken. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Ändrar storlek på sidinnehåll och lägger till angivna marginaler. Marginaler anges i procent av den initiala sidstorleken. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Lägger till sidbrytningar i dokumentets sidor. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Lägger till sidbrytningar i dokumentets sidor. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Lägger till sidbrytningar i dokumentets sidor. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Lägger till sidor, som väljs från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Lägger till sidor, som väljs från array av dokument i portStreams. Den resulterande dokumentet inkluderar firstInputFile och alla portStreams dokument sidor i intervallet startPage till endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Lägger till sidor, som väljs från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Lägger till sidor, som väljs från portFiles dokument. Den resulterande dokumentet inkluderar firstInputFile och alla portFiles dokument sidor i intervallet startPage till endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Sammanfogar dokument. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Sammanfogar filer |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Sammanfogar filer till en fil. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Sammanfogar två filer. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Sammanfogar två filer. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Slår samman två PDF-dokument till ett nytt PDF-dokument med sidor på alternerande sätt och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två PDF-dokumenten kommer att producera det resulterande dokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Slår samman två PDF-dokument till ett nytt PDF-dokument med sidor på alternerande sätt och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två PDF-dokumenten kommer att producera det resulterande dokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Tar bort sidor som anges av nummerarray från indatafilen, sparar som en ny PDF-fil. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Tar bort sidor som anges av nummerarray från indatafilen, sparar som en ny PDF-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Extraherar sidor som anges av nummerarray, sparar som en ny PDF-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Extraherar sidor som anges av nummerarray, sparar som en ny PDF-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Extraherar sidor från indatafilen, sparar som en ny PDF-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Extraherar sidor från indatafilen, sparar som en ny PDF-fil. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Infogar sidor från en annan fil i indata PDF-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Infogar sidor från en annan fil i indata PDF-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Infogar sidor från en annan fil i indata PDF-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Infogar sidor från en annan fil i PDF-filen på en position. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Skapar häfte från InputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Skapar häfte från indatafil till utdatafil. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Skapar häfte från indataflödet och sparar resultatet i utdataflödet. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Skapar häfte från inputFile till outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Skapar anpassat häfte från firstInputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Skapar anpassat häfte från firstInputFile till outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Skapar häfte från firstInputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Skapar anpassat häfte från firstInputFile till outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Skapar N-Up dokument från de två indata PDF-strömmarna till outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Skapar N-Up dokument från de flera indata PDF-strömmarna till outputStream. Varje sida av outputStream kommer att innehålla flera sidor, som är en kombination av sidor i indata strömmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är true och staplas vertikalt om isSidewise är false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Skapar N-Up dokument från de två indata PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla två sidor, en sida är från den första indatafilen och en annan är från den andra indatafilen. De två sidorna staplas horisontellt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Skapar N-Up dokument från de flera indata PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla flera sidor, som är en kombination av sidor i indatafilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är true och staplas vertikalt om isSidewise är false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Skapar N-Up dokument från indataflödet och sparar resultatet i utdataflödet. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Skapar N-Up dokument från firstInputFile till outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Skapar N-Up dokument från den första indataflödet till utdataflödet. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Skapar N-Up dokument från indatafilen till outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Ändrar storlek på sidor i dokumentet. Tomma marginaler läggs till runt den krympta sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Ändrar storlek på sidor i dokumentet. Tomma marginaler läggs till runt den krympta sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Ändrar storlek på innehållet i sidorna i dokumentet. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Ändrar storlek på innehållet i sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standard rumsenheter. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standard rumsenheter. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i procent. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i procent. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Dela från början till angiven plats, och spara den främre delen i utdataflödet. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Dela PDF-filen från första sidan till angiven plats, och spara den främre delen som en ny fil. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Dela PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller fler sidor. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Dela PDF-filen i flera dokument. Dokumenten kan vara enstaka sidor eller fler sidor. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Dela från angiven plats, och spara den bakre delen som en ny filström. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Dela från plats, och spara den bakre delen som en ny fil. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Dela PDF-filen i enstaka sidor. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Dela PDF-filen i enstaka sidor. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Dela PDF-filen i enstaka sidor och spara den i angiven sökväg. Sökvägen specificeras av fältnamnmall. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Dela PDF-filen i enstaka sidor och spara den i angiven sökväg. Sökvägen specificeras av fältnamnmall. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Lägger till sidor, som väljs från array av dokument i portStreams. Den resulterande dokumentet inkluderar firstInputFile och alla portStreams dokument sidor i intervallet startPage till endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Lägger till sidor, som väljs från portFiles dokument. Den resulterande dokumentet inkluderar firstInputFile och alla portFiles dokument sidor i intervallet startPage till endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Sammanfogar dokument. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Sammanfogar filer |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Sammanfogar filer till en fil. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Sammanfogar två filer. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Slår samman två PDF-dokument till ett nytt PDF-dokument med sidor på alternerande sätt och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två PDF-dokumenten kommer att producera det resulterande dokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Slår samman två PDF-dokument till ett nytt PDF-dokument med sidor på alternerande sätt och fyller de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Sammanfogning av de två PDF-dokumenten kommer att producera det resulterande dokumentet med sidor: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Tar bort sidor som anges av nummerarray från indatafilen, sparar som en ny PDF-fil. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Tar bort sidor som anges av nummerarray från indatafilen, sparar som en ny PDF-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Extraherar sidor som anges av nummerarray, sparar som en ny PDF-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Extraherar sidor som anges av nummerarray, sparar som en ny PDF-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Extraherar sidor från indatafilen, sparar som en ny PDF-fil. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Infogar sidor från en annan fil i indata PDF-filen. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Infogar sidor från en annan fil i indata PDF-filen. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Skapar häfte från InputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Skapar häfte från indatafil till utdatafil. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Skapar häfte från indataflödet och sparar resultatet i utdataflödet. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Skapar häfte från inputFile till outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Skapar anpassat häfte från firstInputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Skapar anpassat häfte från firstInputFile till outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Skapar häfte från firstInputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Skapar anpassat häfte från firstInputFile till outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Skapar N-Up dokument från de två indata PDF-strömmarna till outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Skapar N-Up dokument från de flera indata PDF-strömmarna till outputStream. Varje sida av outputStream kommer att innehålla flera sidor, som är en kombination av sidor i indata strömmarna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är true och staplas vertikalt om isSidewise är false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Skapar N-Up dokument från de två indata PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla två sidor, en sida är från den första indatafilen och en annan är från den andra indatafilen. De två sidorna staplas horisontellt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Skapar N-Up dokument från de flera indata PDF-filerna till outputFile. Varje sida av outputFile kommer att innehålla flera sidor, som är en kombination av sidor i indatafilerna med samma sidnummer. De flera sidorna staplas horisontellt om isSidewise är true och staplas vertikalt om isSidewise är false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Skapar N-Up dokument från indataflödet och sparar resultatet i utdataflödet. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Skapar N-Up dokument från firstInputFile till outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Skapar N-Up dokument från den första indataflödet till utdataflödet. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Skapar N-Up dokument från indatafilen till outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Ändrar storlek på innehållet i sidorna i dokumentet. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Ändrar storlek på innehållet i sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Ändrar storlek på innehållet i dokumentets sidor. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standard rumsenheter. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Dela från början till angiven plats, och spara den främre delen i utdataflödet. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Dela PDF-filen från första sidan till angiven plats, och spara den främre delen som en ny fil. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Dela från angiven plats, och spara den bakre delen som en ny filström. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Dela från plats, och spara den bakre delen som en ny fil. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Åtgärd som utförs när en korrupt fil möttes i sammanfogningprocessen. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Klass för att specificera sidstorleksparametrar. Tillåter att ställa in följande parametrar: Storlek på resulterande sida (bredd, höjd) i standard rumsenheter eller i procent av den initiala sidstorleken; Vänster, Topp, Botten och Höger marginaler i standard rumsenheter eller i procent av den initiala sidstorleken; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden kommer att beräknas från resten av sidstorleken efter att de explicit angivna värdena har beräknats. Till exempel: om sidans bredd = 100 och ny sidbredd anges till 60 enheter, då beräknas vänster och höger marginaler automatiskt: (100 - 60) / 2 = 15. Denna klass används i ResizeContents-metoden. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Värde av marginal eller innehållsstorlek specificerat i procent av standard rumsenheter. Denna klass används i ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Klass som tillhandahåller information om korrupta filer under sammanfogning. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Data om sidbrytningsposition. |

### Se även

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)