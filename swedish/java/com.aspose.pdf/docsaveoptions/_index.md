---
title: "DocSaveOptions"
linktitle: "DocSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Spara alternativ för export till Doc-format"
type: docs
weight: 1030
url: /sv/java/com.aspose.pdf/docsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.DocSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.DocSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class DocSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Spara alternativ för export till Doc-format

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [DocSaveOptions](#DocSaveOptions--) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Denna hanterare kan användas för att hantera konverteringsförloppshändelser t.ex. den kan användas för att visa förloppsindikator eller meddelanden om aktuellt antal bearbetade sidor, ett exempel på hanterarens kod som visar förloppet i konsolen är : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre> |
| [getFormat](#getFormat--) | Hämta utdataformat |
| [getImageResolutionX](#getImageResolutionX--) | Konverterade bilder X-upplösning. |
| [getImageResolutionY](#getImageResolutionY--) | Konverterade bilder Y-upplösning. |
| [getMaxDistanceBetweenTextLines](#getMaxDistanceBetweenTextLines--) | Denna parameter används för att gruppera textrader i stycken. Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av procent av textradernas höjd. |
| [getMemorySaveModePath](#getMemorySaveModePath--) | Definierar sökvägen (filnamn eller katalognamn) för att lagra temporära data vid konvertering i minneslagringsläge. |
| [getMode](#getMode--) | Avkänningsläge. |
| [getRelativeHorizontalProximity](#getRelativeHorizontalProximity--) | I PDF kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste man ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord under avkänning av ord i käll‑PDF. (Närvaro av ett tomt utrymme minst lika brett som detta mellan bokstäver betyder att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast när käll‑PDF innehåller specifika sällan använda teckensnitt för vilka ett optimalt värde inte kan beräknas från teckensnittet. Så i de allra flesta fall ändrar denna parameter ingenting i det resulterande dokumentet. |
| [isAddReturnToLineEnd](#isAddReturnToLineEnd--) | Används för stycke- eller radbrytningar. |
| [isConvertType3Fonts](#isConvertType3Fonts--) | Hämtar eller anger konvertering för Type3‑teckensnitt. I Type 3‑teckensnitt ska glyfer definieras av strömmar av grafikoperatorer. Detta innebär att i DOC/DOCX‑utdata ser vi bilder istället för text. Sätt detta flagg till true för att konvertera Type3‑teckensnitt till TTF och få text i den resulterande filen. |
| [isRecognizeBullets](#isRecognizeBullets--) | Aktivera igenkänning av punktlistor. |
| [isReSaveFonts](#isReSaveFonts--) | Hämtar eller anger proceduren för att spara om teckensnitt. Om den sätts till true laddar vi om teckensnitt på varje sida för att undvika påverkan från tidigare teckensnittsegenskaper och laddar det nyss skapade teckensnittet från början. Ställ in detta alternativ till false om du vill förbättra prestanda. Standardvärdet är true; |
| [setAddReturnToLineEnd](#setAddReturnToLineEnd-boolean-) | Använd stycke- eller radbrytningar |
| [setBatchSize](#setBatchSize-int-) | Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet. |
| [setConvertType3Fonts](#setConvertType3Fonts-boolean-) | Hämtar eller anger konvertering för Type3‑teckensnitt. I Type 3‑teckensnitt ska glyfer definieras av strömmar av grafikoperatorer. Detta innebär att i DOC/DOCX‑utdata ser vi bilder istället för text. Sätt detta flagg till true för att konvertera Type3‑teckensnitt till TTF och få text i den resulterande filen. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex. |
| [setFormat](#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-) | Ange utdataformat |
| [setImageResolutionX](#setImageResolutionX-int-) | Konverterade bilder X-upplösning. |
| [setImageResolutionY](#setImageResolutionY-int-) | Konverterade bilder Y-upplösning. |
| [setMaxDistanceBetweenTextLines](#setMaxDistanceBetweenTextLines-float-) | Denna parameter används för att gruppera textrader i stycken. Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av procent av textradernas höjd. |
| [setMemorySaveModePath](#setMemorySaveModePath-java.lang.String-) | Definierar sökvägen (filnamn eller katalognamn) för att lagra temporära data vid konvertering i minneslagringsläge. |
| [setMode](#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-) | Avkänningsläge. |
| [setRecognizeBullets](#setRecognizeBullets-boolean-) | Aktivera igenkänning av punktlistor. |
| [setRelativeHorizontalProximity](#setRelativeHorizontalProximity-float-) | I PDF kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste man ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord under avkänning av ord i käll‑PDF. (Närvaro av ett tomt utrymme minst lika brett som detta mellan bokstäver betyder att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast när käll‑PDF innehåller specifika sällan använda teckensnitt för vilka ett optimalt värde inte kan beräknas från teckensnittet. Så i de allra flesta fall ändrar denna parameter ingenting i det resulterande dokumentet. |
| [setReSaveFonts](#setReSaveFonts-boolean-) | Hämtar eller anger proceduren för att spara om teckensnitt. Om den sätts till true laddar vi om teckensnitt på varje sida för att undvika påverkan från tidigare teckensnittsegenskaper och laddar det nyss skapade teckensnittet från början. Ställ in detta alternativ till false om du vill förbättra prestanda. Standardvärdet är true; |

### DocSaveOptions {#DocSaveOptions--}
```
public DocSaveOptions()
```

Konstruktör

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet.

**Returns:**
int‑värde

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Denna hanterare kan användas för att hantera konverteringsförloppshändelser, t.ex. kan den användas för att visa en förloppsindikator eller meddelanden om det aktuella antalet bearbetade sidor. Exempel på hanterarens kod som visar förloppet i konsolen är : </p> <hr> <pre> public static void convertWithShowingProgress() { (new License()).setLicense("License\\Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.setCustomProgressHandler ( new HtmlSaveOptions.conversionProgressEventHandler(ShowProgressOnConsole)); doc.save("Booklet.doc", saveOptions); System.in.read(); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.getEventType()) { case HtmlSaveOptions.ProgressEventType.TotalProgress: Console.WriteLine("%s - Conversion progress : %s ."format(new Date().getTime(), eventInfo.getValue().toString())); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: Console.WriteLine("%s - Source page %s of %s analyzed.", (new Date().getTime().toString(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: Console.WriteLine("%s - Result page's %s of %s layout created.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: Console.WriteLine("{0} - Result page {1} of {2} exported.", (new Date().getTime(), eventInfo.getValue().toString(), eventInfo.getMaxValue().toString())); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler instans

### getFormat {#getFormat--}
```
public DocSaveOptions.DocFormat getFormat()
```

Hämta utdataformat

**Returns:**
DocFormat-element @see com.aspose.pdf.DocSaveOptions.DocFormat

### getImageResolutionX {#getImageResolutionX--}
```
public int getImageResolutionX()
```

Konverterade bilder X-upplösning.

**Returns:**
int‑värde

### getImageResolutionY {#getImageResolutionY--}
```
public int getImageResolutionY()
```

Konverterade bilder Y-upplösning.

**Returns:**
int‑värde

### getMaxDistanceBetweenTextLines {#getMaxDistanceBetweenTextLines--}
```
public float getMaxDistanceBetweenTextLines()
```

Denna parameter används för att gruppera textrader i stycken. Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av procent av textradernas höjd.

**Returns:**
flyttalsvärde

### getMemorySaveModePath {#getMemorySaveModePath--}
```
public final String getMemorySaveModePath()
```

Definierar sökvägen (filnamn eller katalognamn) för att lagra temporära data vid konvertering i minneslagringsläge.

**Returns:**
String värde

### getMode {#getMode--}
```
public DocSaveOptions.RecognitionMode getMode()
```

Avkänningsläge.

**Returns:**
RecognitionMode-värde @see RecognitionMode

### getRelativeHorizontalProximity {#getRelativeHorizontalProximity--}
```
public float getRelativeHorizontalProximity()
```

I PDF kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste man ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord under avkänning av ord i käll‑PDF. (Närvaro av ett tomt utrymme minst lika brett som detta mellan bokstäver betyder att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast när käll‑PDF innehåller specifika sällan använda teckensnitt för vilka ett optimalt värde inte kan beräknas från teckensnittet. Så i de allra flesta fall ändrar denna parameter ingenting i det resulterande dokumentet.

**Returns:**
Relativ närhet

### isAddReturnToLineEnd {#isAddReturnToLineEnd--}
```
public boolean isAddReturnToLineEnd()
```

Används för stycke- eller radbrytningar.

**Returns:**
booleskt värde.

### isConvertType3Fonts {#isConvertType3Fonts--}
```
public final boolean isConvertType3Fonts()
```

Hämtar eller anger konvertering för Type3‑teckensnitt. I Type 3‑teckensnitt ska glyfer definieras av strömmar av grafikoperatorer. Detta innebär att i DOC/DOCX‑utdata ser vi bilder istället för text. Sätt detta flagg till true för att konvertera Type3‑teckensnitt till TTF och få text i den resulterande filen.

**Returns:**
booleskt värde

### isRecognizeBullets {#isRecognizeBullets--}
```
public boolean isRecognizeBullets()
```

Aktivera igenkänning av punktlistor.

**Returns:**
booleskt värde

### isReSaveFonts {#isReSaveFonts--}
```
public final boolean isReSaveFonts()
```

Hämtar eller anger proceduren för att spara om teckensnitt. Om den sätts till true laddar vi om teckensnitt på varje sida för att undvika påverkan från tidigare teckensnittsegenskaper och laddar det nyss skapade teckensnittet från början. Ställ in detta alternativ till false om du vill förbättra prestanda. Standardvärdet är true;

**Returns:**
booleskt värde

### setAddReturnToLineEnd {#setAddReturnToLineEnd-boolean-}
```
public void setAddReturnToLineEnd(boolean value)
```

Använd stycke- eller radbrytningar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde. |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Definierar batch‑storlek om batchkonvertering är tillämplig för käll‑ och målformatparet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### setConvertType3Fonts {#setConvertType3Fonts-boolean-}
```
public final void setConvertType3Fonts(boolean value)
```

Hämtar eller anger konvertering för Type3‑teckensnitt. I Type 3‑teckensnitt ska glyfer definieras av strömmar av grafikoperatorer. Detta innebär att i DOC/DOCX‑utdata ser vi bilder istället för text. Sätt detta flagg till true för att konvertera Type3‑teckensnitt till TTF och få text i den resulterande filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Denna hanterare kan användas för att hantera konverteringsförlopps‑händelser, t.ex.

### setFormat {#setFormat-com.aspose.pdf.DocSaveOptions.DocFormat-}
Ange utdataformat

### setImageResolutionX {#setImageResolutionX-int-}
```
public void setImageResolutionX(int value)
```

Konverterade bilder X-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setImageResolutionY {#setImageResolutionY-int-}
```
public void setImageResolutionY(int value)
```

Konverterade bilder Y-upplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setMaxDistanceBetweenTextLines {#setMaxDistanceBetweenTextLines-float-}
```
public void setMaxDistanceBetweenTextLines(float value)
```

Denna parameter används för att gruppera textrader i stycken. Bestämmer hur långt ifrån varandra två relativa textrader kan vara. Anges i hundradelar av procent av textradernas höjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setMemorySaveModePath {#setMemorySaveModePath-java.lang.String-}
Definierar sökvägen (filnamn eller katalognamn) för att lagra temporära data vid konvertering i minneslagringsläge.

### setMode {#setMode-com.aspose.pdf.DocSaveOptions.RecognitionMode-}
Avkänningsläge.

### setRecognizeBullets {#setRecognizeBullets-boolean-}
```
public void setRecognizeBullets(boolean value)
```

Aktivera igenkänning av punktlistor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setRelativeHorizontalProximity {#setRelativeHorizontalProximity-float-}
```
public void setRelativeHorizontalProximity(float value)
```

I PDF kan ord internt representeras med operatorer som skriver ut ord genom att skriva ut deras bokstäver eller stavelser var för sig. Så för att upptäcka ord måste man ibland identifiera grupper av oberoende tecken som faktiskt är ord. Denna inställning definierar bredden på avståndet mellan textelement (bokstäver, stavelser) som ska behandlas som avstånd mellan ord under avkänning av ord i käll‑PDF. (Närvaro av ett tomt utrymme minst lika brett som detta mellan bokstäver betyder att textelementen tillhör olika ord). Den är normaliserad till teckenstorlek – 1,0 betyder 100 % av det antagna ordets teckenstorlek. OBS! Den används endast när käll‑PDF innehåller specifika sällan använda teckensnitt för vilka ett optimalt värde inte kan beräknas från teckensnittet. Så i de allra flesta fall ändrar denna parameter ingenting i det resulterande dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Relativ närhet |

### setReSaveFonts {#setReSaveFonts-boolean-}
```
public final void setReSaveFonts(boolean value)
```

Hämtar eller anger proceduren för att spara om teckensnitt. Om den sätts till true laddar vi om teckensnitt på varje sida för att undvika påverkan från tidigare teckensnittsegenskaper och laddar det nyss skapade teckensnittet från början. Ställ in detta alternativ till false om du vill förbättra prestanda. Standardvärdet är true;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
