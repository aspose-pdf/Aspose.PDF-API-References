---
title: "Dokument"
linktitle: "Dokument"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar PDF-dokument."
type: docs
weight: 1060
url: /sv/java/com.aspose.pdf/document/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Document

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class Document extends Object implements IDocument
```

Klass som representerar PDF-dokument.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Det inträffar när ett teckensnitt ersätter ett annat teckensnitt i dokumentet. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Document](#Document--) | Initierar ett tomt dokument. |
| [Document](#Document-byte:A-) | Initiera en ny Document‑instans från {@code input}-byte‑arrayen. |
| [Document](#Document-java.io.InputStream-) | Initierar ett tomt dokument. |
| [Document](#Document-java.io.InputStream-boolean-) | Initierar ett tomt dokument. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Initierar ett tomt dokument. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Initierar ett tomt dokument. |
| [Document](#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Initierar ett tomt dokument. |
| [Document](#Document-java.io.InputStream-java.lang.String-) | Initierar ett tomt dokument. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-) | Initierar ett tomt dokument. |
| [Document](#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initierar ett tomt dokument. |
| [Document](#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initierar ett tomt dokument. |
| [Document](#Document-com.aspose.pdf.PdfVersion-) | Initierar ett tomt dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-) | Initierar ett tomt dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-) | Initierar ett tomt dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-) | Initierar ett tomt dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initierar ett tomt dokument. |
| [Document](#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-boolean-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-com.aspose.pdf.LoadOptions-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-java.lang.String-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initierar ett tomt dokument. |
| [Document](#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initierar ett tomt dokument. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [afterImport](#afterImport--) | Enumerera alla registrerade annotationer och anropa AfterImport för var och en av dem. |
| [bindXml](#bindXml-java.io.InputStream-) | Binda xml till dokument |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | Binda xml/xsl till dokument |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Binda xml/xsl till dokument |
| [bindXml](#bindXml-java.lang.String-) | Binda xml till dokument |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Binda xml/xsl till dokument |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Ändrar dokumentets lösenord. Denna åtgärd kan endast utföras med ägarlösenordet. |
| [check](#check-boolean-) | Validerar dokument. |
| [close](#close--) | Stänger alla resurser som används av detta dokument. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Känn igen bilder i dokumentet och lägg till hocr‑strängar ovanpå dem. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Konvertera dokumentet genom att tillämpa Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Konvertera dokumentet genom att tillämpa Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Konvertera dokumentet genom att tillämpa Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Konvertera dokumentet genom att tillämpa Fixup. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Konverterar en ström i källformat till en ström i målformat. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Konverterar en ström i källformat till en målfil i målformat. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konvertera dokumentet och spara fel i den angivna strömmen. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Konvertera dokument med angivna konverteringsalternativ |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Konverterar en källfil i källformat till en ström i målformat. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Konverterar källfil i källformat till destinationsfil i destinationsformat. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konvertera dokument och spara fel i den angivna filen. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konvertera dokumentet och spara fel i den angivna strömmen. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Konvertera sida till PNG för DSR-, OMR- och OCR-bildström. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras. |
| [decrypt](#decrypt--) | Dekrypterar dokumentet. Anropa sedan Save för att få den dekrypterade versionen av dokumentet. |
| [dispose](#dispose--) | Stänger alla resurser som används av detta dokument. Denna metod är föråldrad, använd close() istället. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Krypterar dokumentet. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Krypterar dokumentet. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Krypterar dokumentet. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exportera alla dokumentanteckningar till en ström. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporterar alla dokumentanteckningar till XFDF-fil |
| [flatten](#flatten--) | Tar bort alla fält (och anteckningar) från dokumentet och placerar deras värden istället. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Tar bort alla fält (och anteckningar) från dokumentet och placerar deras värden istället. |
| [flattenTransparency](#flattenTransparency--) | Ersätter transparent innehåll med icke‑transparent raster‑ och vektorgrafik. |
| [freeMemory](#freeMemory--) | Rensar minne |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Meddelande om saknade teckensnitt vid bearbetning av dokument. |
| [getActions](#getActions--) | <p> Hämtar dokumentåtgärder. Denna egenskap är en instans av klassen DocumentActions som möjliggör att hämta/ställa in BeforClosing, BeforSaving, etc. åtgärder. </p> |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Tillåter att slå samman sidinnehåll för att optimera dokumentstorleken. |
| [getBackground](#getBackground--) | Hämtar dokumentets bakgrundsfärg. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Returnerar objektvärde från katalogordbok. |
| [getCollection](#getCollection--) | Hämtar samling av dokument. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Hämtar säkerhetsinställningar om dokumentet är krypterat. Om dokumentet inte är krypterat kommer motsvarande undantag att kastas i .net 1.1 eller CryptoAlgorithm blir null för andra .net-versioner. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Hämtar en anpassad säkerhetshanterare. |
| [getDefaultCopier](#getDefaultCopier--) | Returnerar kopieringsverktyg som används för att kopiera sidor till detta dokument. |
| [getDestinations](#getDestinations--) | Hämtar samlingen av destinationer. |
| [getDirection](#getDirection--) | Hämtar läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [getDuplex](#getDuplex--) | Hämtar eller anger alternativ för hantering av dubbelsidig utskrift som ska användas när filen skrivs ut från utskriftsdialogen. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Hämtar samling av filer som är inbäddade i dokumentet. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt där flaggan IsEmbedded är satt till true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Hämtar eller anger flagga för att hantera sanering av signaturfält. |
| [getEngineDoc](#getEngineDoc--) | Instans av IPdfDocument som används för att komma åt intern dokumentstruktur. Endast intern. |
| [getFileName](#getFileName--) | Namnet på PDF‑filen som orsakade detta dokument |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Hämta och ställ in filstorleksgränsen för att ladda en hel fil i minnet. |
| [getFontUtilities](#getFontUtilities--) | Instans av IDocumentFontUtilities |
| [getForm](#getForm--) | Hämtar Acro Form för dokumentet. |
| [getId](#getId--) | Hämtar ID:n. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Hämtar eller anger flagga för att ignorera fel i källfiler. När sidor från källdokumentet kopieras till destinationsdokumentet stoppas kopieringsprocessen med ett undantag om vissa objekt i källfilerna är korrupta när flaggan är falsk. exempel: dest.Pages.Add(src.Pages); Om flaggan är satt till true ersätts korrupta objekt med tomma värden. Standardvärde: true. |
| [getInfo](#getInfo--) | Hämtar dokumentinformation. |
| [getJavaScript](#getJavaScript--) | Samling av JavaScript på dokumentnivå. |
| [getLogicalStructure](#getLogicalStructure--) | Hämtar dokumentets logiska struktur. |
| [getMetadata](#getMetadata--) | Dokumentmetadata. (Ett PDF-dokument kan innehålla allmän information, såsom dokumentets titel, författare samt skapande- och ändringsdatum. Sådan global information om dokumentet (i motsats till dess innehåll eller struktur) kallas metadata och är avsedd att underlätta katalogisering och sökning efter dokument i externa databaser.) |
| [getMetadataStream](#getMetadataStream--) | Returnerar rå metadata‑ström |
| [getNamedDestinations](#getNamedDestinations--) | Samling av namngivna destinationer i dokumentet. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Hämtar sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| [getObjectById](#getObjectById-java.lang.String-) | Hämtar ett objekt med angivet ID i dokumentet. |
| [getOpenAction](#getOpenAction--) | <p> Hämtar åtgärd som utförs vid dokumentöppning. </p> <hr> <pre> Exempel visar hur man får CenterWindow-flaggan: Document document = new Document(\"sample.pdf\"); IAppointment value = document.getOpenAction(); </pre> |
| [getOptimizeSize](#getOptimizeSize--) | Hämtar optimeringsflagga. När sidor läggs till i dokumentet slås lika resursströmmar i den resulterande filen samman till ett PDF-objekt om flaggan är satt. Detta möjliggör att minska den resulterande filstorleken men kan leda till långsammare körning och större minneskrav. Standardvärde: false. |
| [getOutlines](#getOutlines--) | Hämtar dokumentets konturer. |
| [getOutputIntents](#getOutputIntents--) | Hämtar samlingen av Output-intent i dokumentet. |
| [getPageInfo](#getPageInfo--) | Hämtar sidinformation (endast för generator, fylls inte i vid läsning av dokumentet) |
| [getPageLabels](#getPageLabels--) | Hämtar sidetiketter i dokumentet. |
| [getPageLayout](#getPageLayout--) | Hämtar sidlayout som ska användas när dokumentet öppnas. |
| [getPageMode](#getPageMode--) | Hämtar sidläge, som specificerar hur dokumentet ska visas när det öppnas. |
| [getPages](#getPages--) | <p> Hämtar samling av dokumentets sidor. Observera att sidor numreras från 1 i samlingen. </p> |
| [getPdfFormat](#getPdfFormat--) | Hämtar pdfa-format |
| [getPermissions](#getPermissions--) | Hämtar behörigheter för dokumentet. |
| [getPrintScaling](#getPrintScaling--) | Hämtar alternativ för hantering av utskriftsskalning att använda när filen skrivs ut från utskriftsdialogen. |
| [getTaggedContent](#getTaggedContent--) | Hämtar åtkomst till TaggedPdf-innehåll. Exemplet visar hur man använder taggat innehåll för att skapa ett nytt dokument med rubrik, stycken och bilder. // Skapa nytt dokument Document document = new Document(); // Hämta det taggade innehållet ITaggedContent taggedContent = document.getTaggedContent(); // Ställ in språk för dokumentet taggedContent.setLanguage("en-US"); // Ställ in titel för PDF-dokumentet taggedContent.setTitle("Example document"); // Skapar och lägger till sektion SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Skapa rubrik HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText("Rubriken"); sect.appendChild(h1); // Skapa stycke ParagraphElement p = taggedContent.createParagraphElement(); p.setTag("Paragraph"); p.setText("Texten i stycket."); sect.appendChild(p); // Skapa illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText("Figur 1"); figure1.setTitle("Bild 1"); figure1.setTag("Fig"); figure1.setImage("path/of/image.jpg"); // Spara dokument document.save("example.pdf"); |
| [getVersion](#getVersion--) | Hämtar en version av Pdf från Pdf-filens rubrik. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Hämta XMP-metadata från dokumentet. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Kontrollerar om det aktuella PDF-dokumentet har sparats med inkrementella uppdateringar. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Importerar annotationer från ström till dokument. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importerar annotationer från XFDF-fil till dokumentet. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Flagga som informerar om ersättning av saknad teckensnitt. |
| [isCenterWindow](#isCenterWindow--) | <p> Hämtar flagga som anger om dokumentfönstrets position ska centreras på skärmen. </p> |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | <p> Hämtar flagga som anger om dokumentfönstrets titelrad ska visa dokumentets titel. </p> |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Hämtar eller anger ett värde som indikerar om loggning av aviseringar ska aktiveras. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Hämtar eller anger flagga som möjliggör att dokumentet delvis laddas ur minnet. |
| [isEncrypted](#isEncrypted--) | Hämtar krypteringsstatus för dokumentet. Sant om dokumentet är krypterat. |
| [isFitWindow](#isFitWindow--) | <p> Hämtar flagga som anger om dokumentfönstret måste ändras i storlek för att passa den första visade sidan. </p> |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Kasta undantag om dokumentet sparas med ändringar och har signatur |
| [isHideMenubar](#isHideMenubar--) | <p> Hämtar flagga som anger om menyraden ska döljas när dokumentet är aktivt. </p> |
| [isHideToolBar](#isHideToolBar--) | <p> Hämtar flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt. </p> |
| [isHideWindowUI](#isHideWindowUI--) | <p> Hämtar flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt. </p> |
| [isLicensed](#isLicensed--) | Hämtar licensierat tillstånd för systemet. |
| [isLinearized](#isLinearized--) | Hämtar ett värde som indikerar om dokumentet är linjäriserat. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Som standard stänger metoden save interna strömmar och frigör minnesresurser. Vi kan utföra vissa operationer och fortsätta arbeta med dokumentet efter metoden save om denna ManualDispose-parameter är aktiverad. |
| [isPdfaCompliant](#isPdfaCompliant--) | Hämtar om dokumentet är PDF/A-kompatibelt. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Hämtar om dokumentet är pdfua-kompatibelt. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Hämtar en flagga som anger om PDF-sidans storlek ska användas för att välja inmatningspappersfacket. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Kontrollerar om dokumentet kräver ett anrop till Repair-metoden. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | Som standard är PDF/A-valideringsprocessen nödvändig för att uppdatera eller ta bort PDF/A-kompatibel data om vissa regler har brutits. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Hämtar eller anger om dokumentet är pdfa-kompatibelt. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Laddar en fil och konverterar den till PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Slår samman dokument. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Slår samman dokument. |
| [merge](#merge-com.aspose.pdf.Document...-) | Slår samman dokument. |
| [merge](#merge-java.lang.String...-) | Slår samman PDF-filer. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Slår samman dokument. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Slår samman dokument. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Slår samman dokument. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | Slår samman PDF-filer. |
| [optimize](#optimize--) | Linearizera dokumentet för att - öppna den första sidan så snabbt som möjligt; - visa nästa sida eller följa länk till nästa sida så snabbt som möjligt; - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara datan först); - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats. Att anropa denna metod sparar faktiskt inte dokumentet. Tvärtom förbereds dokumentet bara för att ha en optimerad struktur, anropa sedan Save för att få ett optimerat dokument. |
| [optimizeResources](#optimizeResources--) | Optimera resurser i dokumentet: 1. Resurser som inte används på dokumentets sidor tas bort; 2. Likadana resurser slås samman till ett objekt; 3. Oanvända objekt tas bort. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimera resurser i dokumentet: 1. Resurser som inte används på dokumentets sidor tas bort; 2. Likadana resurser slås samman till ett objekt; 3. Oanvända objekt tas bort. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organiserar sidträdsnoder i ett dokument i ett balanserat träd. Endast om dokumentet har fler än nodesNumInSubtrees sidobjekt, annars gör den ingenting. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organiserar sidträdsnoder i ett dokument i ett balanserat träd. Endast om dokumentet har fler än nodesNumInSubtrees sidobjekt, annars gör den ingenting. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Intern metod |
| [processParagraphs](#processParagraphs--) | Lagrar dokumentet i en ström. |
| [removeMetadata](#removeMetadata--) | Tar bort metadata från dokumentet. |
| [removePdfaCompliance](#removePdfaCompliance--) | Ta bort pdfa-efterlevnad från dokumentet |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Ta bort pdfUa-efterlevnad från dokumentet |
| [repair](#repair--) | Reparerar trasigt dokument. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Reparerar trasigt dokument. |
| [resumeUpdate](#resumeUpdate--) | återupptar dokumentuppdatering |
| [save](#save--) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [save](#save-java.io.OutputStream-) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [save](#save-com.aspose.pdf.SaveOptions-) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [save](#save-java.lang.String-) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | <p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Sparar PDF-dokumentet inkrementellt till den angivna strömmen. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Sparar PDF-dokumentet inkrementellt till den angivna strömmen. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Sparar PDF-dokumentet inkrementellt till den angivna strömmen. |
| [saveXml](#saveXml-java.lang.String-) | Spara dokumentet till XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Skickar vissa sidor i dokumentet till dokumentenheten för bearbetning. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Meddelande om saknade teckensnitt vid bearbetning av dokument. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Ställer in flagga för att ange programbestämt teckensnitt vid avsaknad av teckensnitt. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Tillåter att slå samman sidinnehåll för att optimera dokumentstorleken. |
| [setBackground](#setBackground-java.awt.Color-) | Ställer in dokumentets bakgrundsfärg. |
| [setCenterWindow](#setCenterWindow-boolean-) | Ställer in flagga som anger om dokumentfönstrets position ska centreras på skärmen. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Ställer in samling av dokument. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Hämtar konverteringsparameter för pdf/ua-konverteraren (Konvertera endast metadata och dokumentkatalog om satt till true) |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Ställer in filstorleksgränsen för att ladda en hel fil i minnet till standardvärdet 210 Mb. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Ställer in läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Ställer in flagga som anger om dokumentfönstrets titelrad ska visa dokumenttiteln. |
| [setDuplex](#setDuplex-int-) | Hämtar eller anger alternativ för hantering av dubbelsidig utskrift som ska användas när filen skrivs ut från utskriftsdialogen. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt där flaggan IsEmbedded är satt till true. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Hämtar eller anger ett värde som indikerar om loggning av aviseringar ska aktiveras. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Hämtar eller anger flagga som möjliggör att dokumentet delvis laddas ur minnet. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Hämtar eller anger flagga för att hantera sanering av signaturfält. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Hämta och ställ in filstorleksgränsen för att ladda en hel fil i minnet. |
| [setFitWindow](#setFitWindow-boolean-) | Ställer in flagga som anger om dokumentfönstret måste ändras i storlek för att passa den första visade sidan. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Kasta undantag om dokumentet sparas med ändringar och har signatur |
| [setHideMenubar](#setHideMenubar-boolean-) | Ställer in flagga som anger om menyraden ska döljas när dokumentet är aktivt. |
| [setHideToolBar](#setHideToolBar-boolean-) | Ställ in flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Ställer in flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Hämtar eller anger flagga för att ignorera fel i källfiler. När sidor från källdokumentet kopieras till destinationsdokumentet stoppas kopieringsprocessen med ett undantag om vissa objekt i källfilerna är korrupta när flaggan är falsk. exempel: dest.Pages.Add(src.Pages); Om flaggan är satt till true ersätts korrupta objekt med tomma värden. Standardvärde: true. |
| [setLinearized](#setLinearized-boolean-) | Ställer in ett värde som indikerar om dokumentet är linjäriserat. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Som standard stänger metoden save interna strömmar och frigör minnesresurser. Vi kan utföra vissa operationer och fortsätta arbeta med dokumentet efter att metoden save har anropats om parametern ManualDispose är aktiverad. Men det rekommenderas starkt att anropa dispose‑metoden när Document‑instansen inte längre behövs. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Ställer in sidläge och specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | <p> Ställer in åtgärden som utförs vid dokumentöppning. <p> |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Ställer in optimeringsflagga. När sidor läggs till i dokumentet slås lika resursströmmar i den resulterande filen samman till ett PDF‑objekt om denna flagga är satt. Detta möjliggör en minskning av den resulterande filstorleken men kan leda till långsammare körning och större minneskrav. Standardvärde: false. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Ställer in sidinformationen. (endast för generator, fylls inte i vid läsning av dokumentet) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Ställer in sidlayouten som ska användas när dokumentet öppnas. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Ställer in sidläge och specificerar hur dokumentet ska visas när det öppnas. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Ställer in en flagga som anger om PDF‑sidans storlek ska användas för att välja inmatningspappersfacket. |
| [setPrintScaling](#setPrintScaling-int-) | Ställer in alternativ för hantering av utskriftsskalning som ska användas när filen skrivs ut från utskriftsdialogen. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | Som standard är pdfa‑valideringsprocessen nödvändig för att uppdatera eller ta bort pdfa om vissa regler har brutits. |
| [setTitle](#setTitle-java.lang.String-) | Ange titel för PDF‑dokument |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Ange XMP‑metadata för dokumentet. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Hämtar eller anger om dokumentet är pdfa-kompatibelt. |
| [suppressUpdate](#suppressUpdate--) | Undertrycker uppdatering av innehållsdata för alla sidor. Innehållet uppdateras inte förrän ResumeUpdate anropas. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validera dokumentet till den angivna filen. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Validera dokumentet till den angivna filen. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validera dokumentet till den angivna filen. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

Det inträffar när ett teckensnitt ersätter ett annat teckensnitt i dokumentet.

### Document {#Document--}
```
public Document()
```

Initierar ett tomt dokument.

### Document {#Document-byte:A-}
```
public Document(byte[] input)
```

Initiera en ny Document‑instans från {@code input}-byte‑arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning |  | byte‑array med pdf‑dokument. |

### Document {#Document-java.io.InputStream-}
Initierar ett tomt dokument.

### Document {#Document-java.io.InputStream-boolean-}
Initierar ett tomt dokument.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Initierar ett tomt dokument.

### Document {#Document-java.io.InputStream-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Initierar ett tomt dokument.

### Document {#Document-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Initierar ett tomt dokument.

### Document {#Document-java.io.InputStream-java.lang.String-}
Initierar ett tomt dokument.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-}
Initierar ett tomt dokument.

### Document {#Document-java.io.InputStream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initierar ett tomt dokument.

### Document {#Document-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initierar ett tomt dokument.

### Document {#Document-com.aspose.pdf.PdfVersion-}
Initierar ett tomt dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-}
Initierar ett tomt dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-com.aspose.pdf.LoadOptions-}
Initierar ett tomt dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-}
Initierar ett tomt dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initierar ett tomt dokument.

### Document {#Document-com.aspose.ms.System.IO.Stream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-boolean-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-com.aspose.pdf.engine.security.CertificateEncryptionOptions-boolean-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-com.aspose.pdf.LoadOptions-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-java.lang.String-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-java.lang.String-boolean-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-java.lang.String-boolean-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initierar ett tomt dokument.

### Document {#Document-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initierar ett tomt dokument.

### afterImport {#afterImport--}
```
public void afterImport()
```

Enumerera alla registrerade annotationer och anropa AfterImport för var och en av dem.

### bindXml {#bindXml-java.io.InputStream-}
Binda xml till dokument

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
Binda xml/xsl till dokument

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
Binda xml/xsl till dokument

### bindXml {#bindXml-java.lang.String-}
Binda xml till dokument

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Binda xml/xsl till dokument

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Ändrar dokumentets lösenord. Denna åtgärd kan endast utföras med ägarlösenordet.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

Validerar dokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| doRepair |  | Om true repareras hittade problem. |

**Returns:**
booleskt värde

### close {#close--}
```
public void close()
```

Stänger alla resurser som används av detta dokument.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Känn igen bilder i dokumentet och lägg till hocr‑strängar ovanpå dem.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Konvertera dokumentet genom att tillämpa Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Konvertera dokumentet genom att tillämpa Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Konvertera dokumentet genom att tillämpa Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Konvertera dokumentet genom att tillämpa Fixup.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Konverterar en ström i källformat till en ström i målformat.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Konverterar en ström i källformat till en målfil i målformat.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konvertera dokumentet och spara fel i den angivna strömmen.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Konvertera dokument med angivna konverteringsalternativ

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Konverterar en källfil i källformat till en ström i målformat.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Konverterar källfil i källformat till destinationsfil i destinationsformat.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konvertera dokument och spara fel i den angivna filen.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konvertera dokumentet och spara fel i den angivna strömmen.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Konvertera sida till PNG för DSR-, OMR- och OCR-bildström.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras.

### decrypt {#decrypt--}
```
public void decrypt()
```

Dekrypterar dokumentet. Anropa sedan Save för att få den dekrypterade versionen av dokumentet.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Stänger alla resurser som används av detta dokument. Denna metod är föråldrad, använd close() istället.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Krypterar dokumentet.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Krypterar dokumentet.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Krypterar dokumentet. Anropa sedan Save för att få den krypterade versionen av dokumentet.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Krypterar dokumentet.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exportera alla dokumentanteckningar till en ström.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exporterar alla dokumentanteckningar till XFDF-fil

### flatten {#flatten--}
```
public void flatten()
```

Tar bort alla fält (och anteckningar) från dokumentet och placerar deras värden istället.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Tar bort alla fält (och anteckningar) från dokumentet och placerar deras värden istället.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Ersätter transparent innehåll med icke‑transparent raster‑ och vektorgrafik.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Rensar minne

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Meddelande om saknade teckensnitt vid bearbetning av dokument.

**Returns:**
ADocument.AbsentFontHandler‑instans

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

<p> Hämtar dokumentåtgärder. Denna egenskap är en instans av klassen DocumentActions som möjliggör att hämta/ställa in BeforClosing, BeforSaving, etc. åtgärder. </p>

**Returns:**
DocumentActionCollection‑objekt <hr> <pre> Detta exempel visar hur man hämtar efter‑öppnings‑åtgärden för dokumentet: Document document = new Document("PdfWithOpenAction.pdf"); DocumentActionCollection actions = document.getActions(); PdfAction afterSavingAction = actions.getAfterSaving(); </pre>

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Tillåter att slå samman sidinnehåll för att optimera dokumentstorleken.

**Returns:**
värde boolean‑värde

### getBackground {#getBackground--}
```
public Color getBackground()
```

Hämtar dokumentets bakgrundsfärg.

**Returns:**
Color‑objekt

### getCatalogValue {#getCatalogValue-java.lang.String-}
Returnerar objektvärde från katalogordbok.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Hämtar samling av dokument.

**Returns:**
Collection object

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Hämtar säkerhetsinställningar om dokumentet är krypterat. Om dokumentet inte är krypterat kommer motsvarande undantag att kastas i .net 1.1 eller CryptoAlgorithm blir null för andra .net-versioner.

**Returns:**
CryptoAlgorithm‑element @see CryptoAlgorithm

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public final com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Hämtar en anpassad säkerhetshanterare.

**Returns:**
ICustomSecurityHandler instance

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Returnerar kopieringsverktyg som används för att kopiera sidor till detta dokument.

**Returns:**
Copier object

### getDestinations {#getDestinations--}
```
public DestinationCollection getDestinations()
```

Hämtar samlingen av destinationer.

**Returns:**
DestinationCollection‑element

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Hämtar läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster).

**Returns:**
Direction‑element @see Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Hämtar eller anger alternativ för hantering av dubbelsidig utskrift som ska användas när filen skrivs ut från utskriftsdialogen.

**Returns:**
PrintDuplex‑element

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Hämtar samling av filer som är inbäddade i dokumentet.

**Returns:**
EmbeddedFileCollection‑objekt

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt där flaggan IsEmbedded är satt till true.

**Returns:**
booleskt värde

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

Hämtar eller anger flagga för att hantera sanering av signaturfält.

**Returns:**
booleskt värde

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instans av IPdfDocument som används för att komma åt intern dokumentstruktur. Endast intern.

**Returns:**
IPdfDocument‑objekt

### getFileName {#getFileName--}
```
public String getFileName()
```

Namnet på PDF‑filen som orsakade detta dokument

**Returns:**
String-objekt

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Hämta och ställ in filstorleksgränsen för att ladda en hel fil i minnet.

**Returns:**
int‑värde

### getFontUtilities {#getFontUtilities--}
```
public Document.IDocumentFontUtilities getFontUtilities()
```

Instans av IDocumentFontUtilities

**Returns:**
Instans av IDocumentFontUtilities

### getForm {#getForm--}
```
public Form getForm()
```

Hämtar Acro Form för dokumentet.

**Returns:**
Form‑objekt

### getId {#getId--}
```
public Id getId()
```

Hämtar ID:n.

**Returns:**
Id‑objekt

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Hämtar eller anger flagga för att ignorera fel i källfiler. När sidor från källdokumentet kopieras till destinationsdokumentet stoppas kopieringsprocessen med ett undantag om vissa objekt i källfilerna är korrupta när flaggan är falsk. exempel: dest.Pages.Add(src.Pages); Om flaggan är satt till true ersätts korrupta objekt med tomma värden. Standardvärde: true.

**Returns:**
booleskt värde

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Hämtar dokumentinformation.

**Returns:**
DocumentInfo‑objekt

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Samling av JavaScript på dokumentnivå.

**Returns:**
JavaScriptCollection objekt

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Hämtar dokumentets logiska struktur.

**Returns:**
RootElement‑objekt

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Dokumentmetadata. (Ett PDF-dokument kan innehålla allmän information, såsom dokumentets titel, författare samt skapande- och ändringsdatum. Sådan global information om dokumentet (i motsats till dess innehåll eller struktur) kallas metadata och är avsedd att underlätta katalogisering och sökning efter dokument i externa databaser.)

**Returns:**
Metadata‑objekt

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Returnerar rå metadata‑ström

**Returns:**
IPdfStreamAccessor‑objekt

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Samling av namngivna destinationer i dokumentet.

**Returns:**
NamedDestinationCollection‑instans

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Hämtar sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge.

**Returns:**
PageMode element @see PageMode

### getObjectById {#getObjectById-java.lang.String-}
Hämtar ett objekt med angivet ID i dokumentet.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

<p> Hämtar åtgärd som utförs vid dokumentöppning. </p> <hr> <pre> Exempel visar hur man får CenterWindow-flaggan: Document document = new Document(\"sample.pdf\"); IAppointment value = document.getOpenAction(); </pre>

**Returns:**
IAppointment‑objekt

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Hämtar optimeringsflagga. När sidor läggs till i dokumentet slås lika resursströmmar i den resulterande filen samman till ett PDF-objekt om flaggan är satt. Detta möjliggör att minska den resulterande filstorleken men kan leda till långsammare körning och större minneskrav. Standardvärde: false.

**Returns:**
booleskt värde

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Hämtar dokumentets konturer.

**Returns:**
OutlineCollection‑objekt

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Hämtar samlingen av Output-intent i dokumentet.

**Returns:**
OutputIntents instans

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Hämtar sidinformation (endast för generator, fylls inte i vid läsning av dokumentet)

**Returns:**
Sidans information.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Hämtar sidetiketter i dokumentet.

**Returns:**
PageLabelCollection‑objekt

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Hämtar sidlayout som ska användas när dokumentet öppnas.

**Returns:**
PageLayout element @see PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Hämtar sidläge, som specificerar hur dokumentet ska visas när det öppnas.

**Returns:**
PageMode element @see PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

<p> Hämtar samling av dokumentets sidor. Observera att sidor numreras från 1 i samlingen. </p>

**Returns:**
PageCollection objekt <hr> <pre> Exemplet nedan visar hur man arbetar med dokumentets sidor: Hur man får antalet sidor och hur man får rektangeln för den första sidan i dokumentet. Document document = new Document("sample.pdf"); PageCollection pages = document.getPages(); System.out.println("Document contains " + pages.size()); Page page = pages.get_Item(1); Rectangle rect = page.getRect(); </pre>

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Hämtar pdfa-format

**Returns:**
PdfFormat element @see PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Hämtar behörigheter för dokumentet.

**Returns:**
int‑värde

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Hämtar alternativ för hantering av utskriftsskalning att använda när filen skrivs ut från utskriftsdialogen.

**Returns:**
PrintScaling‑element

### getTaggedContent {#getTaggedContent--}
```
public final ITaggedContent getTaggedContent()
```

Hämtar åtkomst till TaggedPdf-innehåll. Exemplet visar hur man använder taggat innehåll för att skapa ett nytt dokument med rubrik, stycken och bilder. // Skapa nytt dokument Document document = new Document(); // Hämta det taggade innehållet ITaggedContent taggedContent = document.getTaggedContent(); // Ställ in språk för dokumentet taggedContent.setLanguage("en-US"); // Ställ in titel för PDF-dokumentet taggedContent.setTitle("Example document"); // Skapar och lägger till sektion SectElement sect = taggedContent.createSectElement(); taggedContent.getRootElement().appendChild(sect); // Skapa rubrik HeaderElement h1 = taggedContent.createHeaderElement(1); h1.setText("Rubriken"); sect.appendChild(h1); // Skapa stycke ParagraphElement p = taggedContent.createParagraphElement(); p.setTag("Paragraph"); p.setText("Texten i stycket."); sect.appendChild(p); // Skapa illustration IllustrationElement figure1 = taggedContent.createFigureElement(); sect.appendChild(figure1); figure1.setAlternativeText("Figur 1"); figure1.setTitle("Bild 1"); figure1.setTag("Fig"); figure1.setImage("path/of/image.jpg"); // Spara dokument document.save("example.pdf");

**Returns:**
ITaggedContent‑instans

### getVersion {#getVersion--}
```
public String getVersion()
```

Hämtar en version av Pdf från Pdf-filens rubrik.

**Returns:**
String värde

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Hämta XMP-metadata från dokumentet.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Kontrollerar om det aktuella PDF-dokumentet har sparats med inkrementella uppdateringar.

**Returns:**
true om PDF-dokumentet har inkrementella uppdateringar; annars false.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Importerar annotationer från ström till dokument.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importerar annotationer från XFDF-fil till dokumentet.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Flagga som informerar om ersättning av saknad teckensnitt.

**Returns:**
booleskt värde

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

<p> Hämtar flagga som anger om dokumentfönstrets position ska centreras på skärmen. </p>

**Returns:**
boolean värde <hr> <pre> Exemplet visar hur man får CenterWindow-flaggan: Document document = new Document("sample.pdf"); boolean value = document.isCenterWindow(); </pre>

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt.

**Returns:**
boolean‑värde Som standard falskt.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

<p> Hämtar flagga som anger om dokumentfönstrets titelrad ska visa dokumentets titel. </p>

**Returns:**
boolean värde <hr> <pre> Exemplet visar hur man får DisplayDocTitle-flaggan: Document document = new Document("sample.pdf"); boolean value = document.isDisplayDocTitle(); </pre>

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Hämtar eller anger ett värde som indikerar om loggning av aviseringar ska aktiveras.

**Returns:**
booleskt värde

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Hämtar eller anger flagga som möjliggör att dokumentet delvis laddas ur minnet.

**Returns:**
booleskt värde

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Hämtar krypteringsstatus för dokumentet. Sant om dokumentet är krypterat.

**Returns:**
booleskt värde

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

<p> Hämtar flagga som anger om dokumentfönstret måste ändras i storlek för att passa den första visade sidan. </p>

**Returns:**
boolean värde <hr> <pre> Exemplet visar hur man får FitWindow-flaggan: Document document = new Document("sample.pdf"); boolean value = document.isFitWindow(); </pre>

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Kasta undantag om dokumentet sparas med ändringar och har signatur

**Returns:**
booleskt värde

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

<p> Hämtar flagga som anger om menyraden ska döljas när dokumentet är aktivt. </p>

**Returns:**
boolean värde <hr> <pre> Exemplet visar hur man får HideMenubar-flaggan: Document document = new Document("sample.pdf"); boolean value = document.isHideMenubar(); </pre>

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

<p> Hämtar flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt. </p>

**Returns:**
boolean värde <hr> <pre> Exemplet visar hur man får HideToolBar-flaggan: Document document = new Document("sample.pdf"); boolean value = document.isHideToolBar(); </pre>

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

<p> Hämtar flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt. </p>

**Returns:**
boolean värde <hr> <pre> Exemplet visar hur man får HideWindowUI-flaggan: Document document = new Document("sample.pdf"); boolean value = document.isHideWindowUI(); </pre>

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Hämtar licensierat tillstånd för systemet.

**Returns:**
booleskt värde

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Hämtar ett värde som indikerar om dokumentet är linjäriserat.

**Returns:**
booleskt värde

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Som standard stänger metoden save interna strömmar och frigör minnesresurser. Vi kan utföra vissa operationer och fortsätta arbeta med dokumentet efter metoden save om denna ManualDispose-parameter är aktiverad.

**Returns:**
boolean‑värde. (Standardvärde == falskt)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Hämtar om dokumentet är PDF/A-kompatibelt.

**Returns:**
booleskt värde

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Hämtar om dokumentet är pdfua-kompatibelt.

**Returns:**
booleskt värde

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

Hämtar en flagga som anger om PDF-sidans storlek ska användas för att välja inmatningspappersfacket.

**Returns:**
booleskt värde

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Kontrollerar om dokumentet kräver ett anrop till Repair-metoden.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

Som standard är PDF/A-valideringsprocessen nödvändig för att uppdatera eller ta bort PDF/A-kompatibel data om vissa regler har brutits.

**Returns:**
booleskt värde

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Hämtar eller anger om dokumentet är pdfa-kompatibelt.

**Returns:**
booleskt värde

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Laddar en fil och konverterar den till PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Slår samman dokument.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Slår samman dokument.

### merge {#merge-com.aspose.pdf.Document...-}
Slår samman dokument.

### merge {#merge-java.lang.String...-}
Slår samman PDF-filer.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Slår samman dokument.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Slår samman dokument.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Slår samman dokument.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
Slår samman PDF-filer.

### optimize {#optimize--}
```
public void optimize()
```

Linearizera dokumentet för att - öppna den första sidan så snabbt som möjligt; - visa nästa sida eller följa länk till nästa sida så snabbt som möjligt; - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara datan först); - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats. Att anropa denna metod sparar faktiskt inte dokumentet. Tvärtom förbereds dokumentet bara för att ha en optimerad struktur, anropa sedan Save för att få ett optimerat dokument.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Optimera resurser i dokumentet: 1. Resurser som inte används på dokumentets sidor tas bort; 2. Likadana resurser slås samman till ett objekt; 3. Oanvända objekt tas bort.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimera resurser i dokumentet: 1. Resurser som inte används på dokumentets sidor tas bort; 2. Likadana resurser slås samman till ett objekt; 3. Oanvända objekt tas bort.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organiserar sidträdsnoder i ett dokument i ett balanserat träd. Endast om dokumentet har fler än nodesNumInSubtrees sidobjekt, annars gör den ingenting.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organiserar sidträdsnoder i ett dokument i ett balanserat träd. Endast om dokumentet har fler än nodesNumInSubtrees sidobjekt, annars gör den ingenting.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodesNumInSubtrees |  | Önskat antal undernoder. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Intern metod

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Lagrar dokumentet i en ström.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Tar bort metadata från dokumentet.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Ta bort pdfa-efterlevnad från dokumentet

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Ta bort pdfUa-efterlevnad från dokumentet

### repair {#repair--}
```
public void repair()
```

Reparerar trasigt dokument.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Reparerar trasigt dokument.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

återupptar dokumentuppdatering

### save {#save--}
```
public void save()
```

<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### save {#save-java.io.OutputStream-}
<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### save {#save-com.aspose.pdf.SaveOptions-}
<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### save {#save-com.aspose.ms.System.IO.Stream-}
<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### save {#save-java.lang.String-}
<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
<p> Spara dokumentet inkrementellt (dvs. med inkrementell uppdateringsteknik). </p> <hr> <p> För att spara dokumentet inkrementellt bör vi öppna dokumentfilen för skrivning. Därför får Document inte initieras med InputStream utan med sökvägen till filen, som i följande kodexempel: Document doc = new Document("document.pdf"); // gör några ändringar och spara dokumentet inkrementellt doc.save(); </p> Om dokumentet initierades med InputStream är skrivning till InputStream omöjligt, så vi rekommenderar att använda separata metoder "save" för att spara dokumentet eller "saveIncrementally" för att spara dokumentet inkrementellt.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Sparar PDF-dokumentet inkrementellt till den angivna strömmen.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Sparar PDF-dokumentet inkrementellt till den angivna strömmen.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Sparar PDF-dokumentet inkrementellt till den angivna strömmen.

### saveXml {#saveXml-java.lang.String-}
Spara dokumentet till XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Skickar vissa sidor i dokumentet till dokumentenheten för bearbetning.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Skickar hela dokumentet till dokumentenheten för bearbetning.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Skickar hela dokumentet till dokumentenheten för bearbetning.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Skickar hela dokumentet till dokumentenheten för bearbetning.

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Meddelande om saknade teckensnitt vid bearbetning av dokument.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Ställer in flagga för att ange programbestämt teckensnitt vid avsaknad av teckensnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  |  |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Tillåter att slå samman sidinnehåll för att optimera dokumentstorleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBackground {#setBackground-java.awt.Color-}
Ställer in dokumentets bakgrundsfärg.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

Ställer in flagga som anger om dokumentfönstrets position ska centreras på skärmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Ställer in samling av dokument.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

Hämtar konverteringsparameter för pdf/ua-konverteraren (Konvertera endast metadata och dokumentkatalog om satt till true)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Ställer in filstorleksgränsen för att ladda en hel fil i minnet till standardvärdet 210 Mb.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Ställer in läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | boolean‑värde Som standard falskt. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Ställer in flagga som anger om dokumentfönstrets titelrad ska visa dokumenttiteln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Hämtar eller anger alternativ för hantering av dubbelsidig utskrift som ska användas när filen skrivs ut från utskriftsdialogen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | PrintDuplex‑element |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt där flaggan IsEmbedded är satt till true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Hämtar eller anger ett värde som indikerar om loggning av aviseringar ska aktiveras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Hämtar eller anger flagga som möjliggör att dokumentet delvis laddas ur minnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

Hämtar eller anger flagga för att hantera sanering av signaturfält.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Hämta och ställ in filstorleksgränsen för att ladda en hel fil i minnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Ställer in flagga som anger om dokumentfönstret måste ändras i storlek för att passa den första visade sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Kasta undantag om dokumentet sparas med ändringar och har signatur

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Ställer in flagga som anger om menyraden ska döljas när dokumentet är aktivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Ställ in flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Ställer in flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Hämtar eller anger flagga för att ignorera fel i källfiler. När sidor från källdokumentet kopieras till destinationsdokumentet stoppas kopieringsprocessen med ett undantag om vissa objekt i källfilerna är korrupta när flaggan är falsk. exempel: dest.Pages.Add(src.Pages); Om flaggan är satt till true ersätts korrupta objekt med tomma värden. Standardvärde: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Ställer in ett värde som indikerar om dokumentet är linjäriserat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Som standard stänger metoden save interna strömmar och frigör minnesresurser. Vi kan utföra vissa operationer och fortsätta arbeta med dokumentet efter att metoden save har anropats om parametern ManualDispose är aktiverad. Men det rekommenderas starkt att anropa dispose‑metoden när Document‑instansen inte längre behövs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| manualDisposeEnabled |  | boolean‑värde. (Standardvärde == falskt) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Ställer in sidläge och specificerar hur dokumentet ska visas vid avslut av helskärmsläge.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
<p> Ställer in åtgärden som utförs vid dokumentöppning. <p>

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Ställer in optimeringsflagga. När sidor läggs till i dokumentet slås lika resursströmmar i den resulterande filen samman till ett PDF‑objekt om denna flagga är satt. Detta möjliggör en minskning av den resulterande filstorleken men kan leda till långsammare körning och större minneskrav. Standardvärde: false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Ställer in sidinformationen. (endast för generator, fylls inte i vid läsning av dokumentet)

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Ställer in sidlayouten som ska användas när dokumentet öppnas.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Ställer in sidläge och specificerar hur dokumentet ska visas när det öppnas.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
public final void setPickTrayByPdfSize(boolean value)
```

Ställer in en flagga som anger om PDF‑sidans storlek ska användas för att välja inmatningspappersfacket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Ställer in alternativ för hantering av utskriftsskalning som ska användas när filen skrivs ut från utskriftsdialogen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | PrintDuplex‑element |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

Som standard är pdfa‑valideringsprocessen nödvändig för att uppdatera eller ta bort pdfa om vissa regler har brutits.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | booleskt värde |

### setTitle {#setTitle-java.lang.String-}
Ange titel för PDF‑dokument

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Ange XMP‑metadata för dokumentet.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Hämtar eller anger om dokumentet är pdfa-kompatibelt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Undertrycker uppdatering av innehållsdata för alla sidor. Innehållet uppdateras inte förrän ResumeUpdate anropas.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validera dokumentet till den angivna filen.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Validera dokumentet till den angivna filen.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validera dokumentet till den angivna filen.
