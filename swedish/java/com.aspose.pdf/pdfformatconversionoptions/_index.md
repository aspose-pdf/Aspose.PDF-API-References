---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "representerar en uppsättning alternativ för att konvertera PDF-dokument."
type: docs
weight: 3730
url: /sv/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

representerar en uppsättning alternativ för att konvertera PDF-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktör |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Konstruktör |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktör |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Konstruktör |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktör |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Strategi för att justera text. Denna parameter har mening endast när flaggan {@code AlignText} är satt till true. |
| [getAlignText](#getAlignText--) | Denna flagga styr textjustering i det konverterade dokumentet. Som standard påverkar dokumentkonverteringen inte textjusteringen och lämnar texten oförändrad. Men i vissa fall kan teckensnittssubstitution orsaka överlappande text eller extra mellanslag i det konverterade dokumentet. När denna flagga är satt kommer speciella justeringsoperationer att utföras. Denna flagga bör endast sättas för dokument som har problem med överlappande text eller extra mellanslag, eftersom användning av flaggan minskar prestanda och i vissa fall kan förstöra textinnehållet. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | Hämtar eller ställer in inställningarna för automatisk taggning under PDF-formatkonvertering. Inställningarna för automatisk taggning används för att konfigurera beteendet hos auto‑taggningsprocessen, som vanligtvis används för att förbättra tillgängligheten och strukturen i ett PDF‑dokument vid konvertering till ett specifikt PDF‑format. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Åtgärd för bilder med mjuk mask. |
| [getDefault](#getDefault--) | Hämtar PdfFormatConversionOptions‑objektet med standardparametrar |
| [getErrorAction](#getErrorAction--) | Åtgärd för objekt som inte kan konverteras |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentets filstorlek. Denna parameter har mening endast när flaggan {@code OptimizeFileSize} är satt till true. Som standard används kombinationen av strategierna {@code SubsetFonts} och {@code RemoveDuplicatedFonts}. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Alternativ för fall då det inte är möjligt att bädda in vissa teckensnitt i PDF‑dokumentet. |
| [getFormat](#getFormat--) | PDF-format. |
| [getIccProfileFileName](#getIccProfileFileName--) | Hämtar filnamnet för ICC‑profilen. Om värdet är null används standard‑ICC‑profilen. |
| [getLogFileName](#getLogFileName--) | Sökväg till filen där kommentarer kommer att lagras. |
| [getLogStream](#getLogStream--) | Ström där kommentarer kommer att lagras. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Innehåller flaggor för att styra PDF/A‑konverteringsprocessen för fall då källdokumentet inte motsvarar PDF/A‑specifikationen. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | Denna egenskap är en ut‑egenskap. Den innehåller alla teckensnitt (teckensnittsnamn) som inte hittades på datorn vid den senaste PDF/A‑konverteringen. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | Hämtar en flagga som aktiverar/inaktiverar ett speciellt konverteringsläge för att skapa PDF/A‑dokument med reducerad filstorlek. För närvarande påverkar denna flagga optimeringen av teckensnitt som används i PDF‑dokumentet, och möjligen kommer den i framtiden även att användas för att slå på optimering av andra datastrukturer, såsom grafik. Kombinationen av denna flagga och läge kan avsevärt minska filstorleken men samtidigt kan den avsevärt minska konverteringsprestandan. |
| [getOutputIntent](#getOutputIntent--) | Hämtar eller ställer in {@link OutputIntent} för PDF‑formatkonverteringen. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specificerar den avsedda utdataenheten eller -förhållandet som PDF‑dokumentet förbereds för. Den används för att säkerställa att färgerna i dokumentet återges korrekt på mål­enheten. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Strategi för att bearbeta symboler från Unicode Private Use Area (PUA). |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Strategi för att kopiera kodningsdata för symboliska teckensnitt om ett symboliskt TrueType‑teckensnitt har mer än en kodningstabell. |
| [getTransparencyAction](#getTransparencyAction--) | Åtgärd för bildmaskerade objekt |
| [getTransparencyResolution](#getTransparencyResolution--) | Ställer in upplösning vid konvertering av transparenta bilder. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Regler för att lösa problem med unicode‑mappning. Kan vara null. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Hämtar/inställer körning av bildströmmar i asynkron läge. |
| [isLowMemoryMode](#isLowMemoryMode--) | Är lågminneskonverteringsläge aktiverat |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | Är teckensnittsanalysering per sida aktiverat Standardvärde = false |
| [isTransferInfo](#isTransferInfo--) | Hämtar eller ställer in om data från Info ska överföras till Metadata vid konvertering till PDF 2.0. True som standard. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Standardvärde FALSE och transparensfärg kommer att behandlas för att behålla dokumentets utseende. Med värdet TRUE konverteras transparensfärgen till icke‑transparent, vissa objekt kan bli täckta. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Strategi för att justera text. Denna parameter har mening endast när flaggan {@code AlignText} är satt till true. |
| [setAlignText](#setAlignText-boolean-) | Denna flagga styr textjustering i det konverterade dokumentet. Som standard påverkar dokumentkonverteringen inte textjusteringen och lämnar texten oförändrad. Men i vissa fall kan teckensnittssubstitution orsaka överlappande text eller extra mellanslag i det konverterade dokumentet. När denna flagga är satt kommer speciella justeringsoperationer att utföras. Denna flagga bör endast sättas för dokument som har problem med överlappande text eller extra mellanslag, eftersom användning av flaggan minskar prestanda och i vissa fall kan förstöra textinnehållet. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Hämtar/inställer körning av bildströmmar i asynkron läge. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | Hämtar eller ställer in inställningarna för automatisk taggning under PDF-formatkonvertering. Inställningarna för automatisk taggning används för att konfigurera beteendet hos auto‑taggningsprocessen, som vanligtvis används för att förbättra tillgängligheten och strukturen i ett PDF‑dokument vid konvertering till ett specifikt PDF‑format. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Åtgärd för bilder med mjuk mask. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Åtgärd för objekt som inte kan konverteras |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentets filstorlek. Denna parameter har mening endast när flaggan {@code OptimizeFileSize} är satt till true. Som standard används kombinationen av strategierna {@code SubsetFonts} och {@code RemoveDuplicatedFonts}. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | PDF-format. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | Ställer in filnamnet för ICC‑profilen. Om null används standard‑ICC‑profilen. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Sökväg till filen där kommentarer kommer att lagras. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Ström där kommentarer kommer att lagras. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | Är lågminneskonverteringsläge aktiverat |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | Ställer in en flagga som aktiverar/inaktiverar speciellt konverteringsläge för att få PDF/A‑dokument med minskad filstorlek. Nu påverkar denna flagga optimeringen av teckensnitt som används i PDF‑dokumentet, möjligen kommer flaggan i framtiden även att användas för att slå på optimering av andra datastrukturer, såsom grafik. Kombinationen av denna flagga och läge kan avsevärt minska filstorleken men samtidigt avsevärt minska konverteringsprestandan. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | Hämtar eller ställer in {@link OutputIntent} för PDF‑formatkonverteringen. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specificerar den avsedda utdataenheten eller -förhållandet som PDF‑dokumentet förbereds för. Den används för att säkerställa att färgerna i dokumentet återges korrekt på mål­enheten. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Ställ in teckensnittsanalysering per sida aktiverat Standardvärde = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Strategi för att bearbeta symboler från Unicode Private Use Area (PUA). |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Strategi för att kopiera kodningsdata för symboliska teckensnitt om ett symboliskt TrueType‑teckensnitt har mer än en kodningstabell. |
| [setTransferInfo](#setTransferInfo-boolean-) | Hämtar eller ställer in om data från Info ska överföras till Metadata vid konvertering till PDF 2.0. True som standard. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Åtgärd för bildmaskerade objekt |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Standardvärde FALSE och transparensfärg kommer att behandlas för att behålla dokumentets utseende. Med värdet TRUE konverteras transparensfärgen till icke‑transparent, vissa objekt kan bli täckta. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Ställer in upplösning vid konvertering av transparenta bilder. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Regler för att lösa problem med unicode‑mappning. Kan vara null. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktör

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Konstruktör

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktör

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Konstruktör

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktör

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konstruktör

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Strategi för att justera text. Denna parameter har mening endast när flaggan {@code AlignText} är satt till true.

**Returns:**
SegmentAlignStrategy element @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

Denna flagga styr textjustering i det konverterade dokumentet. Som standard påverkar dokumentkonverteringen inte textjusteringen och lämnar texten oförändrad. Men i vissa fall kan teckensnittssubstitution orsaka överlappande text eller extra mellanslag i det konverterade dokumentet. När denna flagga är satt kommer speciella justeringsoperationer att utföras. Denna flagga bör endast sättas för dokument som har problem med överlappande text eller extra mellanslag, eftersom användning av flaggan minskar prestanda och i vissa fall kan förstöra textinnehållet.

**Returns:**
booleskt värde

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

Hämtar eller ställer in inställningarna för automatisk taggning under PDF-formatkonvertering. Inställningarna för automatisk taggning används för att konfigurera beteendet hos auto‑taggningsprocessen, som vanligtvis används för att förbättra tillgängligheten och strukturen i ett PDF‑dokument vid konvertering till ett specifikt PDF‑format.

**Returns:**
AutoTaggingSettings-instans

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Åtgärd för bilder med mjuk mask.

**Returns:**
int‑värde

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Hämtar PdfFormatConversionOptions‑objektet med standardparametrar

**Returns:**
PdfFormatConversionOptions objekt

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Åtgärd för objekt som inte kan konverteras

**Returns:**
ConvertErrorAction element @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentets filstorlek. Denna parameter har mening endast när flaggan {@code OptimizeFileSize} är satt till true. Som standard används kombinationen av strategierna {@code SubsetFonts} och {@code RemoveDuplicatedFonts}.

**Returns:**
byte värde @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Alternativ för fall då det inte är möjligt att bädda in vissa teckensnitt i PDF‑dokumentet.

**Returns:**
FontEmbeddingOptions objekt

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

PDF-format.

**Returns:**
PdfFormat element @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

Hämtar filnamnet för ICC‑profilen. Om värdet är null används standard‑ICC‑profilen.

**Returns:**
String-objekt

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Sökväg till filen där kommentarer kommer att lagras.

**Returns:**
String-objekt

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Ström där kommentarer kommer att lagras.

**Returns:**
OutputStream objekt

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Innehåller flaggor för att styra PDF/A‑konverteringsprocessen för fall då källdokumentet inte motsvarar PDF/A‑specifikationen.

**Returns:**
PdfANonSpecificationFlags objekt

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

Denna egenskap är en ut‑egenskap. Den innehåller alla teckensnitt (teckensnittsnamn) som inte hittades på datorn vid den senaste PDF/A‑konverteringen.

**Returns:**
Array av Strängar

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

Hämtar en flagga som aktiverar/inaktiverar ett speciellt konverteringsläge för att skapa PDF/A‑dokument med reducerad filstorlek. För närvarande påverkar denna flagga optimeringen av teckensnitt som används i PDF‑dokumentet, och möjligen kommer den i framtiden även att användas för att slå på optimering av andra datastrukturer, såsom grafik. Kombinationen av denna flagga och läge kan avsevärt minska filstorleken men samtidigt kan den avsevärt minska konverteringsprestandan.

**Returns:**
booleskt värde

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

Hämtar eller ställer in {@link OutputIntent} för PDF‑formatkonverteringen. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specificerar den avsedda utdataenheten eller -förhållandet som PDF‑dokumentet förbereds för. Den används för att säkerställa att färgerna i dokumentet återges korrekt på mål­enheten.

**Returns:**
OutputIntent instans

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Strategi för att bearbeta symboler från Unicode Private Use Area (PUA).

**Returns:**
PuaProcessingStrategy element @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Strategi för att kopiera kodningsdata för symboliska teckensnitt om ett symboliskt TrueType‑teckensnitt har mer än en kodningstabell.

**Returns:**
PdfASymbolicFontEncodingStrategy objekt

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Åtgärd för bildmaskerade objekt

**Returns:**
ConvertTransparencyAction element @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Ställer in upplösning vid konvertering av transparenta bilder. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 300.

**Returns:**
Upplösningsvärde

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Regler för att lösa problem med unicode‑mappning. Kan vara null.

**Returns:**
ToUnicodeProcessingRules-objekt

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Hämtar/inställer körning av bildströmmar i asynkron läge.

**Returns:**
booleskt värde

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

Är lågminneskonverteringsläge aktiverat

**Returns:**
booleskt värde

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

Är teckensnittsanalysering per sida aktiverat Standardvärde = false

**Returns:**
booleskt värde

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

Hämtar eller ställer in om data från Info ska överföras till Metadata vid konvertering till PDF 2.0. True som standard.

**Returns:**
booleskt värde

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Standardvärde FALSE och transparensfärg kommer att behandlas för att behålla dokumentets utseende. Med värdet TRUE konverteras transparensfärgen till icke‑transparent, vissa objekt kan bli täckta.

**Returns:**
booleskt värde

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Strategi för att justera text. Denna parameter har mening endast när flaggan {@code AlignText} är satt till true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignStrategy |  | SegmentAlignStrategy element @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

Denna flagga styr textjustering i det konverterade dokumentet. Som standard påverkar dokumentkonverteringen inte textjusteringen och lämnar texten oförändrad. Men i vissa fall kan teckensnittssubstitution orsaka överlappande text eller extra mellanslag i det konverterade dokumentet. När denna flagga är satt kommer speciella justeringsoperationer att utföras. Denna flagga bör endast sättas för dokument som har problem med överlappande text eller extra mellanslag, eftersom användning av flaggan minskar prestanda och i vissa fall kan förstöra textinnehållet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Hämtar/inställer körning av bildströmmar i asynkron läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
Hämtar eller ställer in inställningarna för automatisk taggning under PDF-formatkonvertering. Inställningarna för automatisk taggning används för att konfigurera beteendet hos auto‑taggningsprocessen, som vanligtvis används för att förbättra tillgängligheten och strukturen i ett PDF‑dokument vid konvertering till ett specifikt PDF‑format.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Åtgärd för bilder med mjuk mask.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Åtgärd för objekt som inte kan konverteras

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentets filstorlek. Denna parameter har mening endast när flaggan {@code OptimizeFileSize} är satt till true. Som standard används kombinationen av strategierna {@code SubsetFonts} och {@code RemoveDuplicatedFonts}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
PDF-format.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
Ställer in filnamnet för ICC‑profilen. Om null används standard‑ICC‑profilen.

### setLogFileName {#setLogFileName-java.lang.String-}
Sökväg till filen där kommentarer kommer att lagras.

### setLogStream {#setLogStream-java.io.OutputStream-}
Ström där kommentarer kommer att lagras.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

Är lågminneskonverteringsläge aktiverat

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

Ställer in en flagga som aktiverar/inaktiverar speciellt konverteringsläge för att få PDF/A‑dokument med minskad filstorlek. Nu påverkar denna flagga optimeringen av teckensnitt som används i PDF‑dokumentet, möjligen kommer flaggan i framtiden även att användas för att slå på optimering av andra datastrukturer, såsom grafik. Kombinationen av denna flagga och läge kan avsevärt minska filstorleken men samtidigt avsevärt minska konverteringsprestandan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
Hämtar eller ställer in {@link OutputIntent} för PDF‑formatkonverteringen. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) specificerar den avsedda utdataenheten eller -förhållandet som PDF‑dokumentet förbereds för. Den används för att säkerställa att färgerna i dokumentet återges korrekt på mål­enheten.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Ställ in teckensnittsanalysering per sida aktiverat Standardvärde = false

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| b |  | booleskt värde |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Strategi för att bearbeta symboler från Unicode Private Use Area (PUA).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | PuaProcessingStrategy element @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Strategi för att kopiera kodningsdata för symboliska teckensnitt om ett symboliskt TrueType‑teckensnitt har mer än en kodningstabell.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

Hämtar eller ställer in om data från Info ska överföras till Metadata vid konvertering till PDF 2.0. True som standard.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Åtgärd för bildmaskerade objekt

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Standardvärde FALSE och transparensfärg kommer att behandlas för att behålla dokumentets utseende. Med värdet TRUE konverteras transparensfärgen till icke‑transparent, vissa objekt kan bli täckta.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Ställer in upplösning vid konvertering av transparenta bilder. Ju högre upplösning, desto långsammare konverteringshastighet. Standardvärdet är 300.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpi |  | Upplösningsvärde |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Regler för att lösa problem med unicode‑mappning. Kan vara null.
