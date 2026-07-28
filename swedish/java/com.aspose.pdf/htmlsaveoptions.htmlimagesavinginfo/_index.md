---
title: "HtmlSaveOptions.HtmlImageSavingInfo"
linktitle: "HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass representerar en uppsättning data som är relaterade till sparande av externa bildresursfiler under PDF till HTML-konvertering."
type: docs
weight: 2070
url: /sv/java/com.aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo, com.aspose.pdf.SaveOptions.ResourceSavingInfo, com.aspose.pdf.HtmlSaveOptions.HtmlImageSavingInfo

```
public static class HtmlSaveOptions.HtmlImageSavingInfo extends SaveOptions.ResourceSavingInfo
```

Denna klass representerar en uppsättning data som är relaterade till sparande av externa bildresursfiler under PDF till HTML-konvertering.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [HtmlImageSavingInfo](#HtmlImageSavingInfo--) | skapar en ny instans av HtmlImageSavingInfo |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Anger för anpassad kod på vilken sida i den genererade uppsättningen av HTML‑sidfiler den sparade bilden tillhör. Om uppdelning på sidor är avstängd innehåller detta värde alltid '1' eftersom i så fall endast en HTML‑sida genereras. |
| [getImageType](#getImageType--) | Representerar typen av sparad bild som refereras i HTML. Sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras. |
| [getParentType](#getParentType--) | Sparad bild kan tillhöra HTML själv eller kan extraheras från SVG som är inbäddad i HTML. Denna egenskap kan tala till anpassad kod vilken typ av förälder den bearbetade bilden har. Den sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras med bilden (t.ex. kan anpassad kod bestämma var bilden ska sparas eller hur den ska refereras i förälderns innehåll). |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Anger för anpassad kod på vilken sida i det ursprungliga PDF‑dokumentet den sparade bilden tillhör. Eftersom det är möjligt att inte alla sidor i det ursprungliga dokumentet sparas, visar detta värde den aktuella sidnumret i original‑PDF‑filen. Om originalsidnumret av någon anledning är okänt, returneras alltid '1'. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Anger för anpassad kod på vilken sida i den genererade uppsättningen av HTML‑sidfiler den sparade bilden tillhör. Om uppdelning på sidor är avstängd innehåller detta värde alltid '1' eftersom i så fall endast en HTML‑sida genereras. |
| [setImageType](#setImageType-int-) | Representerar typen av sparad bild som refereras i HTML. Sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras. |
| [setParentType](#setParentType-int-) | Sparad bild kan tillhöra HTML själv eller kan extraheras från SVG som är inbäddad i HTML. Denna egenskap kan tala till anpassad kod vilken typ av förälder den bearbetade bilden har. Den sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras med bilden (t.ex. kan anpassad kod bestämma var bilden ska sparas eller hur den ska refereras i förälderns innehåll). |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Anger för anpassad kod på vilken sida i det ursprungliga PDF‑dokumentet den sparade bilden tillhör. Eftersom det är möjligt att inte alla sidor i det ursprungliga dokumentet sparas, visar detta värde den aktuella sidnumret i original‑PDF‑filen. Om originalsidnumret av någon anledning är okänt, returneras alltid '1'. |

### HtmlImageSavingInfo {#HtmlImageSavingInfo--}
```
public HtmlImageSavingInfo()
```

skapar en ny instans av HtmlImageSavingInfo

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Anger för anpassad kod på vilken sida i den genererade uppsättningen av HTML‑sidfiler den sparade bilden tillhör. Om uppdelning på sidor är avstängd innehåller detta värde alltid '1' eftersom i så fall endast en HTML‑sida genereras.

**Returns:**
int‑värde

### getImageType {#getImageType--}
```
public int getImageType()
```

Representerar typen av sparad bild som refereras i HTML. Sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras.

**Returns:**
HtmlImageType‑element @see HtmlImageType

### getParentType {#getParentType--}
```
public int getParentType()
```

Sparad bild kan tillhöra HTML själv eller kan extraheras från SVG som är inbäddad i HTML. Denna egenskap kan tala till anpassad kod vilken typ av förälder den bearbetade bilden har. Den sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras med bilden (t.ex. kan anpassad kod bestämma var bilden ska sparas eller hur den ska refereras i förälderns innehåll).

**Returns:**
ImageParentTypes‑element @see ImageParentTypes

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Anger för anpassad kod på vilken sida i det ursprungliga PDF‑dokumentet den sparade bilden tillhör. Eftersom det är möjligt att inte alla sidor i det ursprungliga dokumentet sparas, visar detta värde den aktuella sidnumret i original‑PDF‑filen. Om originalsidnumret av någon anledning är okänt, returneras alltid '1'.

**Returns:**
int‑värde

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Anger för anpassad kod på vilken sida i den genererade uppsättningen av HTML‑sidfiler den sparade bilden tillhör. Om uppdelning på sidor är avstängd innehåller detta värde alltid '1' eftersom i så fall endast en HTML‑sida genereras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlHostPageNumber |  | int‑värde |

### setImageType {#setImageType-int-}
```
public void setImageType(int imageType)
```

Representerar typen av sparad bild som refereras i HTML. Sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageType |  | HtmlImageType‑element @see HtmlImageType |

### setParentType {#setParentType-int-}
```
public void setParentType(int parentType)
```

Sparad bild kan tillhöra HTML själv eller kan extraheras från SVG som är inbäddad i HTML. Denna egenskap kan tala till anpassad kod vilken typ av förälder den bearbetade bilden har. Den sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras med bilden (t.ex. kan anpassad kod bestämma var bilden ska sparas eller hur den ska refereras i förälderns innehåll).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentType |  | ImageParentTypes‑element @see ImageParentTypes |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Anger för anpassad kod på vilken sida i det ursprungliga PDF‑dokumentet den sparade bilden tillhör. Eftersom det är möjligt att inte alla sidor i det ursprungliga dokumentet sparas, visar detta värde den aktuella sidnumret i original‑PDF‑filen. Om originalsidnumret av någon anledning är okänt, returneras alltid '1'.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfHostPageNumber |  | int‑värde |
