---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för åtkomst till metadata i PDF-dokument."
type: docs
weight: 490
url: /sv/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

Representerar en klass för åtkomst till metadata i PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initierar fasaden. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initierar fasaden. |
| [clearInfo](#clearInfo--) | Rensar all metainformation i PDF-dokumentet. |
| [close](#close--) | Stänger alla resurser som används av detta dokument. |
| [dispose](#dispose--) | Stänger alla resurser som används av denna instans. Denna metod är föråldrad, använd close() istället. |
| [getAuthor](#getAuthor--) | Hämtar författarinformationen för PDF-dokumentet. |
| [getCreationDate](#getCreationDate--) | Hämtar skapandedatuminformationen för PDF-dokumentet. |
| [getCreator](#getCreator--) | Hämtar skaparinformationen för PDF-dokumentet. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | Hämtar behörighetsinställningarna för PDF-dokumentet. |
| [getHeader](#getHeader--) | <p> Hämtar den anpassade informationen för PDF-dokumentet. </p> |
| [getInputFile](#getInputFile--) | Hämtar indatafilen. |
| [getInputStream](#getInputStream--) | Hämtar indataströmmen. |
| [getKeywords](#getKeywords--) | Hämtar nyckelordsinformationen för PDF-dokumentet. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | Hämtar anpassad information för PDF-dokumentet med egenskapsnamn. Om ingen egenskap matchar namnet returneras en tom sträng. |
| [getModDate](#getModDate--) | Hämtar ändringsdatuminformationen för PDF-dokumentet. |
| [getNumberOfPages](#getNumberOfPages--) | Hämtar antalet sidor i dokumentet. |
| [getPageHeight](#getPageHeight-int-) | Hämtar höjden på den angivna sidan. |
| [getPageRotation](#getPageRotation-int-) | Hämtar rotationen på den angivna sidan. |
| [getPageWidth](#getPageWidth-int-) | Hämtar bredden på den angivna sidan. |
| [getPageXOffset](#getPageXOffset-int-) | Hämtar den horisontella förskjutningen för det angivna sidvisningsområdet. |
| [getPageYOffset](#getPageYOffset-int-) | Hämtar den vertikala förskjutningen för det angivna sidvisningsområdet. |
| [getPasswordType](#getPasswordType--) | Returnerar typen av lösenord som skickades för att skapa PdfFileInfo-instansen. Se möjliga värden i {@code PasswordType}. Observera att PDF-dokumentet kan öppnas med både användarlösenord (eller öppningslösenord) och ägarlösenord (eller behörighets- / redigeringslösenord). |
| [getPdfVersion](#getPdfVersion--) | Hämtar versionsinformationen för PDF-dokumentet. |
| [getProducer](#getProducer--) | Hämtar producentinformationen för PDF-dokumentet. |
| [getSubject](#getSubject--) | Hämtar ämnesinformationen för PDF-dokumentet. |
| [getTitle](#getTitle--) | Hämtar titelinformationen för PDF-dokumentet. |
| [getUseStrictValidation](#getUseStrictValidation--) | Använder strikta valideringsregler via egenskapen {@code IsPdfFile}({@link #isPdfFile}). |
| [hasCollection](#hasCollection--) | Returnerar true om den aktuella inmatningsfilen är en 'Portfolio'-fil som innehåller en samling PDF-filer. |
| [hasEditPassword](#hasEditPassword--) | Returnerar true om ett lösenord krävs för att ändra behörigheter eller dokumentets säkerhetsegenskap. Observera att denna egenskap endast kan läsas om ett giltigt lösenord angavs i {@code PdfFileInfo}-konstruktorn. Om PasswordType är Inaccessible (vilket betyder att ett ogiltigt lösenord angavs) kommer läsning av denna egenskap att misslyckas med {@code InvalidPasswordException}. |
| [hasOpenPassword](#hasOpenPassword--) | Returnerar true om ett lösenord krävs för att öppna ett lösenordsskyddat PDF-dokument. |
| [isEncrypted](#isEncrypted--) | Kontrollerar om PDF-dokumentet är krypterat. |
| [isPdfFile](#isPdfFile--) | Kontrollerar om källinmatningen är en giltig PDF-fil. |
| [save](#save-java.io.OutputStream-) | Sparar PDF-dokumentet till den angivna filen. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | Spara uppdaterat PDF-dokument i den angivna strömmen. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | Spara uppdaterat PDF-dokument i den angivna filen. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | Ändrar de egenskaper som specificerats explicit genom att ange filinformation, andra egenskaper förblir. |
| [setAuthor](#setAuthor-java.lang.String-) | Ställer in författarinformationen för PDF-dokumentet. |
| [setCreationDate](#setCreationDate-java.lang.String-) | Ställer in skapelsedatuminformationen för PDF-dokumentet. |
| [setCreator](#setCreator-java.lang.String-) | Ställer in skaparinformationen för PDF-dokumentet. |
| [setHeader](#setHeader-java.util.Map-) | Ställer in den anpassade informationen för PDF-dokumentet. |
| [setInputFile](#setInputFile-java.lang.String-) | Ställer in inmatningsfilen. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Ställer in inmatningsströmmen. |
| [setKeywords](#setKeywords-java.lang.String-) | Ställer in nyckelordsinformationen för PDF-dokumentet. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | Ställer in anpassad information för PDF-dokumentet. |
| [setModDate](#setModDate-java.lang.String-) | Ställer in ModDate-datinformationen för PDF-dokumentet. |
| [setSubject](#setSubject-java.lang.String-) | Ställer in ämnesinformationen för PDF-dokumentet. |
| [setTitle](#setTitle-java.lang.String-) | Ställer in titelinformationen för PDF-dokumentet. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | Använder strikta valideringsregler via egenskapen {@code IsPdfFile}({@link #isPdfFile}). |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Initierar en ny instans av klassen com.aspose.pdf.facades.PdfFileInfo med standardvärden.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initierar fasaden.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initierar fasaden.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

Rensar all metainformation i PDF-dokumentet.

### close {#close--}
```
public void close()
```

Stänger alla resurser som används av detta dokument.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Stänger alla resurser som används av denna instans. Denna metod är föråldrad, använd close() istället.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Hämtar författarinformationen för PDF-dokumentet.

**Returns:**
String värde

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

Hämtar skapandedatuminformationen för PDF-dokumentet.

**Returns:**
String värde

### getCreator {#getCreator--}
```
public String getCreator()
```

Hämtar skaparinformationen för PDF-dokumentet.

**Returns:**
String värde

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

Hämtar behörighetsinställningarna för PDF-dokumentet.

**Returns:**
PDF-dokumentets privileginställningar.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> Hämtar den anpassade informationen för PDF-dokumentet. </p>

**Returns:**
{@code Map<String, String>}-objekt

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Hämtar indatafilen.

**Returns:**
String värde

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

Hämtar indataströmmen.

**Returns:**
InputStream-objekt

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Hämtar nyckelordsinformationen för PDF-dokumentet.

**Returns:**
String värde

### getMetaInfo {#getMetaInfo-java.lang.String-}
Hämtar anpassad information för PDF-dokumentet med egenskapsnamn. Om ingen egenskap matchar namnet returneras en tom sträng.

### getModDate {#getModDate--}
```
public String getModDate()
```

Hämtar ändringsdatuminformationen för PDF-dokumentet.

**Returns:**
String värde

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

Hämtar antalet sidor i dokumentet.

**Returns:**
int‑värde

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

Hämtar höjden på den angivna sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNum |  | Sidnummer. |

**Returns:**
Sidans höjd.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

Hämtar rotationen på den angivna sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNum |  | Sidnummer. |

**Returns:**
Sidans rotation. Värdet kan vara 0,90,180,270.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

Hämtar bredden på den angivna sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNum |  | Sidnummer. |

**Returns:**
Sidans bredd.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

Hämtar den horisontella förskjutningen för det angivna sidvisningsområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNum |  | Sidnummer. |

**Returns:**
Det horisontella avståndet från sidans vänstra kant.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

Hämtar den vertikala förskjutningen för det angivna sidvisningsområdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNum |  | Sidnummer. |

**Returns:**
Det vertikala avståndet för sidans visningsområde.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

Returnerar typen av lösenord som skickades för att skapa PdfFileInfo-instansen. Se möjliga värden i {@code PasswordType}. Observera att PDF-dokumentet kan öppnas med både användarlösenord (eller öppningslösenord) och ägarlösenord (eller behörighets- / redigeringslösenord).

**Returns:**
PasswordType-element @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

Hämtar versionsinformationen för PDF-dokumentet.

**Returns:**
Versionssträngen.

### getProducer {#getProducer--}
```
public String getProducer()
```

Hämtar producentinformationen för PDF-dokumentet.

**Returns:**
String värde

### getSubject {#getSubject--}
```
public String getSubject()
```

Hämtar ämnesinformationen för PDF-dokumentet.

**Returns:**
String värde

### getTitle {#getTitle--}
```
public String getTitle()
```

Hämtar titelinformationen för PDF-dokumentet.

**Returns:**
String värde

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

Använder strikta valideringsregler via egenskapen {@code IsPdfFile}({@link #isPdfFile}).

**Returns:**
booleskt värde

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

Returnerar true om den aktuella inmatningsfilen är en 'Portfolio'-fil som innehåller en samling PDF-filer.

**Returns:**
booleskt värde

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

Returnerar true om ett lösenord krävs för att ändra behörigheter eller dokumentets säkerhetsegenskap. Observera att denna egenskap endast kan läsas om ett giltigt lösenord angavs i {@code PdfFileInfo}-konstruktorn. Om PasswordType är Inaccessible (vilket betyder att ett ogiltigt lösenord angavs) kommer läsning av denna egenskap att misslyckas med {@code InvalidPasswordException}.

**Returns:**
booleskt värde

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

Returnerar true om ett lösenord krävs för att öppna ett lösenordsskyddat PDF-dokument.

**Returns:**
booleskt värde

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Kontrollerar om PDF-dokumentet är krypterat.

**Returns:**
booleskt värde

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

Kontrollerar om källinmatningen är en giltig PDF-fil.

**Returns:**
booleskt värde

### save {#save-java.io.OutputStream-}
Sparar PDF-dokumentet till den angivna filen.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
Spara uppdaterat PDF-dokument i den angivna strömmen.

### saveNewInfo {#saveNewInfo-java.lang.String-}
Spara uppdaterat PDF-dokument i den angivna filen.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
Ändrar de egenskaper som specificerats explicit genom att ange filinformation, andra egenskaper förblir.

### setAuthor {#setAuthor-java.lang.String-}
Ställer in författarinformationen för PDF-dokumentet.

### setCreationDate {#setCreationDate-java.lang.String-}
Ställer in skapelsedatuminformationen för PDF-dokumentet.

### setCreator {#setCreator-java.lang.String-}
Ställer in skaparinformationen för PDF-dokumentet.

### setHeader {#setHeader-java.util.Map-}
Ställer in den anpassade informationen för PDF-dokumentet.

### setInputFile {#setInputFile-java.lang.String-}
Ställer in inmatningsfilen.

### setInputStream {#setInputStream-java.io.InputStream-}
Ställer in inmatningsströmmen.

### setKeywords {#setKeywords-java.lang.String-}
Ställer in nyckelordsinformationen för PDF-dokumentet.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
Ställer in anpassad information för PDF-dokumentet.

### setModDate {#setModDate-java.lang.String-}
Ställer in ModDate-datinformationen för PDF-dokumentet.

### setSubject {#setSubject-java.lang.String-}
Ställer in ämnesinformationen för PDF-dokumentet.

### setTitle {#setTitle-java.lang.String-}
Ställer in titelinformationen för PDF-dokumentet.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

Använder strikta valideringsregler via egenskapen {@code IsPdfFile}({@link #isPdfFile}).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
