---
title: Document
second_title: Aspose.PDF för .NET API Referens
description: Klass som representerar PDF-dokument
type: docs
weight: 1870
url: /sv/net/aspose.pdf/document/
---
## Document class

Klass som representerar PDF-dokument

```csharp
public sealed class Document : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Document](document#constructor)() | Initierar tomt dokument. |
| [Document](document#constructor_1)(Stream) | Initiera ny dokumentinstans från*input* stream. |
| [Document](document#constructor_6)(string) | Init bara dokument med hjälp av*filename* . Samma som[`Document`](./document) . |
| [Document](document#constructor_3)(Stream, bool) | Initiera ny dokumentinstans från*input* stream. |
| [Document](document#constructor_2)(Stream, LoadOptions) | Öppnar ett befintligt dokument från en ström som ger nödvändig konvertering för att få pdf-dokument. |
| [Document](document#constructor_4)(Stream, string) | Initiera ny dokumentinstans från*input* stream. |
| [Document](document#constructor_7)(string, LoadOptions) | Öppnar ett befintligt dokument från en fil som ger nödvändiga konverteringsalternativ för att få pdf-dokument. |
| [Document](document#constructor_8)(string, string) | Initierar ny instans av[`Document`](../document) klass för att arbeta med krypterade dokument. |
| [Document](document#constructor_5)(Stream, string, bool) | Initiera ny dokumentinstans från*input* stream. |
| [Document](document#constructor_9)(string, string, bool) | Initierar ny instans av[`Document`](../document) klass för att arbeta med krypterade dokument. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | Hämtar dokumentåtgärder. Denna egenskap är en instans av klassen DocumentActions som gör det möjligt att hämta/ställa in BeforClosing, BeforSaving, etc. åtgärder. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | Gör det möjligt att slå samman sidinnehåll för att optimera dokumentstorleken. Om de används kan olika men duplicerade sidor referera till samma innehållsobjekt. Observera att det här läget kan orsaka biverkningar som att ändra sidinnehåll när en annan sida ändras. |
| [Background](../../aspose.pdf/document/background) { get; set; } | Hämtar eller ställer in bakgrundsfärgen för dokumentet. |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | Hämtar eller ställer in flagga som anger om positionen för dokumentets fönster kommer att centreras på skärmen. |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | Hämtar dokumentsamling. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | Får säkerhetsinställningar om dokumentet är krypterat. Om dokumentet inte är krypterat kommer motsvarande undantag att tas upp i .net 1.1 eller så kommer CryptoAlgorithm att vara null för andra .net-versioner. |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | Får samlingen av destinationer. Föråldrad. Använd NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | Hämtar eller ställer in läsordning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna på grund av licens för detta teckensnitt. Till exempel kan vissa teckensnitt inte bäddas in i PDF-dokument om licensregler inaktiverar inbäddning för detta teckensnitt. Denna flagga används för att inaktivera eventuella licensbegränsningar för alla teckensnitt i aktuellt PDF-dokument. Var försiktig när du använder den här flaggan. När den är inställd betyder det att personen som sätter denna flagga, tar allt ansvar för eventuella licens-/lagbrott på sig själv. Så han tar det på egen risk. Det rekommenderas starkt att endast använda denna flagga när du är helt säker på att du inte bryter mot upphovsrättslagen. Som standard false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | Hämtar eller ställer in en flagga som anger om dokumentets fönstertitelrad ska visa dokumentets titel. |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | Hämtar eller ställer in hanteringsalternativ för utskriftsduplexläge som ska användas vid utskrift av filen från utskriftsdialogrutan. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | Får samling av filer inbäddade i dokument. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | Egenskapen som deklarerar att dokumentet måste bädda in alla standardtypsnitt som har flaggan IsEmbedded satt till true. Alla PDF-teckensnitt kan bäddas in i dokument helt enkelt via inställningen av flaggan IsEmbedded in true, men PDF-standard Type1-teckensnitt är ett undantag från denna regel. Standard Type1-fontinbäddning kräver mycket tid, så för att bädda in dessa typsnitt är det nödvändigt inte bara ange flagga IsEmbedded in true för specificerat teckensnitt men ställ också in en tilläggsflagga på dokumentets nivå - EmbedStandardFonts = true; Den här egenskapen kan endast ställas in en gång för alla teckensnitt. Som standard false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | Hämta eller ställer in flagga som gör att dokument delvis kan laddas ur minnet. Detta gör det möjligt att minska minnesanvändningen men kan ha negativ effekt på prestandan. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | Hämtar eller ställer in flagga för att hantera sanering av signaturfält. Aktiverad som standard. |
| [FileName](../../aspose.pdf/document/filename) { get; } | Namnet på PDF-filen som orsakade detta dokument |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | Hämtar eller ställer in flagga som anger om dokumentfönstret måste ändras för att passa den första visade sidan. |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | IDocumentFontUtilities-instans |
| [Form](../../aspose.pdf/document/form) { get; } | Hämtar Acro Form av dokumentet. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | Kasta undantag om dokumentet kommer att sparas med ändringar och har signatur |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | Hämtar eller ställer in flagga som anger om menyraden ska döljas när dokumentet är aktivt. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | Hämtar eller ställer in flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | Hämtar eller ställer in flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [Id](../../aspose.pdf/document/id) { get; } | Får ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | Hämtar eller ställer in flaggan för att ignorera fel i källfiler. När sidor från källdokument kopieras till måldokument, stoppas kopieringsprocessen med undantag om några objekt i källfiler är skadade när denna flagga är falsk. exempel: dest.Pages.Add(src.Pages); Om denna flagga är satt till true kommer skadade objekt att ersättas med tomma värden. Som standard: true. |
| [Info](../../aspose.pdf/document/info) { get; } | Får dokumentinformation. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | Får krypterad status för dokumentet. Sant om dokumentet är krypterat. |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | Hämtar eller ställer in ett värde som anger om dokumentet är linjärt. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | Får dokumentet är pdfa-kompatibelt. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | Får dokumentet är pdfua-kompatibelt. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | Hämtar eller ställer in är dokumentet pdfa-kompatibelt. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | Samling av JavaScript på dokumentnivå. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | Får logisk struktur för dokumentet. |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | Dokumentmetadata. (Ett PDF-dokument kan innehålla allmän information, såsom dokumentets titel, författare och datum för skapande och ändring. Sådan global information om dokumentet (i motsats till dess innehåll eller struktur) kallas metadata och är avsedd att hjälpa till med att katalogisera och söka efter dokument i externa databaser.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | Samling av namngiven destination i dokumentet. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | Hämtar eller ställer in sidläge och anger hur dokumentet ska visas när helskärmsläget avslutas. |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | Hämtar eller ställer in åtgärd som utförs vid dokumentöppning. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | Hämtar eller ställer in optimeringsflagga. När sidor läggs till i dokumentet slås lika resursströmmar i den resulterande filen samman till ett PDF-objekt om denna flagga är inställd. Detta gör det möjligt att minska den resulterande filstorleken men kan orsaka långsammare exekvering och större minneskrav. Standardvärde: false. |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | Får dokumentkonturer. |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | Hämtar eller ställer in sidinformationen.(endast för generator) |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | Hämtar sidetiketter i dokumentet. |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | Hämtar eller ställer in sidlayout som ska användas när dokumentet öppnas. |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | Hämtar eller ställer in sidläge, som anger hur dokumentet ska visas när det öppnas. |
| [Pages](../../aspose.pdf/document/pages) { get; } | Hämtar eller ställer in samling av dokumentsidor. Observera att sidorna är numrerade från 1 i samlingen. |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | Får PDF-format |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | Får behörigheter för dokumentet. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | Får tillgång till TaggedPdf-innehåll. |
| [Version](../../aspose.pdf/document/version) { get; } | Hämtar en version av Pdf från Pdf-filhuvudet. |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | Får licenstillstånd för systemet. Returnerar sant är att systemet fungerar i licensierat läge och annars falskt. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | Bind xml till document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | Bind xml till document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | Bind xml/xsl till document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | Bind xml/xsl till document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | Bind xml/xsl till document |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | Ändrar dokumentlösenord. Denna åtgärd kan endast utföras med ägarlösenord. |
| [Check](../../aspose.pdf/document/check)(bool) | Validerar dokument. |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | Konvertera dokument och spara fel till den angivna filen. |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | Konvertera dokument med angivna konverteringsalternativ |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | Konvertera dokument och spara fel i den angivna strömmen. |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | Konvertera dokument och spara fel till den angivna filen. |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | Konvertera dokument genom att använda Fixup. |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | Konvertera dokument genom att använda Fixup. |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konvertera dokument och spara fel till den angivna filen. |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konvertera dokument och spara fel till den angivna filen. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | Konvertera sida till PNG för DSR, OMR, OCR bildström. |
| [Decrypt](../../aspose.pdf/document/decrypt)() | Dekrypterar dokumentet. Ring sedan Spara för att få en dekrypterad version av dokumentet. |
| [Dispose](../../aspose.pdf/document/dispose)() | Stänger alla resurser som används av detta dokument. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Krypterar dokumentet. Ring sedan Spara för att få en krypterad version av dokumentet. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Krypterar dokumentet. Ring sedan Spara för att få en krypterad version av dokumentet. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Krypterar dokumentet. Ring sedan Spara för att få en krypterad version av dokumentet. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | Exportera alla dokumentkommentarer till stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | Exporterar alla dokumentkommentarer till XFDF file |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | Tar bort alla fält från dokumentet och placerar deras värden istället. |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | Tar bort alla fält från dokumentet och placerar deras värden istället. |
| [FreeMemory](../../aspose.pdf/document/freememory)() | Rensar minne |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | Returnerar objektvärde från katalogordbok. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | Hämtar ett objekt med angivet ID i dokumentet. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | Hämta XMP-metadata från dokument. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importerar kommentarer från ström till dokument. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importerar kommentarer från XFDF-fil till dokument. |
| [Optimize](../../aspose.pdf/document/optimize)() | Linjärisera dokument för att - öppna första sidan så snabbt som möjligt; - visa nästa sida eller följ länken till nästa sida så snabbt som möjligt; - visa sidan stegvis när den kommer när data för en sida levereras över en långsam kanal (visa den mest användbara informationen först); - tillåt användarinteraktion, som att följa en länk, att utföras även innan hela sidan har tagits emot och visats. Att anropa den här metoden sparar faktiskt inte dokumentet . Tvärtom är endast dokumentet förberett att ha optimerad struktur, ring sedan Spara för att få optimerat dokument. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | Optimera resurser i dokumentet: 1. Resurser som inte används på dokumentsidorna tas bort; 2. Lika resurser sammanfogas till ett objekt; 3. Oanvända objekt raderas. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | Optimera resurser i dokumentet enligt definierad optimeringsstrategi. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | Bearbeta stycken för generator. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | Tar bort metadata från dokumentet. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | Ta bort pdfa-kompatibilitet från document |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | Ta bort pdfUa-kompatibilitet från document |
| [Repair](../../aspose.pdf/document/repair)() | Reparerar trasigt dokument. |
| [Save](../../aspose.pdf/document/save#save)() | Spara dokument stegvis (dvs. med inkrementell uppdateringsteknik). |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | Sparar dokumentet med sparalternativ. |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | Lagrar dokument i stream. |
| [Save](../../aspose.pdf/document/save#save_5)(string) | Sparar dokument i den angivna filen. |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | Sparar dokumentet med ett nytt namn tillsammans med ett filformat. |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | Sparar dokumentet i en ström med ett sparalternativ. |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | Sparar dokumentet med ett nytt namn tillsammans med ett filformat. |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ. |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | Sparar dokumentet i en svarsström med ett sparalternativ. |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | Spara dokument till XML. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | Skickar vissa sidor i dokumentet till dokumentenheten för bearbetning. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | Ange titel för Pdf Document |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | Ställ in XMP-metadata för dokument. |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | Validera dokument till den angivna filen. |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | Validera dokument till den angivna filen. |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | Validera dokument till den angivna filen. |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | Konverterar ström i källformat till ström i målformat. |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | Konverterar ström i källformat till målfil i målformat. |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | Konverterar källfil i källformat till stream i målformat. |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | Konverterar källfil i källformat till målfil i målformat. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | Återuppringningsproceduren för hocr-igenkänning. |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | Representerar metoden som kommer att hantera FontSubstitution-händelsen. |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | Innehåller funktionalitet för att justera teckensnitt |

### Se även

* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
