---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass representerar sparalternativ för sparning som använder ett enhetligt konverteringssätt (med enhetlig intern dokumentmodell)"
type: docs
weight: 5420
url: /sv/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

Denna klass representerar sparalternativ för sparning som använder ett enhetligt konverteringssätt (med enhetlig intern dokumentmodell)

## Fält

| Fält | Beskrivning |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | Bearbeta sidor i några trådar. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | Representerar en intern processor för förloppshändelser som arbetar under konvertering och översätter konverteringshändelser från interna konverteringssteg till externa totala förloppshändelser. Klassen sänder också händelser som möjliggör att frigöra resurser som inte längre behövs. Denna interna klass hanterar händelser för PDF till APS och APS till [Other format] för att beräkna totalt förlopp och informera kundens kod om dessa totala förloppshändelser. Klassen använder två typer av händelser: ApsToExternal-modellkonvertering och händelser för konvertering Pdf till APS för att generera totala förloppshändelser. Export har tre steg: 1) Pdf till Aps 2) Aps-igenkänning 3) Aps-export till målformat. Konstruktorn tillåter att justera hur många sidor som konverteras och vilken ungefärlig del av detta eller det steget som utgör den totala förloppet. |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF-dokument med OCR-underlag. Värde: {@code true} text kommer att extraheras i resultatsdokumentet; annars {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Ibland innehåller PDF-filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade nära varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS-format) ibland generera synliga gränser mellan delar av bakgrundsbilderna, eftersom deras teknik för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som om det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF-dokument med OCR-underlag. </p>Värde: {@code true} text kommer att extraheras i resultatsdokumentet; annars {@code false}. <hr> Standardvärde == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Representerar en intern processor för förloppshändelser som arbetar under konvertering och översätter konverteringshändelser från interna konverteringssteg till externa totala förloppshändelser. Klassen sänder också händelser som möjliggör att frigöra resurser som inte längre behövs. Denna interna klass hanterar händelser för PDF till APS och APS till [Other format] för att beräkna totalt förlopp och informera kundens kod om dessa totala förloppshändelser. Klassen använder två typer av händelser: ApsToExternal-modellkonvertering och händelser för konvertering Pdf till APS för att generera totala förloppshändelser. Export har tre steg: 1) Pdf till Aps 2) Aps-igenkänning 3) Aps-export till målformat. Konstruktorn tillåter att justera hur många sidor som konverteras och vilken ungefärlig del av detta eller det steget som utgör den totala förloppet. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Ibland innehåller PDF-filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade nära varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS-format) ibland generera synliga gränser mellan delar av bakgrundsbilderna, eftersom deras teknik för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som om det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

Bearbeta sidor i några trådar.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

Representerar en intern processor för förloppshändelser som arbetar under konvertering och översätter konverteringshändelser från interna konverteringssteg till externa totala förloppshändelser. Klassen sänder också händelser som möjliggör att frigöra resurser som inte längre behövs. Denna interna klass hanterar händelser för PDF till APS och APS till [Other format] för att beräkna totalt förlopp och informera kundens kod om dessa totala förloppshändelser. Klassen använder två typer av händelser: ApsToExternal-modellkonvertering och händelser för konvertering Pdf till APS för att generera totala förloppshändelser. Export har tre steg: 1) Pdf till Aps 2) Aps-igenkänning 3) Aps-export till målformat. Konstruktorn tillåter att justera hur många sidor som konverteras och vilken ungefärlig del av detta eller det steget som utgör den totala förloppet.

**Returns:**
ConversionProgressEventsTranslator-instans

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF-dokument med OCR-underlag. Värde: {@code true} text kommer att extraheras i resultatsdokumentet; annars {@code false}.

**Returns:**
booleskt värde

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Ibland innehåller PDF-filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade nära varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS-format) ibland generera synliga gränser mellan delar av bakgrundsbilderna, eftersom deras teknik för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som om det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt.

**Returns:**
booleskt värde

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> Detta attribut aktiverar funktionalitet för att extrahera bild eller text från PDF-dokument med OCR-underlag. </p>Värde: {@code true} text kommer att extraheras i resultatsdokumentet; annars {@code false}. <hr> Standardvärde == false

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
Representerar en intern processor för förloppshändelser som arbetar under konvertering och översätter konverteringshändelser från interna konverteringssteg till externa totala förloppshändelser. Klassen sänder också händelser som möjliggör att frigöra resurser som inte längre behövs. Denna interna klass hanterar händelser för PDF till APS och APS till [Other format] för att beräkna totalt förlopp och informera kundens kod om dessa totala förloppshändelser. Klassen använder två typer av händelser: ApsToExternal-modellkonvertering och händelser för konvertering Pdf till APS för att generera totala förloppshändelser. Export har tre steg: 1) Pdf till Aps 2) Aps-igenkänning 3) Aps-export till målformat. Konstruktorn tillåter att justera hur många sidor som konverteras och vilken ungefärlig del av detta eller det steget som utgör den totala förloppet.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Ibland innehåller PDF-filer bakgrundsbilder (för sidor eller tabellceller) som är konstruerade av flera identiska mosaikbakgrundsbilder placerade nära varandra. I sådana fall kan renderare för målformat (t.ex. MsWord för DOCS-format) ibland generera synliga gränser mellan delar av bakgrundsbilderna, eftersom deras teknik för bildkantutjämning (anti-aliasing) skiljer sig från Acrobat Reader. Om det ser ut som om det exporterade dokumentet innehåller sådana synliga gränser mellan delar av samma bakgrundsbilder, försök använda den här inställningen för att bli av med den oönskade effekten. OBS! Denna kvalitetsoptimering saktar vanligtvis ner konverteringen avsevärt, så använd detta alternativ endast när det verkligen är nödvändigt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | booleskt värde |
