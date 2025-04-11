---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Document klass. Klass som representerar PDF-dokument
type: docs
weight: 3780
url: /sv/net/aspose.pdf/document/
---
## Dokumentklass

Klass som representerar PDF-dokument.

```csharp
public sealed class Document : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Document](document/#constructor)() | Initierar ett tomt dokument. |
| [Document](document/#constructor_1)(PdfVersion) | Initierar ett tomt dokument efter version. |
| [Document](document/#constructor_2)(Stream) | Initierar en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_7)(string) | Initierar bara Document med *filnamn*. Samma som [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | Initierar en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Öppnar ett befintligt dokument från en ström och tillhandahåller nödvändig konvertering för att få PDF-dokument. |
| [Document](document/#constructor_5)(Stream, string) | Initierar en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_9)(string, bool) | Initierar bara Document med *filnamn*. Samma som [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | Öppnar ett befintligt dokument från en fil och tillhandahåller nödvändiga konverteringsalternativ för att få PDF-dokument. |
| [Document](document/#constructor_10)(string, string) | Initierar en ny instans av `Document`-klassen för att arbeta med krypterade dokument. |
| [Document](document/#constructor_6)(Stream, string, bool) | Initierar en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_11)(string, string, bool) | Initierar en ny instans av `Document`-klassen för att arbeta med krypterade dokument. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Hämtar dokumentåtgärder. Denna egenskap är en instans av DocumentActions-klassen som tillåter att hämta/ange BeforClosing, BeforSaving, etc. åtgärder. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Tillåter att slå samman sidinnehåll för att optimera dokumentstorlek. Om den används kan olika men duplicerade sidor referera till samma innehållsobjekt. Observera att detta läge kan orsaka biverkningar som att ändra sidinnehåll när en annan sida ändras. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Hämtar eller ställer in bakgrundsfärgen för dokumentet. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Hämtar eller ställer in flaggan som specificerar om dokumentfönstrets position ska centreras på skärmen. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Hämtar samlingen av dokument. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Hämtar säkerhetsinställningar om dokumentet är krypterat. Om dokumentet inte är krypterat kommer motsvarande undantag att utlösas i .net 1.1 eller CryptoAlgorithm kommer att vara null för andra .net-versioner. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Hämtar samlingen av destinationer. Föråldrad. Använd vänligen NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Hämtar eller ställer in läsordningen för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Många operationer med typsnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta typsnitt. Till exempel kan vissa typsnitt inte bäddas in i PDF-dokument om licensreglerna inaktiverar inbäddning för detta typsnitt. Denna flagga används för att inaktivera eventuella licensbegränsningar för alla typsnitt i det aktuella PDF-dokumentet. Var försiktig när du använder denna flagga. När den är inställd betyder det att personen som ställer in denna flagga tar allt ansvar för eventuella licens-/lagöverträdelser på sig själv. Så han tar det på egen risk. Det rekommenderas starkt att använda denna flagga endast när du är helt säker på att du inte bryter mot upphovsrättslagen. Som standard falskt. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Hämtar eller ställer in flaggan som specificerar om dokumentets fönstertitelrad ska visa dokumenttiteln. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Hämtar eller ställer in alternativet för hantering av utskrifts duplexläge som ska användas när filen skrivs ut från utskriftsdialogen. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Hämtar samlingen av filer som är inbäddade i dokumentet. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Egenskap som deklarerar att dokumentet måste bädda in alla standard Type1-typsnitt som har flaggan IsEmbedded inställd på true. Alla PDF-typsnitt kan bäddas in i dokumentet helt enkelt genom att ställa in flaggan IsEmbedded på true, men PDF-standard Type1-typsnitt är ett undantag från denna regel. Inbäddning av standard Type1-typsnitt kräver mycket tid, så för att bädda in dessa typsnitt är det nödvändigt att inte bara ställa in flaggan IsEmbedded på true för det angivna typsnittet utan också ställa in en ytterligare flagga på dokumentnivå - EmbedStandardFonts = true; Denna egenskap kan endast ställas in en gång för alla typsnitt. Som standard falskt. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Hämtar eller ställer in flaggan som gör att dokumentet delvis kan laddas ur minnet. Detta gör att minnesanvändningen kan minskas men kan ha negativ effekt på prestanda. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Hämtar eller ställer in flaggan för att hantera sanering av signaturfält. Aktiverad som standard. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Namnet på PDF-filen som orsakade detta dokument |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Hämtar eller ställer in flaggan som specificerar om dokumentfönstret ska ändras för att passa den första visade sidan. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | IDocumentFontUtilities-instans |
| [Form](../../aspose.pdf/document/form/) { get; } | Hämtar Acro Form av dokumentet. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Utlöser undantag om dokumentet kommer att sparas med ändringar och har signatur |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Hämtar eller ställer in flaggan som specificerar om menyraden ska döljas när dokumentet är aktivt. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Hämtar eller ställer in flaggan som specificerar om verktygsfältet ska döljas när dokumentet är aktivt. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Hämtar eller ställer in flaggan som specificerar om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [Id](../../aspose.pdf/document/id/) { get; } | Hämtar ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Hämtar eller ställer in flaggan för att ignorera fel i källfiler. När sidor från källdokumentet kopieras till destinationsdokumentet stoppas kopieringsprocessen med ett undantag om vissa objekt i källfilerna är korrupta när denna flagga är falsk. exempel: dest.Pages.Add(src.Pages); Om denna flagga är inställd på true kommer korrupta objekt att ersättas med tomma värden. Som standard: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Hämtar dokumentinformation. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Hämtar den krypterade statusen för dokumentet. Sant om dokumentet är krypterat. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om dokumentet är linjäriserat. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Hämtar om dokumentet är pdfa-kompatibelt. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Hämtar om dokumentet är pdfua-kompatibelt. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Hämtar eller ställer in om dokumentet är pdfa-kompatibelt. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Samling av JavaScript på dokumentnivå. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Hämtar den logiska strukturen för dokumentet. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Dokumentmetadata. (Ett PDF-dokument kan inkludera allmän information, såsom dokumentets titel, författare och skapelse- och ändringsdatum. Sådan global information om dokumentet (till skillnad från dess innehåll eller struktur) kallas metadata och är avsedd att hjälpa till med katalogisering och sökning efter dokument i externa databaser.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Samling av namngivna destinationer i dokumentet. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Hämtar eller ställer in sidläge, som specificerar hur dokumentet ska visas när det lämnar helskärmsläge. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Hämtar eller ställer in åtgärden som utförs vid dokumentöppning. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Hämtar eller ställer in optimeringsflaggan. När sidor läggs till dokumentet slås lika resursströmmar i den resulterande filen samman till ett PDF-objekt om denna flagga är inställd. Detta gör att den resulterande filstorleken kan minskas men kan orsaka långsammare exekvering och större minneskrav. Standardvärde: falskt. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Hämtar dokumentets innehåll. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Hämtar samlingen av utdataintentioner i dokumentet. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Hämtar eller ställer in sidinformationen. (endast för generator, inte ifyllt när dokumentet läses) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Hämtar sidetiketter i dokumentet. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Hämtar eller ställer in sidlayout som ska användas när dokumentet öppnas. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Hämtar eller ställer in sidläge, som specificerar hur dokumentet ska visas när det öppnas. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Hämtar eller ställer in samlingen av dokumentets sidor. Observera att sidor numreras från 1 i samlingen. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Hämtar PDF-format |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Hämtar behörigheterna för dokumentet. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Hämtar eller ställer in en flagga som specificerar om PDF-sidstorleken ska användas för att välja pappersfacket för inmatning. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Hämtar eller ställer in sidskalningsalternativet som ska väljas när en utskriftsdialog visas för detta dokument. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Hämtar åtkomst till TaggedPdf-innehåll. |
| [Version](../../aspose.pdf/document/version/) { get; } | Hämtar en version av PDF från PDF-filhuvudet. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Hämtar och ställer in filstorleksgränsen för att ladda en hel fil i minnet. Värdet anges i megabyte. Standardvärdet är 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Hämtar licensstatus för systemet. Returnerar sant om systemet fungerar i licensierat läge och falskt annars. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Slår samman dokument. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Slår samman PDF-filer. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Slår samman dokument. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Slår samman dokument. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Binder XML till dokumentet |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Binder XML till dokumentet |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Binder XML/XSL till dokumentet |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Binder XML/XSL till dokumentet |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Binder XML/XSL till dokumentet |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Ändrar dokumentets lösenord. Denna åtgärd kan endast utföras med ägarens lösenord. |
| [Check](../../aspose.pdf/document/check/)(bool) | Validerar dokumentet. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Konverterar dokumentet med angivna konverteringsalternativ |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Känner igen bilder i dokumentet och lägger till hocr-strängar över det. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Känner igen bilder i dokumentet och lägger till hocr-strängar över det. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Konverterar dokumentet och sparar fel i den angivna strömmen. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Konverterar dokumentet och sparar fel i den angivna filen. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Konverterar dokumentet genom att tillämpa Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Konverterar dokumentet genom att tillämpa Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konverterar dokumentet och sparar fel i den angivna filen. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konverterar dokumentet och sparar fel i den angivna filen. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Konverterar sidan till PNG för DSR, OMR, OCR bildström. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Dekrypterar dokumentet. Anropa sedan Spara för att få den dekrypterade versionen av dokumentet. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Stänger alla resurser som används av detta dokument. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Krypterar dokumentet. Anropa sedan Spara för att få den krypterade versionen av dokumentet. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Krypterar dokumentet. Anropa sedan Spara för att få den krypterade versionen av dokumentet. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Krypterar dokumentet. Anropa sedan Spara för att få den krypterade versionen av dokumentet. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Exporterar alla dokumentanoteringar till ström. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Exporterar alla dokumentanoteringar till XFDF-fil |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Tar bort alla fält från dokumentet och placerar deras värden istället. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Tar bort alla fält (och anteckningar) från dokumentet och placerar deras värden istället. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Ersätter transparent innehåll med icke-transparent raster- och vektorgrafik. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Rensar minnet |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Returnerar objektvärde från katalogordlistan. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Hämtar ett objekt med angivet ID i dokumentet. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Hämtar XMP-metadata från dokumentet. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Kontrollerar om det aktuella PDF-dokumentet har sparats med inkrementella uppdateringar. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importerar anteckningar från ström till dokumentet. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importerar anteckningar från XFDF-fil till dokumentet. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Kontrollerar om dokumentet kräver anrop av reparationsmetoden. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Laddar en fil och konverterar den till PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Slår samman dokument. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Slår samman PDF-filer. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Slår samman dokument. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Slår samman dokument. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linjäriserar dokumentet för att - öppna den första sidan så snabbt som möjligt; - visa nästa sida eller följa en länk till nästa sida så snabbt som möjligt; - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara datan först); - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats. Att anropa denna metod sparar faktiskt inte dokumentet. Tvärtom förbereds dokumentet bara för att ha en optimerad struktur, anropa sedan Spara för att få det optimerade dokumentet. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Optimera resurser i dokumentet: 1. Resurser som inte används på dokumentets sidor tas bort; 2. Lika resurser slås samman till ett objekt; 3. Oanvända objekt tas bort. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Optimera resurser i dokumentet enligt definierad optimeringsstrategi. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organiserar sidträdnoder i ett dokument till ett balanserat träd. Endast om dokumentet har mer än nodesNumInSubtrees sidobjekt, annars gör det ingenting. Anropa inte denna metod medan du itererar över Pages-element, det kan ge oförutsägbara resultat |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Bearbeta stycken för generatorn. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Tar bort metadata från dokumentet. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Tar bort pdfa-kompatibilitet från dokumentet |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Tar bort pdfUa-kompatibilitet från dokumentet |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Reparera ett trasigt dokument. |
| [Save](../../aspose.pdf/document/save/#save)() | Spara dokumentet inkrementellt (dvs. med hjälp av inkrementell uppdateringsteknik). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Sparar dokumentet med spara-alternativ. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Lagrar dokumentet i strömmen. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Sparar dokumentet i den angivna filen. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Sparar dokumentet med ett nytt namn tillsammans med ett filformat. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Sparar dokumentet till en ström med spara-alternativ. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Sparar dokumentet med ett nytt namn tillsammans med ett filformat. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Sparar dokumentet med ett nytt namn och ställer in dess spara-alternativ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Spara dokumentet inkrementellt (dvs. med hjälp av inkrementell uppdateringsteknik). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Sparar dokumentet med spara-alternativ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Lagrar dokumentet i strömmen. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Sparar dokumentet i den angivna filen. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Sparar dokumentet med ett nytt namn tillsammans med ett filformat. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Sparar dokumentet till en ström med spara-alternativ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Sparar dokumentet med ett nytt namn tillsammans med ett filformat. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Sparar dokumentet med ett nytt namn och ställer in dess spara-alternativ. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Sparar dokumentet till XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Skickar vissa sidor av dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Sätter titel för PDF-dokument |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Sätter XMP-metadata för dokumentet. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Validerar dokumentet till den angivna filen. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Validerar dokumentet till den angivna filen. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Validerar dokumentet till den angivna filen. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Konverterar ström i källformat till ström i destinationsformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Konverterar ström i källformat till destinationsfil i destinationsformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Konverterar källfil i källformat till ström i destinationsformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Konverterar källfil i källformat till destinationsfil i destinationsformat. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Sätter filstorleksgränsen för att ladda en hel fil i minnet till standardvärdet som är 210 Mb. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Utlöser när ett typsnitt ersätter ett annat typsnitt i dokumentet. |

## Andra medlemmar

| Namn | Beskrivning |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Representerar metoden som kommer att hantera FontSubstitution-händelsen. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Innehåller funktionalitet för att justera typsnitt |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Representerar alternativen för Merge-metoder. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Representerar alternativ för att reparera ett PDF-dokument. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)