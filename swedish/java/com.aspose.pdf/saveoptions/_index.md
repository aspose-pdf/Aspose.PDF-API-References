---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "SaveOptions-typ håller abstraktionsnivå på enskilda sparaalternativ."
type: docs
weight: 4370
url: /sv/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

SaveOptions-typ håller abstraktionsnivå på enskilda sparaalternativ.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Format för datalagring. |
| [getWarningHandler](#getWarningHandler--) | Återanrop för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, i vilket fall Save‑operationen ska avbrytas. |
| [isCacheGlyphs](#isCacheGlyphs--) | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesförbrukningen. |
| [isCloseResponse](#isCloseResponse--) | Hämtar ett booleskt värde som indikerar om Response‑objektet kommer att stängas efter att dokumentet har sparats i svaret. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesförbrukningen. |
| [setCloseResponse](#setCloseResponse-boolean-) | Anger ett booleskt värde som indikerar om Response‑objektet kommer att stängas efter att dokumentet har sparats i svaret. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Återanrop för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, i vilket fall Save‑operationen ska avbrytas. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Format för datalagring.

**Returns:**
SaveFormat‑värde @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Återanrop för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, i vilket fall Save‑operationen ska avbrytas.

**Returns:**
IWarningCallback‑värde

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesförbrukningen.

**Returns:**
booleskt värde

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Hämtar ett booleskt värde som indikerar om Response‑objektet kommer att stängas efter att dokumentet har sparats i svaret.

**Returns:**
booleskt värde

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Hämtar eller anger ett booleskt värde som indikerar om teckenglyfer ska cachas medan APS‑sidor förbereds. Förbättrar prestanda för konvertering av PDF till andra format men ökar minnesförbrukningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Anger ett booleskt värde som indikerar om Response‑objektet kommer att stängas efter att dokumentet har sparats i svaret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Återanrop för att hantera eventuella genererade varningar. WarningHandler returnerar ReturnAction‑enum‑värdet som specificerar antingen Continue eller Abort. Continue är standardåtgärden och Save‑operationen fortsätter, men användaren kan också returnera Abort, i vilket fall Save‑operationen ska avbrytas.
