---
title: PdfFileEditor
second_title: Aspose.PDF för .NET API Referens
description: Implementerar operationer med PDF-fil sammanlänkning dela extrahera sidor göra häften etc.
type: docs
weight: 2470
url: /sv/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Implementerar operationer med PDF-fil: sammanlänkning, dela, extrahera sidor, göra häften, etc.

```csharp
public sealed class PdfFileEditor
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | Hämtar eller ställer in namnet på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | Om satt till sant stängs strömmar efter operation. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | Antal dokument sammanlänkade innan ny inkrementell uppdatering gjordes under sammanlänkning när UseDiskBuffer är satt till true. |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | Hämtar eller ställer in hur innehåll ska lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | Hämtar logg över konverteringsprocessen. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | Ställer in PDF-filformat. Resultatfilen kommer att sparas i angivet filformat. Om den här egenskapen inte anges sparas filen i standard PDF-format utan konvertering. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | Om sant så kopieras filens logiska struktur när sammanlänkning utförs. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | Om sant kommer konturer att kopieras. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | Den här egenskapen definierar beteende när sammanlänkningsprocessen träffade skadad fil. Möjliga värden är: StopWithError och ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | En rad av problem som uppstod när sammanlänkning utfördes. För varje skadat dokument som skickas till Concatenate() skapas -funktionen en ny CorruptedItem-post. Den här egenskapen får endast användas när CorruptedFileAction är ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | Om sant, görs inkrementella uppdateringar under sammanlänkningen. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | Om sanna åtgärder kommer att kopieras från källdokument. Standardvärde: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | Om sant kommer fältnamnen att göras unika när formulär sammanlänkas. Suffix kommer att läggas till fältnamn, suffixmall kan anges i egenskapen UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | Får senast inträffade undantag. Kan användas för att kontrollera orsaken till felet. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | Valfritt innehåll i sammanlänkade dokument med samma namn kommer att slås samman till ett lager i det resulterande dokumentet om den här egenskapen är sann. Annars kommer lager med samma namn att sparas som olika lager i det resulterande dokumentet. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | Om sant, slås dubbletter av konturer samman. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | Hämtar eller ställer in optimeringsflagga. Lika resursströmmar i den resulterande filen slås samman till ett PDF-objekt om denna flagga är inställd. Detta gör det möjligt att minska den resulterande filstorleken men kan orsaka långsammare exekvering och större minneskrav. Standardvärde: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | Ställer in ägarens lösenord om källindata-PDF-filen är krypterad. Den här egenskapen är inte implementerad ännu. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | Om sant, tillämpas användarrättigheterna för det första dokumentet på sammanlänkade dokument. Användarrättigheter för alla andra dokument ignoreras. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | Om sant, kommer alla signaturer att tas bort från fält (fält kommer att finnas kvar); annars kan du få ogiltiga signaturer. |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | Hämtar eller ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | Format för suffixet som läggs till i fältnamnet för att göra det unikt när formulär sammanlänkas. Denna sträng måste innehålla %NUM% delsträng som kommer att ersättas med siffror. Till exempel om UniqueSuffix = "ABC%NUM%" då för fält "fieldName" namn kommer att vara: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | Om detta alternativ används kommer måldokumentet att sparas på disken med jämna mellanrum och ytterligare sammanfogning kommer att tillämpas på det som inkrementella uppdateringar. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. Marginaler anges i standardutrymmesenheter. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | Ändrar storlek på sidinnehåll och lägger till specificerade marginaler. Marginaler anges i standardutrymmesenheter. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Ändrar storlek på sidinnehåll och lägg till specificerade marginaler. Marginaler anges i procent av den ursprungliga sidstorleken. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | Ändrar storlek på sidinnehåll och lägg till specificerade marginaler. Marginaler anges i procent av den ursprungliga sidstorleken. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | Lägger till sidbrytningar på dokumentsidor. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | Lägger till sidbrytningar på dokumentsidor. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | Lägger till sidbrytningar på dokumentsidor. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | Lägger till sidor, som är valda från portStream inom intervallet från startPage till endPage, i portStream i slutet av firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | Lägger till dokument till källdokument och sparar resultatet i svarsobjekt. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | Lägger till sidor, som väljs från en mängd dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams dokumentsidor i intervallet startPage to endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | Lägger till sidor, som är valda från portFile inom intervallet från startPage till endPage, i portFile i slutet av firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | Lägger till dokument till källdokument och sparar resultatet i HttpResponse-objekt. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | Lägger till sidor som är valda från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentsidor i intervallet startPage to endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | Sammanfogar dokument. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | Sammanfogar filer och lagrar resultat till HttpResponse-objekt. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | Sammanfogar filer |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | Sammanfogar filer och sparar reslt i HttpResposnse-objekt. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | Sammanfogar filer till en fil. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | Sammanfogar två filer. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | Sammanfogar två filer. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor på alternativa sätt och fyll de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Genom att slå samman de två PDF-dokumenten skapas resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blanksida, p5, blanksida . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor på alternativa sätt och fyll de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Genom att slå samman de två PDF-dokumenten skapas resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blanksida, p5, blanksida . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | Tar bort angivna sidor från dokument och sparar resultatet i HttpResponse-objekt. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | Tar bort sidor specificerade av nummermatris från inmatningsfilen, sparar som en ny pdf-fil. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | Tar bort specificerade sidor från dokument och lagrar resultatet till HttpResponse-objekt. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | Tar bort sidor specificerade av nummermatris från inmatningsfilen, sparar som en ny pdf-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | Extraherar specificerade sidor från källfilen och lagrar resultatet i HttpResponse-objekt. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | Extraherar sidor specificerade av nummermatris, sparar som en ny pdf-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | Extraherar specificerade sidor från källfilen och lagrar resultatet i HttpResponse-objekt. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | Extraherar sidor specificerade av nummermatris, sparar som en ny PDF-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | Extraherar sidor från indatafilen, sparar som en ny pdf-fil. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | Extraherar sidor från indatafilen, sparar som en ny pdf-fil. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | Infogar dokument i annat dokument och lagrar resultatet i svarsobjekt. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | Infogar sidor från en annan fil i indata-Pdf-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | Infogar innehållet i filen i källfilen och lagrar resultatet i HttpResponse-objektet. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | Infogar sidor från en annan fil i indata-Pdf-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | Infogar sidor från en annan fil i indata-Pdf-filen. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | Infogar sidor från en annan fil i Pdf-filen på en plats. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | Gör häfte från InputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | Gör häfte från indatafilen till utdatafilen. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | Gör häfte från källfil och lagrar resultatet i HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | Gör häfte från ingångsströmmen och sparar resultatet i utmatningsström. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | Gör häfte från källfil och lagrar resultat i HttpResponse-objekt. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | Gör häfte från inputFile till outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | Gör ett anpassat häfte från firstInputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | Gör ett anpassat häfte från firstInputFile till outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Skapa häfte från PDF-fil och lagra den i HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Gör häfte från firstInputStream till outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Gör häfte från källfil och lagrar resultat i HttpResponse-objekt. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | Gör ett anpassat häfte från firstInputFile till outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | Gör N-Up-dokument från de två ingående PDF-strömmarna till outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | Gör N-Up-dokument från PDF-strömmarna med flera indata till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, som är kombinationer med sidorna i inmatningsströmmarna med samma sidnummer. Flera sidor staplade upp horisontellt om isSidewise är sant och staplade upp vertikalt om isSidewise är falskt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | Gör N-Up-dokument från de två inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida är från den första inmatningsfilen och en annan är från den andra inmatningsfilen. De två sidorna är staplade horisontellt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | Gör N-Up-dokument från PDF-filer med flera indata till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, som är kombination med sidorna i inmatningsfilerna med samma sidnummer. Flera sidor staplade upp horisontellt om isSidewise är sant och staplade upp vertikalt om isSidewise är falskt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | Gör N-up-dokument och lagrar resultatet i HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i utdataström. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | Gör N-up-dokument och lagrar resultatet i HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | Gör N-Up-dokument från den första InputFile till outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | Gör N-up-dokument och lagrar resultatet i HttpResponse-objekt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | Gör N-Up-dokument från den första ingångsströmmen till utdataström. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | Gör N-up-dokument och lagrar resultatet i HttpResponse-objekt. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | Gör N-Up-dokument från indatafilen till outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | Ändrar storlek på dokumentsidor. Tomma marginaler läggs till runt den krympta sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | Ändrar storlek på dokumentsidor. Tomma marginaler läggs till runt den krympta sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Ändrar storleken på innehållet på sidorna i dokumentet. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | Ändrar storleken på innehållet på dokumentsidorna. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardutrymmesenheter. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | Ändrar storleken på innehållet på dokumentsidorna. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardutrymmesenheter. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | Ändrar storleken på innehållet på dokumentsidorna. Krymper sidans innehåll och lägger till marginaler. Ny innehållsstorlek anges i procent. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | Ändrar storleken på innehållet på dokumentsidorna. Krymper sidans innehåll och lägger till marginaler. Ny innehållsstorlek anges i procent. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | Delar dokument från start till angiven plats och lagrar resultatet i HttpResponse-objekt. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | Delar från start till angiven plats och sparar den främre delen i output Stream. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | Delar dokument från första sida till plats och sparar resultatet i HttpResponse-objekt. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | Delar Pdf-fil från första sidan till angiven plats och sparar den främre delen som en ny fil. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | Delar upp Pdf-filen i flera dokument. Dokumenten kan vara ensidiga eller flera sidor. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | Delar upp Pdf-filen i flera dokument. Dokumenten kan vara ensidiga eller flera sidor. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | Delas från angiven plats och sparar den bakre delen i HttpResponse-objekt. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | Delas från angiven plats och sparar den bakre delen som en ny fil Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | Delas från angiven plats och sparar den bakre delen i HttpResponse-objekt. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | Delas från plats och sparar den bakre delen som en ny fil. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | Delar upp Pdf-filen i ensidiga dokument. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | Delar upp PDF-filen i ensidiga dokument. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | Dela upp Pdf-filen i ensidiga dokument och spara den i en angiven sökväg. Sökvägen är specificerad av fältnamnet temaplate. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | Dela upp Pdf-filen i ensidiga dokument och spara den i en angiven sökväg. Sökvägen är specificerad av fältnamnet temaplate. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | Lägger till dokument till källdokument och sparar resultatet i svarsobjekt. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | Lägger till sidor, som väljs från en mängd dokument i portStreams. Resultatdokumentet inkluderar firstInputFile och alla portStreams dokumentsidor i intervallet startPage to endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | Lägger till dokument till källdokument och sparar resultatet i HttpResponse-objekt. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | Lägger till sidor som är valda från portFiles-dokument. Resultatdokumentet inkluderar firstInputFile och alla portFiles-dokumentsidor i intervallet startPage to endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | Sammanfogar dokument. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | Sammanfogar filer och lagrar resultat till HttpResponse-objekt. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | Sammanfogar filer |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | Sammanfogar filer och sparar reslt i HttpResposnse-objekt. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | Sammanfogar filer till en fil. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | Sammanfogar två filer. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor på alternativa sätt och fyll de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Genom att slå samman de två PDF-dokumenten skapas resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blanksida, p5, blanksida . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | Slår samman två Pdf-dokument till ett nytt Pdf-dokument med sidor på alternativa sätt och fyll de tomma platserna med tomma sidor. t.ex.: dokument1 har 5 sidor: p1, p2, p3, p4, p5. dokument2 har 3 sidor: p1', p2', p3'. Genom att slå samman de två PDF-dokumenten skapas resultatdokumentet med sidor:p1, p1', p2, p2', p3, p3', p4, blanksida, p5, blanksida . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | Tar bort angivna sidor från dokument och sparar resultatet i HttpResponse-objekt. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | Tar bort sidor specificerade av nummermatris från inmatningsfilen, sparar som en ny pdf-fil. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | Tar bort specificerade sidor från dokument och lagrar resultatet till HttpResponse-objekt. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | Tar bort sidor specificerade av nummermatris från inmatningsfilen, sparar som en ny pdf-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | Extraherar specificerade sidor från källfilen och lagrar resultatet i HttpResponse-objekt. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | Extraherar sidor specificerade av nummermatris, sparar som en ny pdf-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | Extraherar specificerade sidor från källfilen och lagrar resultatet i HttpResponse-objekt. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | Extraherar sidor specificerade av nummermatris, sparar som en ny PDF-fil. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | Extraherar sidor från indatafilen, sparar som en ny pdf-fil. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | Infogar dokument i annat dokument och lagrar resultatet i svarsobjekt. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | Infogar sidor från en annan fil i indata-Pdf-filen. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | Infogar innehållet i filen i källfilen och lagrar resultatet i HttpResponse-objektet. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | Infogar sidor från en annan fil i indata-Pdf-filen. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | Gör häfte från InputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | Gör häfte från indatafilen till utdatafil. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | Gör häfte från källfil och lagrar resultatet i HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | Gör häfte från ingångsströmmen och sparar resultatet i utmatningsström. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | Gör häfte från källfil och lagrar resultat i HttpResponse-objekt. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | Gör häfte från inputFile till outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | Gör ett anpassat häfte från firstInputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | Gör ett anpassat häfte från firstInputFile till outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Skapa häfte från PDF-fil och lagra den i HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Gör häfte från firstInputStream till outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Gör häfte från källfil och lagrar resultat i HttpResponse-objekt. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | Gör ett anpassat häfte från firstInputFile till outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | Gör N-Up-dokument från de två ingående PDF-strömmarna till outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | Gör N-Up-dokument från PDF-strömmarna med flera indata till outputStream. Varje sida i outputStream kommer att innehålla flera sidor, som är kombinationer med sidorna i inmatningsströmmarna med samma sidnummer. Flera sidor staplade upp horisontellt om isSidewise är sant och staplade upp vertikalt om isSidewise är falskt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | Gör N-Up-dokument från de två inmatade PDF-filerna till outputFile. Varje sida i outputFile kommer att innehålla två sidor, en sida är från den första inmatningsfilen och en annan är från den andra inmatningsfilen. De två sidorna är staplade horisontellt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | Gör N-Up-dokument från PDF-filer med flera indata till outputFile. Varje sida i outputFile kommer att innehålla flera sidor, som är kombination med sidorna i inmatningsfilerna med samma sidnummer. Flera sidor staplade upp horisontellt om isSidewise är sant och staplade upp vertikalt om isSidewise är falskt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | Gör N-up-dokument och lagrar resultatet i HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | Skapar N-Up-dokument från inmatningsströmmen och sparar resultatet i utdataström. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | Gör N-up-dokument och lagrar resultatet i HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | Gör N-Up-dokument från den första InputFile till outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | Gör N-up-dokument och lagrar resultatet i HttpResponse-objekt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | Gör N-Up-dokument från den första ingångsströmmen till utdataström. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | Gör N-up-dokument och lagrar resultatet i HttpResponse-objekt. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | Gör N-Up-dokument från indatafilen till outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Ändrar storleken på innehållet på sidorna i dokumentet. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. Resultatet lagras i HttpResponse-objektet. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | Ändrar storleken på innehållet på sidorna i dokumentet. Om sidan krymps läggs tomma marginaler till runt sidan. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | Ändrar storleken på innehållet på dokumentsidorna. Krymper innehållet på sidan och lägger till marginaler. Ny storlek på innehållet anges i standardutrymmesenheter. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | Delar dokument från start till angiven plats och lagrar resultatet i HttpResponse-objekt. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | Delar från start till angiven plats och sparar den främre delen i output Stream. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | Delar dokument från första sida till plats och sparar resultatet i HttpResponse-objekt. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | Delar Pdf-fil från första sidan till angiven plats och sparar den främre delen som en ny fil. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | Delas från angiven plats och sparar den bakre delen i HttpResponse-objekt. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | Delas från angiven plats och sparar den bakre delen som en ny fil Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | Delas från angiven plats och sparar den bakre delen i HttpResponse-objekt. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | Delas från plats och sparar den bakre delen som en ny fil. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | Åtgärden utfördes när skadad fil uppfylldes i sammankopplingsprocessen. |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | Klass för att ange parametrar för sidstorleksändring. Tillåt att ställa in följande parametrar: Storlek på resultatsida (bredd, höjd) i standardutrymmesenheter eller i procent av initial sidstorlek; Vänster-, topp-, botten- och högermarginaler i standardutrymmesenheter eller i procent av den ursprungliga sidstorleken; Vissa värden kan lämnas null för automatisk beräkning. Dessa värden kommer att beräknas från resten av sidstorleken efter beräkning explicit angivna värden. Till exempel: om sidbredd = 100 och ny sidbredd specificeras 60 enheter så beräknas vänster och höger marginaler automatiskt: (100) - . 2 = 15. Denna klass används i metoden ResizeContents. |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | Värdet på marginalen eller innehållsstorleken specificerad i procent av standardutrymmesenheter. Den här klassen används i ContentsResizeParameters. |
| class [CorruptedItem](pdffileeditor.corrupteditem) | Klass som ger information om skadade filer i tid för sammanlänkning. |
| class [PageBreak](pdffileeditor.pagebreak) | Data för sidbrytningsposition. |

### Se även

* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
