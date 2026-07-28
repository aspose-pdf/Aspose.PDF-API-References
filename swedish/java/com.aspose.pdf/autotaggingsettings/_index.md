---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Aspose.PDF för Java API-referens"
description: "Tillhandahåller inställningar för den automatiska taggningsfunktionen i PDF-dokument. Klassen {@link AutoTaggingSettings} möjliggör konfiguration av alternativ för automatisk taggning av PDF-innehåll. Den."
type: docs
weight: 230
url: /sv/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Tillhandahåller inställningar för automatisk taggning i PDF‑dokument. Klassen {@link AutoTaggingSettings} möjliggör konfiguration av alternativ för automatisk taggning av PDF‑innehåll. Den inkluderar egenskaper för att aktivera eller inaktivera automatisk taggning, specificera en strategi för rubrikigenkänning och definiera rubriknivåer baserat på teckenstorlekar.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDefault](#getDefault--) | Hämtar standardinställningarna för den automatiska taggningsfunktionen i PDF-dokument. Standardinställningarna aktiverar automatisk taggning och använder den automatiska strategin för rubrikigenkänning. Dessa inställningar kan användas som en grundkonfiguration för PDF-formatkonvertering eller andra operationer som kräver automatisk taggning av PDF-innehåll. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Hämtar eller anger ett värde som indikerar om den automatiska taggningsfunktionen är aktiverad. När den är aktiverad genererar den automatiska taggningen automatiskt taggat innehåll för PDF-dokumentet, vilket kan förbättra tillgänglighet och struktur. |
| [getHeadingLevels](#getHeadingLevels--) | Hämtar eller anger rubriknivåerna som används för att bestämma strukturen av rubriker i ett PDF-dokument. Egendomen {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) möjliggör konfiguration av mappningen mellan teckenstorlekar och rubriknivåer. Detta används under den automatiska taggningsprocessen för att identifiera och tilldela lämpliga rubriknivåer baserat på teckenstorleken för textelement i dokumentet. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Hämtar eller anger strategin som används för att känna igen rubriker i dokumentet under automatisk taggning. Egendomen {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) bestämmer hur rubriker identifieras i dokumentet. Tillgängliga strategier inkluderar att känna igen rubriker baserat på dispositioner, heuristisk analys eller automatisk detektering. Att sätta denna egendom till {@link HeadingRecognitionStrategy#None} inaktiverar rubrikigenkänning. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Hämtar eller anger ett värde som indikerar om den automatiska taggningsfunktionen är aktiverad. När den är aktiverad genererar den automatiska taggningen automatiskt taggat innehåll för PDF-dokumentet, vilket kan förbättra tillgänglighet och struktur. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Hämtar eller anger rubriknivåerna som används för att bestämma strukturen av rubriker i ett PDF-dokument. Egendomen {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) möjliggör konfiguration av mappningen mellan teckenstorlekar och rubriknivåer. Detta används under den automatiska taggningsprocessen för att identifiera och tilldela lämpliga rubriknivåer baserat på teckenstorleken för textelement i dokumentet. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Hämtar eller anger strategin som används för att känna igen rubriker i dokumentet under automatisk taggning. Egendomen {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) bestämmer hur rubriker identifieras i dokumentet. Tillgängliga strategier inkluderar att känna igen rubriker baserat på dispositioner, heuristisk analys eller automatisk detektering. Att sätta denna egendom till {@link HeadingRecognitionStrategy#None} inaktiverar rubrikigenkänning. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Hämtar standardinställningarna för den automatiska taggningsfunktionen i PDF-dokument. Standardinställningarna aktiverar automatisk taggning och använder den automatiska strategin för rubrikigenkänning. Dessa inställningar kan användas som en grundkonfiguration för PDF-formatkonvertering eller andra operationer som kräver automatisk taggning av PDF-innehåll.

**Returns:**
AutoTaggingSettings-instans

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Hämtar eller anger ett värde som indikerar om den automatiska taggningsfunktionen är aktiverad. När den är aktiverad genererar den automatiska taggningen automatiskt taggat innehåll för PDF-dokumentet, vilket kan förbättra tillgänglighet och struktur.

**Returns:**
booleskt värde

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Hämtar eller anger rubriknivåerna som används för att bestämma strukturen av rubriker i ett PDF-dokument. Egendomen {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) möjliggör konfiguration av mappningen mellan teckenstorlekar och rubriknivåer. Detta används under den automatiska taggningsprocessen för att identifiera och tilldela lämpliga rubriknivåer baserat på teckenstorleken för textelement i dokumentet.

**Returns:**
HeadingLevels‑instans

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Hämtar eller anger strategin som används för att känna igen rubriker i dokumentet under automatisk taggning. Egendomen {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) bestämmer hur rubriker identifieras i dokumentet. Tillgängliga strategier inkluderar att känna igen rubriker baserat på dispositioner, heuristisk analys eller automatisk detektering. Att sätta denna egendom till {@link HeadingRecognitionStrategy#None} inaktiverar rubrikigenkänning.

**Returns:**
HeadingRecognitionStrategy‑element

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Hämtar eller anger ett värde som indikerar om den automatiska taggningsfunktionen är aktiverad. När den är aktiverad genererar den automatiska taggningen automatiskt taggat innehåll för PDF-dokumentet, vilket kan förbättra tillgänglighet och struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Hämtar eller anger rubriknivåerna som används för att bestämma strukturen av rubriker i ett PDF-dokument. Egendomen {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) möjliggör konfiguration av mappningen mellan teckenstorlekar och rubriknivåer. Detta används under den automatiska taggningsprocessen för att identifiera och tilldela lämpliga rubriknivåer baserat på teckenstorleken för textelement i dokumentet.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Hämtar eller anger strategin som används för att känna igen rubriker i dokumentet under automatisk taggning. Egendomen {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) bestämmer hur rubriker identifieras i dokumentet. Tillgängliga strategier inkluderar att känna igen rubriker baserat på dispositioner, heuristisk analys eller automatisk detektering. Att sätta denna egendom till {@link HeadingRecognitionStrategy#None} inaktiverar rubrikigenkänning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | HeadingRecognitionStrategy‑element |
