---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar renderingsalternativ"
type: docs
weight: 4150
url: /sv/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Representerar renderingsalternativ

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Initierar en ny instans av objektet {@code RenderingOptions}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Fontsubstitutionsalgoritmen följer dessa steg: 1. Om användaren explicit anger egenskapen DefaultFontName, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är angivet, sök bland teckensnitt som lagts till via {@code FontRepository.Sources}. 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en reserv, sök i systemet efter något teckensnitt som kan visa de erforderliga tecknen. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Hämtar streckkodoptimeringsläge. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Indikerar att alla teckensnitt kommer att konverteras till TTF Unicode-versioner. Detta är användbart av kompatibilitetsskäl och för att optimera teckensnittsanvändning, eftersom varje nytt TTF-teckensnitt inte kommer att innehålla alla symboler från källteckensnittet, utan endast de symboler som används i texten. |
| [getDefaultFontName](#getDefaultFontName--) | Hämtar/ställer in standardnamnet på teckensnitt som används för att ersätta saknade teckensnitt. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel för avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Hämtar eller ställer in högkvalitetsläge för interpolation. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Maximalt antal teckensnitt i teckensnittscache. Standardvärdet är 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Maximalt antal symboler i symbolcache. Standardvärdet är 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Hämtar eller ställer in läge för optimering av dimensioner. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Hämtar eller ställer in värden som används för att skala alla bilder på sidan så att de passar sidans bredd. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Hämtar ett läge där systemteckensnitt renderas nativt |
| [getUseFontHinting](#getUseFontHinting--) | Användning av denna flagga aktiverar font hinting-mekanismen. Font hinting är användningen av matematiska instruktioner för att justera visningen av ett konturteckensnitt. I vissa fall kan aktivering av denna flagga lösa problem med textläsbarhet. För närvarande kan användning av denna flagga endast ha effekt för TTF-teckensnitt, om dessa teckensnitt används i källdokumentet. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Hämtar en flagga som bestämmer om den nya bildbehandlingsmotorn används eller inte. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | Hämtar ett värde som används för att hoppa över fel under bearbetning av pdf‑fil. |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Fontsubstitutionsalgoritmen följer dessa steg: 1. Om användaren explicit anger egenskapen DefaultFontName, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är angivet, sök bland teckensnitt som lagts till via {@code FontRepository.Sources}. 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en reserv, sök i systemet efter något teckensnitt som kan visa de erforderliga tecknen. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Ställer in optimeringsläge för streckkod. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Indikerar att alla teckensnitt kommer att konverteras till TTF Unicode-versioner. Detta är användbart av kompatibilitetsskäl och för att optimera teckensnittsanvändning, eftersom varje nytt TTF-teckensnitt inte kommer att innehålla alla symboler från källteckensnittet, utan endast de symboler som används i texten. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Hämtar/ställer in standardnamnet på teckensnitt som används för att ersätta saknade teckensnitt. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel för avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard. |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Hämtar eller ställer in högkvalitetsläge för interpolation. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Maximalt antal teckensnitt i teckensnittscache. Standardvärdet är 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Maximalt antal symboler i symbolcache. Standardvärdet är 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Hämtar eller ställer in läge för optimering av dimensioner. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Hämtar eller ställer in värden som används för att skala alla bilder på sidan så att de passar sidans bredd. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Ställer in ett läge där systemteckensnitt renderas nativt. |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | Ställer in ett värde som används för att hoppa över fel under bearbetning av pdf‑fil. |
| [setUseFontHinting](#setUseFontHinting-boolean-) | Användning av denna flagga aktiverar font hinting-mekanismen. Font hinting är användningen av matematiska instruktioner för att justera visningen av ett konturteckensnitt. I vissa fall kan aktivering av denna flagga lösa problem med textläsbarhet. För närvarande kan användning av denna flagga endast ha effekt för TTF-teckensnitt, om dessa teckensnitt används i källdokumentet. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Ställer in en flagga som avgör om den nya bildbehandlingsmotorn används eller inte. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Initierar en ny instans av objektet {@code RenderingOptions}.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Fontsubstitutionsalgoritmen följer dessa steg: 1. Om användaren explicit anger egenskapen DefaultFontName, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är angivet, sök bland teckensnitt som lagts till via {@code FontRepository.Sources}. 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en reserv, sök i systemet efter något teckensnitt som kan visa de erforderliga tecknen.

**Returns:**
booleskt värde

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Hämtar streckkodoptimeringsläge.

**Returns:**
booleskt värde

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Indikerar att alla teckensnitt kommer att konverteras till TTF Unicode-versioner. Detta är användbart av kompatibilitetsskäl och för att optimera teckensnittsanvändning, eftersom varje nytt TTF-teckensnitt inte kommer att innehålla alla symboler från källteckensnittet, utan endast de symboler som används i texten.

**Returns:**
booleskt värde

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Hämtar/ställer in standardnamnet på teckensnitt som används för att ersätta saknade teckensnitt.

**Returns:**
String värde

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn.

**Returns:**
flyttalsvärde

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel för avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard.

**Returns:**
booleskt värde

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Hämtar eller ställer in högkvalitetsläge för interpolation.

**Returns:**
booleskt värde

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Maximalt antal teckensnitt i teckensnittscache. Standardvärdet är 10.

**Returns:**
int‑värde

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Maximalt antal symboler i symbolcache. Standardvärdet är 100.

**Returns:**
int‑värde

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Hämtar eller ställer in läge för optimering av dimensioner.

**Returns:**
booleskt värde

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Hämtar eller ställer in värden som används för att skala alla bilder på sidan så att de passar sidans bredd.

**Returns:**
booleskt värde @deprecated ScaleImagesToFitPageWidth är föråldrat.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Hämtar ett läge där systemteckensnitt renderas nativt

**Returns:**
booleskt värde

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

Användning av denna flagga aktiverar font hinting-mekanismen. Font hinting är användningen av matematiska instruktioner för att justera visningen av ett konturteckensnitt. I vissa fall kan aktivering av denna flagga lösa problem med textläsbarhet. För närvarande kan användning av denna flagga endast ha effekt för TTF-teckensnitt, om dessa teckensnitt används i källdokumentet.

**Returns:**
booleskt värde

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Hämtar en flagga som bestämmer om den nya bildbehandlingsmotorn används eller inte.

**Returns:**
booleskt värde @deprecated UseNewImagingEngine är föråldrat

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn.

**Returns:**
flyttalsvärde

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

Hämtar ett värde som används för att hoppa över fel under bearbetning av pdf‑fil.

**Returns:**
booleskt värde

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Ersätter teckensnitt vid behov för att säkerställa att alla tecken i texten kan visas. Fontsubstitutionsalgoritmen följer dessa steg: 1. Om användaren explicit anger egenskapen DefaultFontName, kontrollera om det angivna teckensnittet kan visa de önskade tecknen. 2. Om inget användardefinierat teckensnitt är angivet, sök bland teckensnitt som lagts till via {@code FontRepository.Sources}. 3. Analysera texten för att identifiera dess alfabet eller skript och föreslå teckensnittsnamn därefter. Försök att lokalisera och använda dessa teckensnitt från systemet. 4. Som en reserv, sök i systemet efter något teckensnitt som kan visa de erforderliga tecknen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Ställer in optimeringsläge för streckkod.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Indikerar att alla teckensnitt kommer att konverteras till TTF Unicode-versioner. Detta är användbart av kompatibilitetsskäl och för att optimera teckensnittsanvändning, eftersom varje nytt TTF-teckensnitt inte kommer att innehålla alla symboler från källteckensnittet, utan endast de symboler som används i texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Hämtar/ställer in standardnamnet på teckensnitt som används för att ersätta saknade teckensnitt.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Hämtar eller anger indikation på att fel relaterade till avsaknad av teckensnitt ska ignoreras. true – betyder att fel för avsaknad av teckensnitt ignoreras. Textsegment som refererar till felaktiga resurser hoppas över under bearbetning. false som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Hämtar eller ställer in högkvalitetsläge för interpolation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Maximalt antal teckensnitt i teckensnittscache. Standardvärdet är 10.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Maximalt antal symboler i symbolcache. Standardvärdet är 100.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Hämtar eller ställer in läge för optimering av dimensioner.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Hämtar eller ställer in värden som används för att skala alla bilder på sidan så att de passar sidans bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde @deprecated ScaleImagesToFitPageWidth är föråldrat. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Ställer in ett läge där systemteckensnitt renderas nativt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

Ställer in ett värde som används för att hoppa över fel under bearbetning av pdf‑fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

Användning av denna flagga aktiverar font hinting-mekanismen. Font hinting är användningen av matematiska instruktioner för att justera visningen av ett konturteckensnitt. I vissa fall kan aktivering av denna flagga lösa problem med textläsbarhet. För närvarande kan användning av denna flagga endast ha effekt för TTF-teckensnitt, om dessa teckensnitt används i källdokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Ställer in en flagga som avgör om den nya bildbehandlingsmotorn används eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde @deprecated UseNewImagingEngine är föråldrat |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

Hämtar eller ställer in ett värde som används för att öka eller minska bredden på rektangeln för AppendRectangle-operatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |
