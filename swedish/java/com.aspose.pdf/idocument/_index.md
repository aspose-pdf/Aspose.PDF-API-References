---
title: "IDocument"
linktitle: "IDocument"
second_title: "Aspose.PDF för Java API-referens"
description: "gränssnitt som representerar PDF-dokument"
type: docs
weight: 2230
url: /sv/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

gränssnitt som representerar PDF-dokument

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [afterImport](#afterImport--) | Enumerera alla registrerade annotationer och anropa AfterImport för var och en av dem. |
| [bindXml](#bindXml-java.io.InputStream-) | Binda xml till dokument |
| [bindXml](#bindXml-java.lang.String-) | Binda xml till dokument |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Binda xml/xsl till dokument |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Ändrar dokumentlösenord. |
| [check](#check-boolean-) | Validerar dokument. |
| [close](#close--) | Stänger alla resurser som används av detta dokument. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertera dokument till sökbart dokument. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Konvertera dokument och spara fel i den angivna filen. <p> Detta möjliggör att visa/dölja sökbar text på sidan. Standardvärdet är FALSE. Detta möjliggör att hämta originalbild från pdf. Standardvärdet är FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Konvertera dokument och spara fel i den angivna filen. <p> Detta möjliggör att visa/dölja sökbar text på sidan. Standardvärdet är FALSE. Detta möjliggör att hämta originalbild från pdf. Standardvärdet är FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Konvertera dokument med angivna konverteringsalternativ |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konvertera dokument och spara fel i den angivna filen. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konvertera dokument och spara fel i den angivna filen. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Intern metod |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras. |
| [decrypt](#decrypt--) | Dekrypterar dokumentet. |
| [dispose](#dispose--) | Föråldrad. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Krypterar dokumentet. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Krypterar dokumentet. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Krypterar dokumentet. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporterar alla dokumentanteckningar till XFDF-fil |
| [flatten](#flatten--) | Tar bort alla fält (och anteckningar) från dokumentet och placerar deras värden istället. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Tar bort alla fält från dokumentet och placerar deras värden istället. |
| [flattenTransparency](#flattenTransparency--) | Ersätter transparent innehåll med icke‑transparent raster‑ och vektorgrafik. |
| [freeMemory](#freeMemory--) | Rensar minne |
| [getActions](#getActions--) | Hämtar dokumentåtgärder. |
| [getBackground](#getBackground--) | Hämtar dokumentets bakgrundsfärg. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Returnerar objektvärde från katalogordbok. |
| [getCollection](#getCollection--) | Hämtar samling av dokument. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Hämtar säkerhetsinställningar om dokumentet är krypterat. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Hämtar en anpassad säkerhetshanterare. |
| [getDefaultCopier](#getDefaultCopier--) | Returnerar kopieringsverktyg som används för att kopiera sidor till detta dokument. |
| [getDestinations](#getDestinations--) | Hämtar samlingen av destinationer. |
| [getDirection](#getDirection--) | Hämtar läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [getDuplex](#getDuplex--) | Hämtar eller anger alternativ för hantering av dubbelsidig utskrift som ska användas när filen skrivs ut från utskriftsdialogen. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Hämtar samling av filer som är inbäddade i dokumentet. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt där flaggan IsEmbedded är satt till true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Hämtar eller anger flagga för att hantera sanering av signaturfält. |
| [getEngineDoc](#getEngineDoc--) | Instans av IPdfDocument som används för att komma åt intern dokumentstruktur. |
| [getFileName](#getFileName--) | Namnet på PDF‑filen som orsakade detta dokument |
| [getForm](#getForm--) | Hämtar Acro Form för dokumentet. |
| [getId](#getId--) | Hämtar ID:n. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Hämtar eller anger flagga för att ignorera fel i källfiler. |
| [getInfo](#getInfo--) | Hämtar dokumentinformation. |
| [getLogicalStructure](#getLogicalStructure--) | Hämtar dokumentets logiska struktur. |
| [getMetadata](#getMetadata--) | Dokumentmetadata. |
| [getMetadataStream](#getMetadataStream--) | Returnerar rå metadata‑ström |
| [getNamedDestinations](#getNamedDestinations--) | Samling av namngivna destinationer i dokumentet. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Hämtar sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| [getObjectById](#getObjectById-java.lang.String-) | Hämtar ett objekt med angivet ID i dokumentet. |
| [getOpenAction](#getOpenAction--) | Hämtar åtgärd som utförs vid dokumentöppning. |
| [getOptimizeSize](#getOptimizeSize--) | Hämtar optimeringsflagga. |
| [getOutlines](#getOutlines--) | Hämtar dokumentets konturer. |
| [getPageInfo](#getPageInfo--) | Hämtar sidinformation (endast för generator, fylls inte i vid läsning av dokumentet) |
| [getPageLabels](#getPageLabels--) | Hämtar sidetiketter i dokumentet. |
| [getPageLayout](#getPageLayout--) | Hämtar sidlayout som ska användas när dokumentet öppnas. |
| [getPageMode](#getPageMode--) | Hämtar sidläge, som specificerar hur dokumentet ska visas när det öppnas. |
| [getPages](#getPages--) | Hämtar samling av dokumentets sidor. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Hämtar behörigheter för dokumentet. |
| [getPrintScaling](#getPrintScaling--) | Hämtar alternativ för hantering av utskriftsskalning att använda när filen skrivs ut från utskriftsdialogen. |
| [getTaggedContent](#getTaggedContent--) | Hämtar åtkomst till TaggedPdf-innehåll. |
| [getVersion](#getVersion--) | Hämtar en version av Pdf från Pdf-filens rubrik. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Hämta XMP-metadata från dokumentet. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importerar annotationer från XFDF-fil till dokumentet. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Meddelande om saknade teckensnitt när dokument bearbetas |
| [isCenterWindow](#isCenterWindow--) | Hämtar flagga som anger om dokumentfönstrets position ska centreras på skärmen. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Hämtar flagga som anger om dokumentfönstrets titelrad ska visa dokumentets titel. |
| [isEncrypted](#isEncrypted--) | Hämtar krypteringsstatus för dokumentet. |
| [isFitWindow](#isFitWindow--) | Hämtar flagga som anger om dokumentfönstret måste ändras i storlek för att passa den första visade sidan. |
| [isHideMenubar](#isHideMenubar--) | Hämtar flagga som anger om menyraden ska döljas när dokumentet är aktivt. |
| [isHideToolBar](#isHideToolBar--) | Hämtar flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt. |
| [isHideWindowUI](#isHideWindowUI--) | Hämtar eller anger flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [isLinearized](#isLinearized--) | Hämtar eller anger ett värde som indikerar om dokumentet är linjäriserat. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Som standard stänger metoden save interna strömmar och frigör minnesresurser. Vi kan utföra vissa operationer och fortsätta arbeta med dokumentet efter metoden save om denna ManualDispose-parameter är aktiverad. |
| [isPdfaCompliant](#isPdfaCompliant--) | Hämtar om dokumentet är pdf/a-kompatibelt. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Hämtar om dokumentet är pdfua-kompatibelt. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Hämtar en flagga som anger om PDF-sidans storlek ska användas för att välja inmatningspappersfacket. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Hämtar eller anger om dokumentet är pdfa-kompatibelt. |
| [optimize](#optimize--) | Linjärisera dokumentet för att - öppna den första sidan så snabbt som möjligt; - visa nästa sida eller följa en länk till nästa sida så snabbt som möjligt; - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara datan först); - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats. |
| [optimizeResources](#optimizeResources--) | Optimera resurser i dokumentet: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimera resurser i dokumentet enligt definierad optimeringsstrategi. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organiserar sidträdsnoder i ett dokument i ett balanserat träd. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organiserar sidträdsnoder i ett dokument i ett balanserat träd. |
| [processParagraphs](#processParagraphs--) | Lagrar dokumentet i en ström. |
| [removeMetadata](#removeMetadata--) | Tar bort metadata från dokumentet. |
| [removePdfaCompliance](#removePdfaCompliance--) | Ta bort pdfa-efterlevnad från dokumentet |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Ta bort pdfUa-efterlevnad från dokumentet |
| [repair](#repair--) | Reparerar trasigt dokument. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Spara dokumentet inkrementellt (dvs. |
| [save](#save-java.io.OutputStream-) | Lagrar dokumentet i en ström. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Spara dokumentet |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ. |
| [save](#save-java.lang.String-) | Sparar dokumentet i den angivna filen. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Sparar PDF-dokumentet inkrementellt till den angivna strömmen. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Sparar PDF-dokumentet inkrementellt till den angivna strömmen. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Sparar PDF-dokumentet inkrementellt till den angivna strömmen. |
| [saveXml](#saveXml-java.lang.String-) | Spara dokumentet till XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Skickar vissa sidor i dokumentet till dokumentenheten för bearbetning. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Skickar hela dokumentet till dokumentenheten för bearbetning. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Ställer in flagga för att använda programbestämt teckensnitt om teckensnitt saknas. |
| [setBackground](#setBackground-java.awt.Color-) | Ställer in dokumentets bakgrundsfärg. |
| [setCenterWindow](#setCenterWindow-boolean-) | Ställer in flagga som anger om dokumentfönstrets position ska centreras på skärmen. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Ställer in samling av dokument. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Hämtar konverteringsparameter för pdf/ua-konverteraren (Konvertera endast metadata och dokumentkatalog om satt till true) |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Ställer in läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Ställer in flagga som anger om dokumentfönstrets titelrad ska visa dokumenttiteln. |
| [setDuplex](#setDuplex-int-) | Hämtar eller anger alternativ för hantering av dubbelsidig utskrift som ska användas när filen skrivs ut från utskriftsdialogen. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt där flaggan IsEmbedded är satt till true. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Hämtar eller anger flagga för att hantera sanering av signaturfält. |
| [setFitWindow](#setFitWindow-boolean-) | Ställer in flagga som anger om dokumentfönstret måste ändras i storlek för att passa den första visade sidan. |
| [setHideMenubar](#setHideMenubar-boolean-) | Ställer in flagga som anger om menyraden ska döljas när dokumentet är aktivt. |
| [setHideToolBar](#setHideToolBar-boolean-) | Ställ in flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Ställer in flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Ställer in ett värde som indikerar om dokumentet är linjäriserat. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Som standard stänger metoden save interna strömmar och frigör minnesresurser. Vi kan utföra vissa operationer och fortsätta arbeta med dokumentet efter att metoden save har anropats om denna ManualDispose‑parameter är aktiverad. Men det rekommenderas starkt att anropa dispose‑metoden när Document‑instansen inte längre behövs. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Ställer in sidläge och specificerar hur dokumentet ska visas vid avslut av helskärmsläge. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Ställer in åtgärden som utförs när dokumentet öppnas. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Ställer in optimeringsflagga. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Ställer in sidinformationen. (endast för generator, fylls inte i vid läsning av dokumentet) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Ställer in sidlayouten som ska användas när dokumentet öppnas. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Ställer in sidläge och specificerar hur dokumentet ska visas när det öppnas. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Ställer in en flagga som anger om PDF‑sidans storlek ska användas för att välja inmatningspappersfacket. |
| [setPrintScaling](#setPrintScaling-int-) | Ställer in alternativ för hantering av utskriftsskalning som ska användas när filen skrivs ut från utskriftsdialogen. |
| [setTitle](#setTitle-java.lang.String-) | Ange titel för PDF‑dokument |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Ange XMP‑metadata för dokumentet. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Hämtar eller anger om dokumentet är pdfa-kompatibelt. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validera dokumentet till den angivna filen. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validera dokumentet till den angivna filen. |

### afterImport {#afterImport--}
```
void afterImport()
```

Enumerera alla registrerade annotationer och anropa AfterImport för var och en av dem.

### bindXml {#bindXml-java.io.InputStream-}
Binda xml till dokument

### bindXml {#bindXml-java.lang.String-}
Binda xml till dokument

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Binda xml/xsl till dokument

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Ändrar dokumentlösenord.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
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
void close()
```

Stänger alla resurser som används av detta dokument.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertera dokument till sökbart dokument.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Konvertera dokument och spara fel i den angivna filen. <p> Detta möjliggör att visa/dölja sökbar text på sidan. Standardvärdet är FALSE. Detta möjliggör att hämta originalbild från pdf. Standardvärdet är FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Konvertera dokument och spara fel i den angivna filen. <p> Detta möjliggör att visa/dölja sökbar text på sidan. Standardvärdet är FALSE. Detta möjliggör att hämta originalbild från pdf. Standardvärdet är FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Konvertera dokument med angivna konverteringsalternativ

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konvertera dokument och spara fel i den angivna filen.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konvertera dokument och spara fel i den angivna filen.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Intern metod

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Konvertera dokument till sökbart dokument och hoppa över fel i hochr som inte kan konverteras.

### decrypt {#decrypt--}
```
void decrypt()
```

Dekrypterar dokumentet.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Föråldrad.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Krypterar dokumentet.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Krypterar dokumentet.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Krypterar dokumentet.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exporterar alla dokumentanteckningar till XFDF-fil

### flatten {#flatten--}
```
void flatten()
```

Tar bort alla fält (och anteckningar) från dokumentet och placerar deras värden istället.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Tar bort alla fält från dokumentet och placerar deras värden istället.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Ersätter transparent innehåll med icke‑transparent raster‑ och vektorgrafik.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Rensar minne

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Hämtar dokumentåtgärder.

**Returns:**
DocumentActionCollection object

### getBackground {#getBackground--}
```
Color getBackground()
```

Hämtar dokumentets bakgrundsfärg.

**Returns:**
java.awt.Color object

### getCatalogValue {#getCatalogValue-java.lang.String-}
Returnerar objektvärde från katalogordbok.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Hämtar samling av dokument.

**Returns:**
Collection object

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Hämtar säkerhetsinställningar om dokumentet är krypterat.

**Returns:**
CryptoAlgorithm element or null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Hämtar en anpassad säkerhetshanterare.

**Returns:**
ICustomSecurityHandler instance

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Returnerar kopieringsverktyg som används för att kopiera sidor till detta dokument.

**Returns:**
Copier object

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Hämtar samlingen av destinationer.

**Returns:**
DestinationCollection object

### getDirection {#getDirection--}
```
Direction getDirection()
```

Hämtar läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster).

**Returns:**
Direction element

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Hämtar eller anger alternativ för hantering av dubbelsidig utskrift som ska användas när filen skrivs ut från utskriftsdialogen.

**Returns:**
PrintDuplex‑element

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Hämtar samling av filer som är inbäddade i dokumentet.

**Returns:**
EmbeddedFileCollection‑objekt

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt där flaggan IsEmbedded är satt till true.

**Returns:**
booleskt värde

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

Hämtar eller anger flagga för att hantera sanering av signaturfält.

**Returns:**
booleskt värde

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instans av IPdfDocument som används för att komma åt intern dokumentstruktur.

**Returns:**
IPdfDocument‑objekt

### getFileName {#getFileName--}
```
String getFileName()
```

Namnet på PDF‑filen som orsakade detta dokument

**Returns:**
String-objekt

### getForm {#getForm--}
```
Form getForm()
```

Hämtar Acro Form för dokumentet.

**Returns:**
Form‑objekt

### getId {#getId--}
```
Id getId()
```

Hämtar ID:n.

**Returns:**
Id‑objekt

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Hämtar eller anger flagga för att ignorera fel i källfiler.

**Returns:**
booleskt värde

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Hämtar dokumentinformation.

**Returns:**
DocumentInfo‑objekt

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Hämtar dokumentets logiska struktur.

**Returns:**
RootElement‑objekt

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Dokumentmetadata.

**Returns:**
Metadata‑objekt

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Returnerar rå metadata‑ström

**Returns:**
IPdfStreamAccessor‑objekt

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Samling av namngivna destinationer i dokumentet.

**Returns:**
NamedDestinationCollection‑instans

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Hämtar sidläge, som specificerar hur dokumentet ska visas vid avslut av helskärmsläge.

**Returns:**
PageMode‑element

### getObjectById {#getObjectById-java.lang.String-}
Hämtar ett objekt med angivet ID i dokumentet.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Hämtar åtgärd som utförs vid dokumentöppning.

**Returns:**
IAppointment‑objekt

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Hämtar optimeringsflagga.

**Returns:**
booleskt värde

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Hämtar dokumentets konturer.

**Returns:**
OutlineCollection‑objekt

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Hämtar sidinformation (endast för generator, fylls inte i vid läsning av dokumentet)

**Returns:**
Sidans information.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Hämtar sidetiketter i dokumentet.

**Returns:**
PageLabelCollection‑objekt

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Hämtar sidlayout som ska användas när dokumentet öppnas.

**Returns:**
PageLayout‑element

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Hämtar sidläge, som specificerar hur dokumentet ska visas när det öppnas.

**Returns:**
PageMode‑element

### getPages {#getPages--}
```
PageCollection getPages()
```

Hämtar samling av dokumentets sidor.

**Returns:**
booleskt värde

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
PdfFormat‑element

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Hämtar behörigheter för dokumentet.

**Returns:**
int‑värde

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Hämtar alternativ för hantering av utskriftsskalning att använda när filen skrivs ut från utskriftsdialogen.

**Returns:**
PrintScaling‑element

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

Hämtar åtkomst till TaggedPdf-innehåll.

**Returns:**
ITaggedContent‑instans

### getVersion {#getVersion--}
```
String getVersion()
```

Hämtar en version av Pdf från Pdf-filens rubrik.

**Returns:**
String-objekt

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Hämta XMP-metadata från dokumentet.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importerar annotationer från XFDF-fil till dokumentet.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Meddelande om saknade teckensnitt när dokument bearbetas

**Returns:**
booleskt värde

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Hämtar flagga som anger om dokumentfönstrets position ska centreras på skärmen.

**Returns:**
booleskt värde

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt.

**Returns:**
boolean‑värde Som standard falskt.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Hämtar flagga som anger om dokumentfönstrets titelrad ska visa dokumentets titel.

**Returns:**
booleskt värde

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Hämtar krypteringsstatus för dokumentet.

**Returns:**
booleskt värde

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Hämtar flagga som anger om dokumentfönstret måste ändras i storlek för att passa den första visade sidan.

**Returns:**
booleskt värde

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Hämtar flagga som anger om menyraden ska döljas när dokumentet är aktivt.

**Returns:**
booleskt värde

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Hämtar flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt.

**Returns:**
booleskt värde

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Hämtar eller anger flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt.

**Returns:**
booleskt värde

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Hämtar eller anger ett värde som indikerar om dokumentet är linjäriserat.

**Returns:**
booleskt värde

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

Som standard stänger metoden save interna strömmar och frigör minnesresurser. Vi kan utföra vissa operationer och fortsätta arbeta med dokumentet efter metoden save om denna ManualDispose-parameter är aktiverad.

**Returns:**
boolean‑värde. (Standardvärde == falskt)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Hämtar om dokumentet är pdf/a-kompatibelt.

**Returns:**
booleskt värde

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Hämtar om dokumentet är pdfua-kompatibelt.

**Returns:**
booleskt värde

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

Hämtar en flagga som anger om PDF-sidans storlek ska användas för att välja inmatningspappersfacket.

**Returns:**
booleskt värde

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Hämtar eller anger om dokumentet är pdfa-kompatibelt.

**Returns:**
booleskt värde

### optimize {#optimize--}
```
void optimize()
```

Linjärisera dokumentet för att - öppna den första sidan så snabbt som möjligt; - visa nästa sida eller följa en länk till nästa sida så snabbt som möjligt; - visa sidan inkrementellt när den anländer när data för en sida levereras över en långsam kanal (visa den mest användbara datan först); - tillåta användarinteraktion, såsom att följa en länk, att utföras även innan hela sidan har mottagits och visats.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Optimera resurser i dokumentet: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimera resurser i dokumentet enligt definierad optimeringsstrategi.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Organiserar sidträdsnoder i ett dokument i ett balanserat träd.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organiserar sidträdsnoder i ett dokument i ett balanserat träd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodesNumInSubtrees |  | Önskat antal undernoder. Standardvärdet är tio. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Lagrar dokumentet i en ström.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Tar bort metadata från dokumentet.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Ta bort pdfa-efterlevnad från dokumentet

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Ta bort pdfUa-efterlevnad från dokumentet

### repair {#repair--}
```
void repair()
```

Reparerar trasigt dokument.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Spara dokumentet inkrementellt (dvs.

### save {#save-java.io.OutputStream-}
Lagrar dokumentet i en ström.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Spara dokumentet

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ.

### save {#save-java.lang.String-}
Sparar dokumentet i den angivna filen.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Sparar dokumentet med ett nytt namn och ställer in dess sparalternativ.

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

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Ställer in flagga för att använda programbestämt teckensnitt om teckensnitt saknas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | booleskt värde |

### setBackground {#setBackground-java.awt.Color-}
Ställer in dokumentets bakgrundsfärg.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
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
void setConvertMetadataAndCatalogOnly(boolean value)
```

Hämtar konverteringsparameter för pdf/ua-konverteraren (Konvertera endast metadata och dokumentkatalog om satt till true)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Ställer in läsriktning för text: L2R (vänster till höger) eller R2L (höger till vänster).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

Många operationer med teckensnitt kan inte utföras om dessa operationer är förbjudna av licensen för detta teckensnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | boolean‑värde Som standard falskt. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Ställer in flagga som anger om dokumentfönstrets titelrad ska visa dokumenttiteln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Hämtar eller anger alternativ för hantering av dubbelsidig utskrift som ska användas när filen skrivs ut från utskriftsdialogen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | PrintDuplex‑element |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Egenskap som deklarerar att dokumentet måste bädda in alla standard‑Type1‑typsnitt där flaggan IsEmbedded är satt till true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

Hämtar eller anger flagga för att hantera sanering av signaturfält.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Ställer in flagga som anger om dokumentfönstret måste ändras i storlek för att passa den första visade sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Ställer in flagga som anger om menyraden ska döljas när dokumentet är aktivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Ställ in flagga som anger om verktygsfältet ska döljas när dokumentet är aktivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Ställer in flagga som anger om användargränssnittselement ska döljas när dokumentet är aktivt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Ställer in ett värde som indikerar om dokumentet är linjäriserat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Som standard stänger metoden save interna strömmar och frigör minnesresurser. Vi kan utföra vissa operationer och fortsätta arbeta med dokumentet efter att metoden save har anropats om denna ManualDispose‑parameter är aktiverad. Men det rekommenderas starkt att anropa dispose‑metoden när Document‑instansen inte längre behövs.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| manualDisposeEnabled |  | boolean‑värde. (Standardvärde == falskt) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Ställer in sidläge och specificerar hur dokumentet ska visas vid avslut av helskärmsläge.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Ställer in åtgärden som utförs när dokumentet öppnas.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
void setOptimizeSize(boolean value)
```

Ställer in optimeringsflagga.

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
void setPickTrayByPdfSize(boolean value)
```

Ställer in en flagga som anger om PDF‑sidans storlek ska användas för att välja inmatningspappersfacket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Ställer in alternativ för hantering av utskriftsskalning som ska användas när filen skrivs ut från utskriftsdialogen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | PrintDuplex‑element |

### setTitle {#setTitle-java.lang.String-}
Ange titel för PDF‑dokument

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Ange XMP‑metadata för dokumentet.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Hämtar eller anger om dokumentet är pdfa-kompatibelt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validera dokumentet till den angivna filen.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validera dokumentet till den angivna filen.
