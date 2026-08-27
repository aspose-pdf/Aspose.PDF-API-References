---
title: "UnifiedSaveOptions.ProgressEventHandlerInfo"
linktitle: "UnifiedSaveOptions.ProgressEventHandlerInfo"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse stellt Informationen über den Konvertierungsfortschritt dar, die in einer externen Anwendung verwendet werden können, um den Fortschritt dem Endbenutzer anzuzeigen."
type: docs
weight: 5440
url: /de/java/com.aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.UnifiedSaveOptions.ProgressEventHandlerInfo

```
public static class UnifiedSaveOptions.ProgressEventHandlerInfo extends Object
```

Diese Klasse stellt Informationen über den Konvertierungsfortschritt dar, die in einer externen Anwendung verwendet werden können, um den Fortschritt dem Endbenutzer anzuzeigen.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDocumentId](#getDocumentId--) | Die eindeutige Dokument-ID. |
| [getEventType](#getEventType--) | Typ des aufgetretenen Fortschrittsereignisses |
| [getMaxValue](#getMaxValue--) | maximal möglicher Wert des Fortschrittswertes |
| [getValue](#getValue--) | aktueller Wert des Fortschrittswertes |
| [setDocumentId](#setDocumentId-com.aspose.ms.System.Guid-) | Die eindeutige Dokument-ID. |
| [setEventType](#setEventType-int-) | Typ des aufgetretenen Fortschrittsereignisses |
| [setMaxValue](#setMaxValue-int-) | maximal möglicher Wert des Fortschrittswertes |
| [setValue](#setValue-int-) | aktueller Wert des Fortschrittswertes |

### getDocumentId {#getDocumentId--}
```
public com.aspose.ms.System.Guid getDocumentId()
```

Die eindeutige Dokument-ID.

**Returns:**
Guid-Instanz

### getEventType {#getEventType--}
```
public int getEventType()
```

Typ des aufgetretenen Fortschrittsereignisses

**Returns:**
ProgressEventType-Element @see ProgressEventType

### getMaxValue {#getMaxValue--}
```
public int getMaxValue()
```

maximal möglicher Wert des Fortschrittswertes

**Returns:**
int-Wert

### getValue {#getValue--}
```
public int getValue()
```

aktueller Wert des Fortschrittswertes

**Returns:**
int-Wert

### setDocumentId {#setDocumentId-com.aspose.ms.System.Guid-}
Die eindeutige Dokument-ID.

### setEventType {#setEventType-int-}
```
public void setEventType(int eventType)
```

Typ des aufgetretenen Fortschrittsereignisses

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType |  | ProgressEventType-Element @see ProgressEventType |

### setMaxValue {#setMaxValue-int-}
```
public void setMaxValue(int maxValue)
```

maximal möglicher Wert des Fortschrittswertes

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxValue |  | int-Wert |

### setValue {#setValue-int-}
```
public void setValue(int value)
```

aktueller Wert des Fortschrittswertes

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
