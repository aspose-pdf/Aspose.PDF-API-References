---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för inläsning/import av HTML‑fil till PDF‑dokument."
type: docs
weight: 1960
url: /sv/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

Representerar alternativ för inläsning/import av HTML‑fil till PDF‑dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Skapar laddningsalternativ för att konvertera html till pdf-dokument med tom basväg. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Skapar laddningsalternativ för att konvertera html till pdf-dokument med tom basväg. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBasePath](#getBasePath--) | Basvägen/url för html-filen. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.PDF i molnet är direkt åtkomst till refererade filer omöjlig: i sådant fall bör viss kundkod som placerats i en speciell metod användas, och en delegat som refererar till den metoden ska tilldelas detta attribut. |
| [getHtmlMediaType](#getHtmlMediaType--) | Hämtar eller anger möjliga mediatyper som används under rendering. |
| [getInputEncoding](#getInputEncoding--) | Hämtar attributet som specificerar kodningen som används för detta dokument vid parsning. Om detta attribut är null bestäms kodningen från dokumentets teckenuppsättning. |
| [getPageInfo](#getPageInfo--) | Hämtar dokumentets sidinformation |
| [getPageLayoutOption](#getPageLayoutOption--) | Hämtar eller anger layoutalternativ. |
| [isEmbedFonts](#isEmbedFonts--) | Hämtar eller anger inbäddning av teckensnitt i resulterande dokument |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | Hämtar eller anger flaggan som specificerar att @page-regler definierade i css kommer att åsidosätta värden definierade i PageInfo. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Hämtar eller anger rendering av hela dokumentet till en enda sida |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Hämtar eller anger inbäddning av teckensnitt i resulterande dokument |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Hämtar eller anger möjliga mediatyper som används under rendering. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Anger attributet som specificerar kodningen som används för detta dokument vid parsning. Om detta attribut är null bestäms kodningen från dokumentets teckenuppsättning. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Anger dokumentets sidinformation |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Hämtar eller anger layoutalternativ. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | Hämtar eller anger flaggan som specificerar att @page-regler definierade i css kommer att åsidosätta värden definierade i PageInfo. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Hämtar eller anger rendering av hela dokumentet till en enda sida |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Skapar laddningsalternativ för att konvertera html till pdf-dokument med tom basväg.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Skapar laddningsalternativ för att konvertera html till pdf-dokument med tom basväg.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Basvägen/url för html-filen.

**Returns:**
String värde

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.PDF i molnet är direkt åtkomst till refererade filer omöjlig: i sådant fall bör viss kundkod som placerats i en speciell metod användas, och en delegat som refererar till den metoden ska tilldelas detta attribut.

**Returns:**
ResourceLoadingStrategy-instans

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Hämtar eller anger möjliga mediatyper som används under rendering.

**Returns:**
HtmlMediaType-element

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Hämtar attributet som specificerar kodningen som används för detta dokument vid parsning. Om detta attribut är null bestäms kodningen från dokumentets teckenuppsättning.

**Returns:**
String värde

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Hämtar dokumentets sidinformation

**Returns:**
sidinformation

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Hämtar eller anger layoutalternativ.

**Returns:**
HtmlPageLayoutOption-element @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Hämtar eller anger inbäddning av teckensnitt i resulterande dokument

**Returns:**
booleskt värde

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

Hämtar eller anger flaggan som specificerar att @page-regler definierade i css kommer att åsidosätta värden definierade i PageInfo.

**Returns:**
booleskt värde

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Hämtar eller anger rendering av hela dokumentet till en enda sida

**Returns:**
booleskt värde

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Hämtar eller anger inbäddning av teckensnitt i resulterande dokument

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Hämtar eller anger möjliga mediatyper som används under rendering.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Anger attributet som specificerar kodningen som används för detta dokument vid parsning. Om detta attribut är null bestäms kodningen från dokumentets teckenuppsättning.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Anger dokumentets sidinformation

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Hämtar eller anger layoutalternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | HtmlPageLayoutOption-element @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

Hämtar eller anger flaggan som specificerar att @page-regler definierade i css kommer att åsidosätta värden definierade i PageInfo.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Hämtar eller anger rendering av hela dokumentet till en enda sida

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
