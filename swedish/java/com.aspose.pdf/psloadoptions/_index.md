---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för inläsning/import av .mht-fil till pdf-dokument."
type: docs
weight: 4060
url: /sv/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

Representerar alternativ för inläsning/import av .mht-fil till pdf-dokument.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Skapar laddningsalternativ för att konvertera PostScript till PDF-dokument med tom basväg. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Hämtar sökvägar till teckensnittsmappar. Mapparna med ytterligare teckensnitt för konvertering. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | Anger om icke-TrueType-teckensnitt ska sparas som TTF. Det minskar avsevärt volymen på det resulterande dokumentet vid PS till PDF-konvertering och ökar hastigheten för konvertering av PS-filer med en stor mängd text i icke-TrueType-teckensnitt till vilket utdataformat som helst. Däremot finns en liten vertikal förskjutning av texten när en PostSctipt-fil konverteras till bild. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | Anger om icke-TrueType-teckensnitt ska sparas som TTF. Det minskar avsevärt volymen på det resulterande dokumentet vid PS till PDF-konvertering och ökar hastigheten för konvertering av PS-filer med en stor mängd text i icke-TrueType-teckensnitt till vilket utdataformat som helst. Däremot finns en liten vertikal förskjutning av texten när en PostSctipt-fil konverteras till bild. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Ställer in sökvägar till teckensnittsmappar. Mapparna med ytterligare teckensnitt för konvertering. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Skapar laddningsalternativ för att konvertera PostScript till PDF-dokument med tom basväg.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Hämtar sökvägar till teckensnittsmappar. Mapparna med ytterligare teckensnitt för konvertering.

**Returns:**
array av String-värden

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

Anger om icke-TrueType-teckensnitt ska sparas som TTF. Det minskar avsevärt volymen på det resulterande dokumentet vid PS till PDF-konvertering och ökar hastigheten för konvertering av PS-filer med en stor mängd text i icke-TrueType-teckensnitt till vilket utdataformat som helst. Däremot finns en liten vertikal förskjutning av texten när en PostSctipt-fil konverteras till bild.

**Returns:**
booleskt värde

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

Anger om icke-TrueType-teckensnitt ska sparas som TTF. Det minskar avsevärt volymen på det resulterande dokumentet vid PS till PDF-konvertering och ökar hastigheten för konvertering av PS-filer med en stor mängd text i icke-TrueType-teckensnitt till vilket utdataformat som helst. Däremot finns en liten vertikal förskjutning av texten när en PostSctipt-fil konverteras till bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Ställer in sökvägar till teckensnittsmappar. Mapparna med ytterligare teckensnitt för konvertering.
