---
title: "Aspose::Pdf::Document klass"
linktitle: "Document"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Document klass. Klass som representerar ett PDF-dokument i C++."
type: docs
weight: 3900
url: /sv/cpp/aspose.pdf/document/
---
## Document class


Klass som representerar PDF-dokument.

```cpp
class Document : public System::IDisposable,
                 public Aspose::Pdf::ISupportsMemoryCleanup,
                 public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Nested classes

* Class [IDocumentFontUtilities](./idocumentfontutilities/)
* Class [MergeOptions](./mergeoptions/)
* Class [OptimizationOptions](./optimizationoptions/)
* Class [RepairOptions](./repairoptions/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BindXml](./bindxml/)(System::String) | Koppla XML till dokumentet. |
| [BindXml](./bindxml/)(const System::String\&, const System::String\&) | Koppla XML/XSL till dokumentet. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Koppla XML/XSL till dokumentet. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Xml::XmlReaderSettings\>\&) | Koppla XML/XSL till dokumentet. |
| [BindXml](./bindxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Koppla XML till dokumentet. |
| [ChangePasswords](./changepasswords/)(const System::String\&, const System::String\&, const System::String\&) | Ändrar dokumentets lösenord. Denna åtgärd kan endast utföras med ägarlösenordet. |
| [Check](./check/)(bool) | Validerar dokumentet. |
| [Convert](./convert/)(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konvertera dokumentet och spara fel i den angivna filen. |
| [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konvertera dokumentet och spara fel i den angivna filen. |
| [Convert](./convert/)(const System::String\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) | Konvertera dokumentet och spara fel i den angivna filen. |
| [Convert](./convert/)(const System::SharedPtr\<PdfFormatConversionOptions\>\&) | Konvertera dokumentet med angivna konverteringsalternativ. |
| [Convert](./convert/)(Document::CallBackGetHocrWithPage, bool) | Identifiera bilder i dokumentet och lägg till hocr-strängar ovanpå dem. |
| [Convert](./convert/)(Document::CallBackGetHocr, bool) | Identifiera bilder i dokumentet och lägg till hocr-strängar ovanpå dem. |
| [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat, ConvertErrorAction) | Konvertera dokumentet och spara fel i den angivna strömmen. |
| [Convert](./convert/)(Fixup, const System::SharedPtr\<System::IO::Stream\>\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) | Konvertera dokumentet genom att tillämpa [Fixup](../fixup/). |
| [Convert](./convert/)(Fixup, const System::String\&, bool, const System::ArrayPtr\<System::SharedPtr\<System::Object\>\>\&) | Konvertera dokumentet genom att tillämpa [Fixup](../fixup/). |
| static [Convert](./convert/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) | Konverterar källfilen i källformat till destinationsfil i destinationsformat. |
| static [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::String\&, System::SharedPtr\<SaveOptions\>) | Konverterar strömmen i källformat till destinationsfil i destinationsformat. |
| static [Convert](./convert/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) | Konverterar källfilen i källformat till en ström i destinationsformat. |
| static [Convert](./convert/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::SharedPtr\<SaveOptions\>) | Konverterar strömmen i källformat till en ström i destinationsformat. |
| [ConvertPageToPNGMemoryStream](./convertpagetopngmemorystream/)(const System::SharedPtr\<Page\>\&) | Konvertera sidan till PNG för DSR-, OMR- och OCR-bildström. |
| [Decrypt](./decrypt/)() | Dekrypterar dokumentet. Anropa sedan Save för att få den dekrypterade versionen av dokumentet. |
| [Dispose](./dispose/)() override | Stänger alla resurser som används av detta dokument. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&) | Initiera en ny [Document](./)-instans från *input*  strömmen. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, bool) | Initiera en ny [Document](./)-instans från *input*  strömmen. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) | Initiera en ny [Document](./)-instans från *input*  strömmen. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) | Initiera en ny [Document](./)-instans från *input*  strömmen. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) | Initiera en ny [Document](./)-instans från *input*  strömmen. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&) | Initierar en ny instans av klassen [Document](./) för att arbeta med krypterat dokument. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<Security::CertificateEncryptionOptions\>\&, bool) | Initierar en ny instans av klassen [Document](./) för att arbeta med krypterat dokument. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Initiera en ny [Document](./)-instans från *input*  strömmen. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool) | Initiera en ny [Document](./)-instans från *input*  strömmen. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Initiera en ny [Document](./)-instans från *input*  strömmen. |
| [Document](./document/)(const System::String\&) | Initiera bara [Document](./) med *filename*. Samma som [Document(Stream)](../). |
| [Document](./document/)(const System::String\&, bool) | Initiera bara [Document](./) med *filename*. Samma som [Document(Stream)](../). |
| [Document](./document/)(const System::String\&, const System::String\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Initierar en ny instans av klassen [Document](./) för att arbeta med krypterat dokument. |
| [Document](./document/)(const System::String\&, const System::String\&) | Initierar en ny instans av klassen [Document](./) för att arbeta med krypterat dokument. |
| [Document](./document/)(const System::String\&, const System::String\&, bool) | Initierar en ny instans av klassen [Document](./) för att arbeta med krypterat dokument. |
| [Document](./document/)(const System::String\&, const System::String\&, bool, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Initierar en ny instans av klassen [Document](./) för att arbeta med krypterat dokument. |
| [Document](./document/)() | Initierar ett tomt dokument. |
| [Document](./document/)(PdfVersion) | Initierar ett tomt dokument efter version. |
| [Document](./document/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Öppnar ett befintligt dokument från en fil och tillhandahåller nödvändiga konverteringsalternativ för att få ett pdf-dokument. |
| [Document](./document/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<LoadOptions\>\&) | Öppnar ett befintligt dokument från en ström och tillhandahåller nödvändiga konverteringar för att få ett pdf-dokument. |
| [Encrypt](./encrypt/)(Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, const System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>\>\>\&) | Krypterar dokumentet. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Krypterar dokumentet. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, const System::SharedPtr\<Security::ICustomSecurityHandler\>\&) | Krypterar dokumentet. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, const System::SharedPtr\<Facades::DocumentPrivilege\>\&, Aspose::Pdf::CryptoAlgorithm, bool) | Krypterar dokumentet. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm) | Krypterar dokumentet. |
| [Encrypt](./encrypt/)(const System::String\&, const System::String\&, Aspose::Pdf::Permissions, Aspose::Pdf::CryptoAlgorithm, bool) | Krypterar dokumentet. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::String\&) | Exporterar alla dokumentanteckningar till en XFDF-fil. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exportera alla dokumentanteckningar till en ström. |
| [Flatten](./flatten/)() | Tar bort alla fält från dokumentet och placerar deras värden istället. |
| [Flatten](./flatten/)(const System::SharedPtr\<Forms::Form::FlattenSettings\>\&) | Tar bort alla fält (och anteckningar) från dokumentet och placerar deras värden istället. |
| [FlattenTransparency](./flattentransparency/)() | Ersätter transparent innehåll med icke-transparent raster- och vektorgrafik. |
| [FreeMemory](./freememory/)() override | Rensar minnet. |
| [get_Actions](./get_actions/)() | Hämtar dokumentåtgärder. Denna egenskap är en instans av klassen DocumentActions som möjliggör att hämta/ange BeforClosing, BeforSaving osv. åtgärder. |
| [get_AllowReusePageContent](./get_allowreusepagecontent/)() | Tillåter att slå samman sidinnehåll för att optimera dokumentstorleken. Om den används kan olika men duplicerade sidor referera till samma innehållsobjekt. Observera att detta läge kan orsaka bieffekter, såsom att sidinnehållet ändras när en annan sida ändras. |
| [get_Background](./get_background/)() | Hämtar dokumentets bakgrundsfärg. |
| [get_CenterWindow](./get_centerwindow/)() | Hämtar flagga som anger om dokumentfönstrets position ska centreras på skärmen. |
| [get_Collection](./get_collection/)() | Hämtar samling av dokument. |
| [get_CryptoAlgorithm](./get_cryptoalgorithm/)() | Hämtar säkerhetsinställningar om dokumentet är krypterat. Om dokumentet inte är krypterat kommer motsvarande undantag att kastas i .net 1.1 eller så blir [CryptoAlgorithm](../cryptoalgorithm/) null för andra .net-versioner. |
| [get_CustomSecurityHandler](./get_customsecurityhandler/)() const | Hämtar en anpassad säkerhetshanterare. |
| [get_Destinations](./get_destinations/)() | Hämtar samlingen av destinationer. Föråldrad. Använd NamedDestinations. |
| [get_Direction](./get_direction/)() | Hämtar läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [get_DisableFontLicenseVerifications](./get_disablefontlicenseverifications/)() const | Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av teckensnittets licens. Till exempel kan vissa teckensnitt inte bäddas in i ett PDF-dokument om licensreglerna förbjuder inbäddning för detta teckensnitt. Denna flagga används för att inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella PDF-dokumentet. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens-/lagöverträdelser på sig själv. Så han tar det på egen risk. Det rekommenderas starkt att endast använda flaggan när du är helt säker på att du inte bryter mot upphovsrättslagen. Som standard false. |
| [get_DisplayDocTitle](./get_displaydoctitle/)() | Hämtar flagga som anger om dokumentfönstrets titelrad ska visa dokumentets titel. |
| [get_Duplex](./get_duplex/)() | Hämtar alternativ för hantering av utskriftsduplexläge att använda när filen skrivs ut från utskriftsdialogen. |
| [get_EmbeddedFiles](./get_embeddedfiles/)() | Hämtar samling av filer som är inbäddade i dokumentet. |
| [get_EmbedStandardFonts](./get_embedstandardfonts/)() const | Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑teckensnitt som har flaggan IsEmbedded satt till true. Alla PDF‑teckensnitt kan enkelt bäddas in i dokumentet genom att sätta flaggan IsEmbedded till true, men PDF‑standard‑Type1‑teckensnitt är ett undantag från denna regel. Inbäddning av standard‑Type1‑teckensnitt kräver mycket tid, så för att bädda in dessa teckensnitt måste man inte bara sätta flaggan IsEmbedded till true för det specifika teckensnittet utan även sätta en ytterligare flagga på dokumentnivå – EmbedStandardFonts = true; Denna egenskap kan endast sättas en gång för alla teckensnitt. Som standard false. |
| [get_EnableNotificationLogging](./get_enablenotificationlogging/)() const | Hämtar ett värde som indikerar om loggning av aviseringar ska aktiveras. |
| [get_EnableObjectUnload](./get_enableobjectunload/)() | Hämtar eller sätter flagga som möjliggör att dokumentet delvis avlastas från minnet. Detta minskar minnesanvändningen men kan ha negativ påverkan på prestanda. |
| [get_EnableSignatureSanitization](./get_enablesignaturesanitization/)() const | Hämtar flagga för att hantera sanering av signaturfält. Aktiverad som standard. |
| [get_FileName](./get_filename/)() | Namnet på PDF‑filen som orsakade detta dokument. |
| static [get_FileSizeLimitToMemoryLoading](./get_filesizelimittomemoryloading/)() | Hämtar och sätter filstorleksgränsen för att ladda en hel fil i minnet. Värdet anges i megabyte. Standardvärdet är 210 Mb. |
| [get_FitWindow](./get_fitwindow/)() | Hämtar flagga som anger om dokumentfönstret ska storleksändras för att passa den första visade sidan. |
| [get_FontUtilities](./get_fontutilities/)() | [IDocumentFontUtilities](./idocumentfontutilities/) instans. |
| [get_Form](./get_form/)() | Hämtar Acro Form för dokumentet. |
| [get_HandleSignatureChange](./get_handlesignaturechange/)() const | Kasta undantag om dokumentet sparas med ändringar och har en signatur. |
| [get_HideMenubar](./get_hidemenubar/)() | Hämtar flagga som anger om menyraden ska döljas när dokumentet är aktivt. |
| [get_HideToolBar](./get_hidetoolbar/)() | Hämtar flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt. |
| [get_HideWindowUI](./get_hidewindowui/)() | Hämtar flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [get_Id](./get_id/)() | Hämtar ID:t. |
| [get_IgnoreCorruptedObjects](./get_ignorecorruptedobjects/)() | Hämtar flagga för att ignorera fel i källfiler. När sidor från källdokumentet kopieras till måldokumentet stoppas kopieringsprocessen med ett undantag om vissa objekt i källfilerna är korrupta när flaggan är falsk. exempel: dest.Pages.Add(src.Pages); Om flaggan är satt till true ersätts korrupta objekt med tomma värden. Standardvärde: true. |
| [get_Info](./get_info/)() | Hämtar dokumentinformation. |
| [get_IsEncrypted](./get_isencrypted/)() | Hämtar krypteringsstatus för dokumentet. True om dokumentet är krypterat. |
| static [get_IsLicensed](./get_islicensed/)() | Hämtar licensierat tillstånd för systemet. Returnerar true om systemet kör i licensierat läge och false annars. |
| [get_IsLinearized](./get_islinearized/)() | Hämtar ett värde som indikerar om dokumentet är linjäriserat. |
| [get_IsPdfaCompliant](./get_ispdfacompliant/)() | Hämtar om dokumentet är PDF/A-kompatibelt. |
| [get_IsPdfUaCompliant](./get_ispdfuacompliant/)() | Hämtar om dokumentet är PDF/UA-kompatibelt. |
| [get_IsXrefGapsAllowed](./get_isxrefgapsallowed/)() | Hämtar om dokumentet är PDF/A-kompatibelt. |
| [get_JavaScript](./get_javascript/)() | [Collection](../collection/) av JavaScript på dokumentnivå. |
| [get_LogicalStructure](./get_logicalstructure/)() | Hämtar den logiska strukturen för dokumentet. |
| [get_Metadata](./get_metadata/)() | [Document](./) metadata. (Ett PDF-dokument kan innehålla allmän information, såsom dokumentets titel, författare samt skapande- och ändringsdatum. Sådan global information om dokumentet (i motsats till dess innehåll eller struktur) kallas metadata och är avsedd att hjälpa till vid katalogisering och sökning efter dokument i externa databaser.) |
| [get_NamedDestinations](./get_nameddestinations/)() | [Collection](../collection/) av namngivna destinationer i dokumentet. |
| [get_NonFullScreenPageMode](./get_nonfullscreenpagemode/)() | Hämtar sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| [get_OpenAction](./get_openaction/)() | Hämtar åtgärden som utförs vid dokumentöppning. |
| [get_OptimizeSize](./get_optimizesize/)() | Hämtar optimeringsflagga. När sidor läggs till i dokumentet slås lika resursströmmar i den resulterande filen samman till ett PDF-objekt om flaggan är satt. Detta minskar den resulterande filstorleken men kan leda till långsammare körning och högre minneskrav. Standardvärde: false. |
| [get_Outlines](./get_outlines/)() | Hämtar dokumentets konturer. |
| [get_OutputIntents](./get_outputintents/)() | Hämtar samlingen av Output-intent i dokumentet. |
| [get_PageInfo](./get_pageinfo/)() | Hämtar sidinformationen. (endast för generator, fylls inte i vid läsning av dokumentet) |
| [get_PageLabels](./get_pagelabels/)() | Hämtar sidetiketter i dokumentet. |
| [get_PageLayout](./get_pagelayout/)() | Hämtar sidlayout som ska användas när dokumentet öppnas. |
| [get_PageMode](./get_pagemode/)() | Hämtar sidläge, som specificerar hur dokumentet ska visas när det öppnas. |
| [get_Pages](./get_pages/)() | Hämtar samling av dokumentets sidor. [Note](../note/) att sidor numreras från 1 i samlingen. |
| [get_PdfFormat](./get_pdfformat/)() | Hämtar PDF-format. |
| [get_Permissions](./get_permissions/)() | Hämtar behörigheter för dokumentet. |
| [get_PickTrayByPdfSize](./get_picktraybypdfsize/)() | Hämtar en flagga som anger om PDF-sidans storlek ska användas för att välja inmatningspappersfacket. |
| [get_PrintScaling](./get_printscaling/)() | Hämtar sidskalningsalternativet som ska väljas när en utskriftsdialog visas för detta dokument. |
| [get_TaggedContent](./get_taggedcontent/)() |  |
| [get_Version](./get_version/)() | Hämtar en version av [Pdf](../) från [Pdf](../)-filhuvudet. |
| [GetCatalogValue](./getcatalogvalue/)(const System::String\&) | Returnerar postens värde från katalogordlistan. |
| [GetObjectById](./getobjectbyid/)(const System::String\&) | Hämtar ett objekt med angivet ID i dokumentet. |
| [GetXmpMetadata](./getxmpmetadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Hämta XMP-metadata från dokumentet. |
| [HasIncrementalUpdate](./hasincrementalupdate/)() | Kontrollerar om det aktuella PDF-dokumentet har sparats med inkrementella uppdateringar. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::String\&) | Importerar annotationer från XFDF-fil till dokumentet. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importerar annotationer från ström till dokumentet. |
| [IsRepairNeeded](./isrepairneeded/)(System::SharedPtr\<Document::RepairOptions\>\&) | Kontrollerar om dokumentet kräver ett anrop av Repair-metoden. |
| [LoadFrom](./loadfrom/)(const System::String\&, const System::SharedPtr\<LoadOptions\>\&) | Laddar en fil och konverterar den till PDF. |
| [Merge](./merge/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Slår ihop dokument. |
| [Merge](./merge/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::String\>\&) | Slår ihop dokument. |
| [Merge](./merge/)(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Slår ihop dokument. |
| [Merge](./merge/)(const System::ArrayPtr\<System::String\>\&) | Slår ihop pdf-filer. |
| static [MergeDocuments](./mergedocuments/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::String\>\&) | Slår ihop dokument. |
| static [MergeDocuments](./mergedocuments/)(const System::SharedPtr\<Document::MergeOptions\>\&, const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Slår ihop dokument. |
| static [MergeDocuments](./mergedocuments/)(const System::ArrayPtr\<System::String\>\&) | Slår ihop pdf-filer. |
| static [MergeDocuments](./mergedocuments/)(const System::ArrayPtr\<System::SharedPtr\<Document\>\>\&) | Slår ihop dokument. |
| [Optimize](./optimize/)() | Lineariserar dokumentet för att. |
| [OptimizeResources](./optimizeresources/)() | Optimera resurser i dokumentet: |
| [OptimizeResources](./optimizeresources/)(const System::SharedPtr\<Aspose::Pdf::Optimization::OptimizationOptions\>\&) | Optimera resurser i dokumentet enligt definierad optimeringsstrategi. |
| [PageNodesToBalancedTree](./pagenodestobalancedtree/)(uint8_t) | Organiserar sidträdsnoder i ett dokument till ett balanserat träd. Endast om dokumentet har fler än nodesNumInSubtrees sidobjekt, annars gör den ingenting. Anropa inte den här metoden medan du itererar över Pages-element, den kan ge oförutsägbara resultat. |
| [ProcessParagraphs](./processparagraphs/)() | Bearbeta stycken för generatorn. |
| [RemoveMetadata](./removemetadata/)() | Tar bort metadata från dokumentet. |
| [RemovePdfaCompliance](./removepdfacompliance/)() | Ta bort pdfa-efterlevnad från dokumentet. |
| [RemovePdfUaCompliance](./removepdfuacompliance/)() | Ta bort pdfUa-efterlevnad från dokumentet. |
| [Repair](./repair/)(System::SharedPtr\<Document::RepairOptions\>) | Reparerar trasigt dokument. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Lagrar dokumentet i en ström. |
| [Save](./save/)(const System::String\&) | Sparar dokumentet i den angivna filen. |
| [Save](./save/)() | Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). |
| [Save](./save/)(const System::SharedPtr\<SaveOptions\>\&) | Sparar dokumentet med sparalternativ. |
| [Save](./save/)(const System::String\&, SaveFormat) | Sparar dokumentet med ett nytt namn tillsammans med ett filformat. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, SaveFormat) | Sparar dokumentet med ett nytt namn tillsammans med ett filformat. |
| [Save](./save/)(const System::String\&, const System::SharedPtr\<SaveOptions\>\&) | Sparar dokumentet med ett nytt namn och anger dess sparalternativ. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SaveOptions\>\&) | Sparar dokumentet till en ström med ett sparalternativ. |
| [Save](./save/)(const System::SharedPtr\<System::Web::HttpResponse\>\&, const System::String\&, ContentDisposition, const System::SharedPtr\<SaveOptions\>\&) | Sparar dokumentet till en svarström med ett sparalternativ. |
| [SaveXml](./savexml/)(System::String) | Spara dokumentet till XML. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) | Skickar vissa sidor i dokumentet till dokumentenheten för bearbetning. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, const System::String\&) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [SendTo](./sendto/)(const System::SharedPtr\<Devices::DocumentDevice\>\&, int32_t, int32_t, const System::String\&) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [set_AllowReusePageContent](./set_allowreusepagecontent/)(bool) | Tillåter att slå samman sidinnehåll för att optimera dokumentstorleken. Om den används kan olika men duplicerade sidor referera till samma innehållsobjekt. Observera att detta läge kan orsaka bieffekter, såsom att sidinnehållet ändras när en annan sida ändras. |
| [set_Background](./set_background/)(const System::SharedPtr\<Color\>\&) | Ställer in dokumentets bakgrundsfärg. |
| [set_CenterWindow](./set_centerwindow/)(bool) | Ställer in flagga som anger om dokumentfönstrets position ska centreras på skärmen. |
| [set_Collection](./set_collection/)(const System::SharedPtr\<Aspose::Pdf::Collection\>\&) | Hämtar samling av dokument. |
| [set_Direction](./set_direction/)(Aspose::Pdf::Direction) | Ställer in läsordning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [set_DisableFontLicenseVerifications](./set_disablefontlicenseverifications/)(bool) | Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av teckensnittets licens. Till exempel kan vissa teckensnitt inte bäddas in i ett PDF-dokument om licensreglerna förbjuder inbäddning för detta teckensnitt. Denna flagga används för att inaktivera alla licensrestriktioner för alla teckensnitt i det aktuella PDF-dokumentet. Var försiktig när du använder denna flagga. När den är satt betyder det att personen som sätter flaggan tar fullt ansvar för eventuella licens-/lagöverträdelser på sig själv. Så han tar det på egen risk. Det rekommenderas starkt att endast använda flaggan när du är helt säker på att du inte bryter mot upphovsrättslagen. Som standard false. |
| [set_DisplayDocTitle](./set_displaydoctitle/)(bool) | Ställer in flagga som anger om dokumentfönstrets titelrad ska visa dokumenttiteln. |
| [set_Duplex](./set_duplex/)(PrintDuplex) | Ställer in alternativ för hantering av dubbelsidig utskrift att använda när filen skrivs ut från utskriftsdialogen. |
| [set_EmbedStandardFonts](./set_embedstandardfonts/)(bool) | Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑teckensnitt som har flaggan IsEmbedded satt till true. Alla PDF‑teckensnitt kan enkelt bäddas in i dokumentet genom att sätta flaggan IsEmbedded till true, men PDF‑standard‑Type1‑teckensnitt är ett undantag från denna regel. Inbäddning av standard‑Type1‑teckensnitt kräver mycket tid, så för att bädda in dessa teckensnitt måste man inte bara sätta flaggan IsEmbedded till true för det specifika teckensnittet utan även sätta en ytterligare flagga på dokumentnivå – EmbedStandardFonts = true; Denna egenskap kan endast sättas en gång för alla teckensnitt. Som standard false. |
| [set_EnableNotificationLogging](./set_enablenotificationlogging/)(bool) | Ställer in ett värde som indikerar om loggning av aviseringar ska aktiveras. |
| [set_EnableObjectUnload](./set_enableobjectunload/)(bool) | Hämtar eller sätter flagga som möjliggör att dokumentet delvis avlastas från minnet. Detta minskar minnesanvändningen men kan ha negativ påverkan på prestanda. |
| [set_EnableSignatureSanitization](./set_enablesignaturesanitization/)(bool) | Ställer in flagga för att hantera sanering av signaturfält. Aktiverad som standard. |
| static [set_FileSizeLimitToMemoryLoading](./set_filesizelimittomemoryloading/)(int32_t) | Hämtar och sätter filstorleksgränsen för att ladda en hel fil i minnet. Värdet anges i megabyte. Standardvärdet är 210 Mb. |
| [set_FitWindow](./set_fitwindow/)(bool) | Ställer in flagga som anger om dokumentfönstret måste ändras i storlek för att passa den först visade sidan. |
| [set_HandleSignatureChange](./set_handlesignaturechange/)(bool) | Kasta undantag om dokumentet sparas med ändringar och har en signatur. |
| [set_HideMenubar](./set_hidemenubar/)(bool) | Ställer in flagga som anger om menyraden ska döljas när dokumentet är aktivt. |
| [set_HideToolBar](./set_hidetoolbar/)(bool) | Ställer in flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt. |
| [set_HideWindowUI](./set_hidewindowui/)(bool) | Ställer in flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [set_IgnoreCorruptedObjects](./set_ignorecorruptedobjects/)(bool) | Ställer in flagga för att ignorera fel i källfiler. När sidor från källdokumentet kopieras till måldokumentet stoppas kopieringsprocessen med ett undantag om vissa objekt i källfilerna är korrupta när flaggan är falsk. exempel: dest.Pages.Add(src.Pages); Om flaggan är satt till true ersätts korrupta objekt med tomma värden. Som standard: true. |
| [set_IsLinearized](./set_islinearized/)(bool) | Ställer in ett värde som indikerar om dokumentet är linjäriserat. |
| [set_IsXrefGapsAllowed](./set_isxrefgapsallowed/)(bool) | Ställer in att dokumentet är PDF/A-kompatibelt. |
| [set_NonFullScreenPageMode](./set_nonfullscreenpagemode/)(Aspose::Pdf::PageMode) | Ställer in sidläge, som anger hur dokumentet ska visas vid avslut av helskärmsläge. |
| [set_OpenAction](./set_openaction/)(const System::SharedPtr\<Annotations::IAppointment\>\&) | Ställer in åtgärd som utförs vid dokumentöppning. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Ställer in optimeringsflaggan. När sidor läggs till i dokumentet slås lika resursströmmar i den resulterande filen ihop till ett PDF-objekt om flaggan är satt. Detta möjliggör att minska den resulterande filstorleken men kan leda till långsammare körning och större minneskrav. Standardvärde: false. |
| [set_PageInfo](./set_pageinfo/)(const System::SharedPtr\<Aspose::Pdf::PageInfo\>\&) | Ställer in sidinformationen. (endast för generator, fylls inte i vid läsning av dokumentet) |
| [set_PageLayout](./set_pagelayout/)(Aspose::Pdf::PageLayout) | Ställer in sidlayouten som ska användas när dokumentet öppnas. |
| [set_PageMode](./set_pagemode/)(Aspose::Pdf::PageMode) | Ställer in sidläge, vilket specificerar hur dokumentet ska visas när det öppnas. |
| [set_PickTrayByPdfSize](./set_picktraybypdfsize/)(bool) | Ställer in en flagga som anger om PDF-sidstorleken ska användas för att välja inmatningspappersfacket. |
| [set_PrintScaling](./set_printscaling/)(Aspose::Pdf::PrintScaling) | Ställer in sidskalningsalternativet som ska väljas när en utskriftsdialog visas för detta dokument. |
| static [SetDefaultFileSizeLimitToMemoryLoading](./setdefaultfilesizelimittomemoryloading/)() | Ställer in filstorleksgränsen för att ladda en hel fil i minnet till standardvärdet 210 Mb. |
| [SetTitle](./settitle/)(const System::String\&) | Ställ in titel för [Pdf](../)[Document](./). |
| [SetXmpMetadata](./setxmpmetadata/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ställ in XMP-metadata för dokumentet. |
| [Validate](./validate/)(const System::String\&, Aspose::Pdf::PdfFormat) | Validera dokumentet till den angivna filen. |
| [Validate](./validate/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::PdfFormat) | Validera dokumentet till den angivna filen. |
| [Validate](./validate/)(const System::SharedPtr\<PdfFormatConversionOptions\>\&) | Validera dokumentet till den angivna filen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [DefaultNodesNumInSubtrees](./defaultnodesnuminsubtrees/) |  |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [CallBackGetHocr](./callbackgethocr/) | Återuppringningsproceduren för hocr-igenkänning. |
| [CallBackGetHocrWithPage](./callbackgethocrwithpage/) | Återuppringningsproceduren för hocr-igenkänning. |
| [FontSubstitutionHandler](./fontsubstitutionhandler/) | Representerar metoden som kommer att hantera FontSubstitution‑händelsen. |
## Se även

* Class [IDisposable](../../system/idisposable/)
* Class [ISupportsMemoryCleanup](../isupportsmemorycleanup/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
