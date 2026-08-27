---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Der Typ SaveOptions hält das Abstraktionsniveau für einzelne Speicheroptionen."
type: docs
weight: 4370
url: /de/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

Der Typ SaveOptions hält das Abstraktionsniveau für einzelne Speicheroptionen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Format der Datenspeicherung. |
| [getWarningHandler](#getWarningHandler--) | Rückruf, um erzeugte Warnungen zu behandeln. Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speichervorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, worin der Speichervorgang beendet werden soll. |
| [isCacheGlyphs](#isCacheGlyphs--) | Liest oder setzt den booleschen Wert, der angibt, ob Schriftglyphen beim Vorbereiten von APS‑Seiten zwischengespeichert werden. Verbessert die Leistung der PDF‑Konvertierung in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [isCloseResponse](#isCloseResponse--) | Liest den booleschen Wert, der angibt, ob das Response‑Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Liest oder setzt den booleschen Wert, der angibt, ob Schriftglyphen beim Vorbereiten von APS‑Seiten zwischengespeichert werden. Verbessert die Leistung der PDF‑Konvertierung in andere Formate, erhöht jedoch den Speicherverbrauch. |
| [setCloseResponse](#setCloseResponse-boolean-) | Setzt den booleschen Wert, der angibt, ob das Response‑Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Rückruf, um erzeugte Warnungen zu behandeln. Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speichervorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, worin der Speichervorgang beendet werden soll. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Format der Datenspeicherung.

**Returns:**
SaveFormat-Wert @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Rückruf, um erzeugte Warnungen zu behandeln. Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speichervorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, worin der Speichervorgang beendet werden soll.

**Returns:**
IWarningCallback-Wert

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Liest oder setzt den booleschen Wert, der angibt, ob Schriftglyphen beim Vorbereiten von APS‑Seiten zwischengespeichert werden. Verbessert die Leistung der PDF‑Konvertierung in andere Formate, erhöht jedoch den Speicherverbrauch.

**Returns:**
boolescher Wert

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Liest den booleschen Wert, der angibt, ob das Response‑Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird.

**Returns:**
boolescher Wert

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Liest oder setzt den booleschen Wert, der angibt, ob Schriftglyphen beim Vorbereiten von APS‑Seiten zwischengespeichert werden. Verbessert die Leistung der PDF‑Konvertierung in andere Formate, erhöht jedoch den Speicherverbrauch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Setzt den booleschen Wert, der angibt, ob das Response‑Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Rückruf, um erzeugte Warnungen zu behandeln. Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speichervorgang wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, worin der Speichervorgang beendet werden soll.
