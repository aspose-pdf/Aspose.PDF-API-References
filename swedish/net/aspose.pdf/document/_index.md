---
title: "Klass Document"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Document-klass. Klass som representerar PDF-dokument"
type: docs
weight: 3900
url: /sv/net/aspose.pdf/document/
---
## Document class

Klass som representerar PDF-dokument.

```csharp
public sealed class Document : IDisposable
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Document](document/#constructor)() | Initierar ett tomt dokument. |
| [Document](document/#constructor_1)(PdfVersion) | Initierar ett tomt dokument efter version. |
| [Document](document/#constructor_2)(Stream) | Initiera en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_11)(string) | Initiera bara Document med *filename*. Samma som [`Document`](./document/). |
| [Document](document/#constructor_6)(Stream, bool) | Initiera en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_4)(Stream, CertificateEncryptionOptions) | Initiera en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Öppnar ett befintligt dokument från en ström som tillhandahåller nödvändig konvertering för att få PDF-dokument. |
| [Document](document/#constructor_7)(Stream, string) | Initiera en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_15)(string, bool) | Initiera bara Document med *filename*. Samma som [`Document`](./document/). |
| [Document](document/#constructor_13)(string, CertificateEncryptionOptions) | Initierar en ny instans av `Document`-klassen för att arbeta med krypterat dokument. |
| [Document](document/#constructor_12)(string, LoadOptions) | Öppnar ett befintligt document från en fil och tillhandahåller nödvändiga konverteringsalternativ för att få pdf document. |
| [Document](document/#constructor_16)(string, string) | Initierar en ny instans av `Document`-klassen för att arbeta med krypterat dokument. |
| [Document](document/#constructor_5)(Stream, CertificateEncryptionOptions, bool) | Initiera en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_9)(Stream, string, bool) | Initiera en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_8)(Stream, string, ICustomSecurityHandler) | Initiera en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_14)(string, CertificateEncryptionOptions, bool) | Initierar en ny instans av `Document`-klassen för att arbeta med krypterat dokument. |
| [Document](document/#constructor_18)(string, string, bool) | Initierar en ny instans av `Document`-klassen för att arbeta med krypterat dokument. |
| [Document](document/#constructor_17)(string, string, ICustomSecurityHandler) | Initierar en ny instans av `Document`-klassen för att arbeta med krypterat dokument. |
| [Document](document/#constructor_10)(Stream, string, bool, ICustomSecurityHandler) | Initiera en ny Document-instans från *input*-strömmen. |
| [Document](document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | Initierar en ny instans av `Document`-klassen för att arbeta med krypterat dokument. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Hämtar document‑åtgärder. Denna egenskap är en instans av DocumentActions‑klassen som tillåter att få/ställa in BeforClosing, BeforSaving osv. åtgärder. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Tillåter att slå ihop page‑innehåll för att optimera document‑storlek. Om den används kan olika men duplicerade pages referera till samma innehållsobjekt. Observera att detta läge kan orsaka bieffekter som att ändra page‑innehåll när en annan page ändras. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Hämtar eller anger bakgrundsfärgen för document. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Hämtar eller anger flagga som specificerar om positionen för document‑fönstret ska centreras på skärmen. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Hämtar samling av document. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Hämtar säkerhetsinställningar om document är krypterat. Om document inte är krypterat kommer motsvarande undantag att kastas i .net 1.1 eller CryptoAlgorithm blir null för andra .net‑versioner. |
| [CustomSecurityHandler](../../aspose.pdf/document/customsecurityhandler/) { get; } | Hämtar en anpassad säkerhetshanterare. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Hämtar samlingen av destinations. Föråldrad. Använd NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Hämtar eller anger läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Många operationer med font kan inte utföras om dessa operationer är förbjudna av licensen för denna font. Till exempel kan vissa font inte bäddas in i PDF‑document om licensreglerna inaktiverar inbäddning för denna font. Denna flagga används för att inaktivera alla licensrestriktioner för alla font i aktuellt PDF‑document. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar allt ansvar för eventuella licens‑/lagöverträdelser på egen hand. Så han tar det på egen risk. Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter mot upphovsrättslagen. Standardvärdet är falskt. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Hämtar eller anger flagga som specificerar om document‑fönstrets titelrad ska visa document‑titel. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Hämtar eller anger alternativ för hantering av utskriftsduplex‑läge att använda när filen skrivs ut från utskriftsdialogen. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Hämtar samling av filer som är inbäddade i document. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Egenskap som deklarerar att document måste bädda in alla standard‑Type1‑font som har flaggan IsEmbedded satt till true. Alla PDF‑font kan bäddas in i document enkelt genom att sätta flaggan IsEmbedded till true, men PDF‑standard‑Type1‑font är ett undantag från denna regel. Inbäddning av standard‑Type1‑font kräver mycket tid, så för att bädda in dessa font är det nödvändigt inte bara att sätta flaggan IsEmbedded till true för den angivna fonten utan också att sätta en ytterligare flagga på document‑nivå – EmbedStandardFonts = true; Denna egenskap kan endast sättas en gång för alla font. Standardvärdet är falskt. |
| [EnableNotificationLogging](../../aspose.pdf/document/enablenotificationlogging/) { get; set; } | Hämtar eller anger ett värde som indikerar om loggning av aviseringar ska aktiveras. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Hämtar eller anger flagga som möjliggör att document delvis laddas ur minnet. Detta minskar minnesanvändning men kan ha negativ påverkan på prestanda. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Hämtar eller anger flagga för att hantera sanering av signaturfält. Aktiverad som standard. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Namnet på PDF‑filen som orsakade detta document |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Hämtar eller anger flagga som specificerar om document‑fönstret måste ändras i storlek för att passa den första visade page. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | IDocumentFontUtilities‑instans |
| [Form](../../aspose.pdf/document/form/) { get; } | Hämtar Acro Form för document. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Kasta Exception om document sparas med ändringar och har signatur |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Hämtar eller anger flagga som specificerar om menyraden ska döljas när document är aktiv. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Hämtar eller anger flagga som specificerar om verktygsfältet ska döljas när dokumentet är aktivt. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Hämtar eller anger flagga som specificerar om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [Id](../../aspose.pdf/document/id/) { get; } | Hämtar ID:t. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Hämtar eller anger flagga för att ignorera fel i källfiler. När sidor från källdokumentet kopieras till måldokumentet stoppas kopieringsprocessen med ett undantag om vissa objekt i källfilerna är korrupta när denna flagga är falsk. exempel: dest.Pages.Add(src.Pages); Om flaggan är satt till true ersätts korrupta objekt med tomma värden. Standardvärde: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Hämtar dokumentinformation. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Hämtar krypteringsstatus för dokumentet. Sant om dokumentet är krypterat. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Hämtar eller anger ett värde som indikerar om dokumentet är lineariserat. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Hämtar om dokumentet är PDF/A-kompatibelt. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Hämtar om dokumentet är PDF/UA-kompatibelt. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Hämtar eller anger om dokumentet är PDF/A-kompatibelt. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Samling av JavaScript på dokumentnivå. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Hämtar dokumentets logiska struktur. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Dokumentmetadata. (Ett PDF-dokument kan innehålla allmän information, såsom dokumentets titel, författare samt skapande- och ändringsdatum. Sådan global information om dokumentet (i motsats till dess innehåll eller struktur) kallas metadata och är avsedd att underlätta katalogisering och sökning efter dokument i externa databaser.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Samling av namngivna destinationer i dokumentet. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Hämtar eller anger sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Hämtar eller anger åtgärd som utförs vid dokumentets öppning. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Hämtar eller anger optimeringsflagga. När sidor läggs till i dokumentet slås lika resursströmmar i den resulterande filen samman till ett PDF-objekt om flaggan är satt. Detta möjliggör en minskning av filstorleken men kan leda till långsammare körning och större minneskrav. Standardvärde: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Hämtar dokumentets innehållsförteckning. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Hämtar samlingen av Output-intent i dokumentet. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Hämtar eller anger sidinformation. (endast för generator, fylls inte i vid läsning av dokumentet) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Hämtar sidetiketter i dokumentet. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Hämtar eller anger sidlayout som ska användas när dokumentet öppnas. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Hämtar eller anger sidläge, som specificerar hur dokumentet ska visas när det öppnas. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Hämtar eller anger samling av dokumentsidor. Observera att sidor numreras från 1 i samlingen. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Hämtar PDF-format |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Hämtar behörigheter för document. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Hämtar eller anger en flagga som specificerar om PDF page-storlek ska användas för att välja inmatningspappersfacket. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Hämtar eller anger page-skalningsalternativet som ska väljas när en utskriftsdialog visas för detta document. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Hämtar åtkomst till TaggedPdf-innehåll. |
| [Version](../../aspose.pdf/document/version/) { get; } | Hämtar en version av Pdf från Pdf-filens rubrik. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Hämta och ange filstorleksgränsen för att läsa in en hel fil i minnet. Värdet anges i megabyte. Standardvärdet är 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Hämtar licensierat tillstånd för systemet. Returnerar true om systemet körs i licensierat läge och false annars. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Slår samman documents. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Slår samman pdf-filer. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Slår samman documents. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Slår samman documents. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Koppla xml till document. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Koppla xml till document. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Koppla xml/xsl till document. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Koppla xml/xsl till document. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Koppla xml/xsl till document. |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Ändrar document‑lösenord. Denna åtgärd kan endast utföras med ägarlösenord. |
| [Check](../../aspose.pdf/document/check/)(bool) | Validerar document. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Konvertera document med angivna konverteringsalternativ. |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Känn igen bilder i document och lägg till hocr‑strängar ovanpå dem. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Känn igen bilder i document och lägg till hocr‑strängar ovanpå dem. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Konvertera document och spara fel i den angivna streamen. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Konvertera document och spara fel i den angivna filen. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Konvertera document genom att tillämpa Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Konvertera document genom att tillämpa Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konvertera document och spara fel i den angivna filen. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konvertera document och spara fel i den angivna filen. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Konvertera page till PNG för DSR-, OMR- och OCR‑bildström. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Dekrypterar document. Anropa sedan Save för att få den dekrypterade versionen av document. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Stänger alla resurser som används av detta document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) | Krypterar document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, DocumentPrivilege, ICustomSecurityHandler) | Krypterar document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_3)(string, string, Permissions, CryptoAlgorithm) | Krypterar document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_5)(string, string, Permissions, ICustomSecurityHandler) | Krypterar document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Krypterar document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_4)(string, string, Permissions, CryptoAlgorithm, bool) | Krypterar document. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Exportera alla document‑anteckningar till streamen. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Exporterar alla document‑anteckningar till XFDF‑fil. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Tar bort alla fält från document och placerar deras värden istället. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Tar bort alla fält (och annotationer) från document och placerar deras värden istället. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Ersätter transparent innehåll med icke-transparent raster- och vektorgrafik. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Rensar minnet. |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Returnerar objektvärde från katalogordlistan. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Hämtar ett objekt med specificerat ID i document. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Hämta XMP-metadata från document. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Kontrollerar om det aktuella PDF document har sparats med inkrementella uppdateringar. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importerar annotationer från ström till document. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importerar annotationer från XFDF-fil till document. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Kontrollerar om document kräver ett anrop av Repair-metoden. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Laddar en fil och konverterar den till PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Slår samman documents. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Slår samman pdf-filer. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Slår samman documents. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Slår samman documents. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Lineariserar document för att - öppna den första sidan så snabbt som möjligt; - visa nästa sida eller följa en länk till nästa sida så snabbt som möjligt; - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara datan först); - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats. Att anropa denna metod sparar faktiskt inte document. Tvärtom förbereds document bara för att ha en optimerad struktur, anropa sedan Save för att få ett optimerat document. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Optimera resurser i document: 1. Resurser som inte används på document sidor tas bort; 2. Likadana resurser slås samman till ett objekt; 3. Oanvända objekt tas bort. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Optimera resurser i document enligt definierad optimeringsstrategi. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organiserar sidträdsnoder i ett document till ett balanserat träd. Endast om document har fler än nodesNumInSubtrees sidobjekt, annars gör den ingenting. Anropa inte denna metod medan du itererar över Pages-element, den kan ge oförutsägbara resultat. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Bearbeta stycken för generatorn. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Tar bort metadata från document. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Ta bort pdfa-efterlevnad från document |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Ta bort pdfUa-efterlevnad från document |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Reparerar trasigt document. |
| [Save](../../aspose.pdf/document/save/#save)() | Spara document inkrementellt (dvs. med inkrementell uppdateringsteknik). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Sparar document med sparalternativ. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Lagrar document i en ström. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Sparar document i den angivna filen. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Sparar document med ett nytt namn samt ett filformat. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Sparar dokumentet till en ström med sparalternativ. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Sparar document med ett nytt namn samt ett filformat. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Spara document inkrementellt (dvs. med inkrementell uppdateringsteknik). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Sparar document med sparalternativ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Lagrar document i en ström. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Sparar document i den angivna filen. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Sparar document med ett nytt namn samt ett filformat. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Sparar dokumentet till en ström med sparalternativ. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Sparar document med ett nytt namn samt ett filformat. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Spara dokumentet till XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Skickar vissa sidor i dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Ange titel för Pdf Document |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Ange XMP-metadata för dokumentet. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Validera dokumentet till den angivna filen. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Validera dokumentet till den angivna filen. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Validera dokumentet till den angivna filen. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Konverterar ström i källformat till ström i målformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Konverterar ström i källformat till målfil i målformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Konverterar källfil i källformat till ström i målformat. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Konverterar källfil i källformat till målfil i målformat. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Ställer in filstorleksgränsen för att ladda en hel fil i minnet till standardvärdet 210 Mb. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Uppstår när ett teckensnitt ersätter ett annat teckensnitt i dokumentet. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Representerar metoden som kommer att hantera FontSubstitution‑händelsen. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Innehåller funktionalitet för att justera teckensnitt. |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Representerar alternativen för Merge‑metoder. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Representerar alternativ för reparation av ett PDF‑dokument. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


