---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Aspose.PDF för Java API-referens"
description: "Om egenskapen SplitToPages i HtmlSaveOptions är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konvertering av PDF till HTML. Denna klass representerar en uppsättning av."
type: docs
weight: 2100
url: /sv/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

Om egenskapen SplitToPages i HtmlSaveOptions är aktiverad, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konvertering av PDF till HTML. Denna klass representerar en uppsättning data som är relaterade till anpassad sparning av en HTML-sidas markup under konvertering av PDF till HTML

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getContentStream](#getContentStream--) | Sätts av konverteraren. Representerar sparad HTML som ström |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap innehåller ordningsnumret för den sparade HTML-sidans fil. Egenskapen kan användas i logiken för anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara HTML-sidan, och om sidindelning är avstängd innehåller detta värde alltid '1' eftersom i så fall genereras endast en stor HTML-sida för hela källdokumentet. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap talar till anpassad kod om från vilken sida i original‑PDF‑filen det sparade HTML-markupet skapades. Om originalsidnumret av någon anledning är okänt eller SplitOnPages=false, innehåller denna egenskap alltid '0' vilket signalerar att konverteraren inte kan ange exakt original‑PDF‑sidnummer för den levererade HTML‑markup‑filen. |
| [getSupposedFileName](#getSupposedFileName--) | Sätts av konverteraren. Antaget filnamn som går från konverteraren till kod för anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara innehållet. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Skall sättas i anpassad kod när det behövs. Detta flagga måste sättas till "true" i anpassad kod om av någon anledning det levererade html-markupet ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så, om detta flagga sätts i anpassad kod betyder det att anpassad kod inte bearbetade den refererade filen och konverteraren måste hantera den själv |
| [setContentStream](#setContentStream-java.io.InputStream-) | Sätts av konverteraren. Representerar sparad HTML som ström |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Skall sättas i anpassad kod när det behövs. Detta flagga måste sättas till "true" i anpassad kod om av någon anledning det levererade html-markupet ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så, om detta flagga sätts i anpassad kod betyder det att anpassad kod inte bearbetade den refererade filen och konverteraren måste hantera den själv |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap innehåller ordningsnumret för den sparade HTML-sidans fil. Egenskapen kan användas i logiken för anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara HTML-sidan, och om sidindelning är avstängd innehåller detta värde alltid '1' eftersom i så fall genereras endast en stor HTML-sida för hela källdokumentet. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap talar till anpassad kod om från vilken sida i original‑PDF‑filen det sparade HTML-markupet skapades. Om originalsidnumret av någon anledning är okänt eller SplitOnPages=false, innehåller denna egenskap alltid '0' vilket signalerar att konverteraren inte kan ange exakt original‑PDF‑sidnummer för den levererade HTML‑markup‑filen. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Sätts av konverteraren. Antaget filnamn som går från konverteraren till kod för anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara innehållet. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Sätts av konverteraren. Representerar sparad HTML som ström

**Returns:**
InputStream‑instans

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap innehåller ordningsnumret för den sparade HTML-sidans fil. Egenskapen kan användas i logiken för anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara HTML-sidan, och om sidindelning är avstängd innehåller detta värde alltid '1' eftersom i så fall genereras endast en stor HTML-sida för hela källdokumentet.

**Returns:**
int‑värde

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap talar till anpassad kod om från vilken sida i original‑PDF‑filen det sparade HTML-markupet skapades. Om originalsidnumret av någon anledning är okänt eller SplitOnPages=false, innehåller denna egenskap alltid '0' vilket signalerar att konverteraren inte kan ange exakt original‑PDF‑sidnummer för den levererade HTML‑markup‑filen.

**Returns:**
int‑värde

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Sätts av konverteraren. Antaget filnamn som går från konverteraren till kod för anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara innehållet.

**Returns:**
String värde

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Skall sättas i anpassad kod när det behövs. Detta flagga måste sättas till "true" i anpassad kod om av någon anledning det levererade html-markupet ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så, om detta flagga sätts i anpassad kod betyder det att anpassad kod inte bearbetade den refererade filen och konverteraren måste hantera den själv

**Returns:**
booleskt värde

### setContentStream {#setContentStream-java.io.InputStream-}
Sätts av konverteraren. Representerar sparad HTML som ström

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Skall sättas i anpassad kod när det behövs. Detta flagga måste sättas till "true" i anpassad kod om av någon anledning det levererade html-markupet ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så, om detta flagga sätts i anpassad kod betyder det att anpassad kod inte bearbetade den refererade filen och konverteraren måste hantera den själv

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| customProcessingCancelled |  | booleskt värde |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap innehåller ordningsnumret för den sparade HTML-sidans fil. Egenskapen kan användas i logiken för anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara HTML-sidan, och om sidindelning är avstängd innehåller detta värde alltid '1' eftersom i så fall genereras endast en stor HTML-sida för hela källdokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlHostPageNumber |  | int‑värde |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap talar till anpassad kod om från vilken sida i original‑PDF‑filen det sparade HTML-markupet skapades. Om originalsidnumret av någon anledning är okänt eller SplitOnPages=false, innehåller denna egenskap alltid '0' vilket signalerar att konverteraren inte kan ange exakt original‑PDF‑sidnummer för den levererade HTML‑markup‑filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfHostPageNumber |  | int‑värde |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Sätts av konverteraren. Antaget filnamn som går från konverteraren till kod för anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara innehållet.
