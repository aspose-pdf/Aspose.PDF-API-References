---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt das Ergebnis eines Validierungsprozesses für ein Zertifikat dar. Die Klasse ValidationResult liefert Informationen über das Ergebnis der Zertifikatsvalidierung, einschließlich seiner."
type: docs
weight: 40
url: /de/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

Stellt das Ergebnis eines Validierungsprozesses für ein Zertifikat dar. Die Klasse ValidationResult liefert Informationen über das Ergebnis der Zertifikatsvalidierung, einschließlich ihres Status und einer Nachricht, die etwaige während der Validierung aufgetretene Probleme beschreibt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ValidationResult](#ValidationResult--) | Erstellt eine Instanz der {@link ValidationResult}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMessage](#getMessage--) | Stellt die mit dem Validierungsergebnis verbundene Nachricht dar. Die Eigenschaft Message liefert zusätzlichen Kontext oder Informationen zum Zustand des Validierungsergebnisses. |
| [getStatus](#getStatus--) | Liest den Status des Validierungsprozesses für ein Zertifikat. Die Eigenschaft Status gibt das Ergebnis der Zertifikatsvalidierung an. Mögliche Werte sind in der {@link ValidationStatus}-Aufzählung definiert, z. B. Valid, Invalid oder Undefined. Sie liefert einen Einblick, ob das Zertifikat die Validierungsprüfungen bestanden hat oder nicht. |
| [setMessage](#setMessage-java.lang.String-) | Stellt die mit dem Validierungsergebnis verbundene Nachricht dar. Die Eigenschaft Message liefert zusätzlichen Kontext oder Informationen zum Zustand des Validierungsergebnisses. |
| [setStatus](#setStatus-int-) | Liest den Status des Validierungsprozesses für ein Zertifikat. Die Eigenschaft Status gibt das Ergebnis der Zertifikatsvalidierung an. Mögliche Werte sind in der {@link ValidationStatus}-Aufzählung definiert, z. B. Valid, Invalid oder Undefined. Sie liefert einen Einblick, ob das Zertifikat die Validierungsprüfungen bestanden hat oder nicht. |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

Erstellt eine Instanz der {@link ValidationResult}-Klasse.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Stellt die mit dem Validierungsergebnis verbundene Nachricht dar. Die Eigenschaft Message liefert zusätzlichen Kontext oder Informationen zum Zustand des Validierungsergebnisses.

**Returns:**
String Wert

### getStatus {#getStatus--}
```
public final int getStatus()
```

Liest den Status des Validierungsprozesses für ein Zertifikat. Die Eigenschaft Status gibt das Ergebnis der Zertifikatsvalidierung an. Mögliche Werte sind in der {@link ValidationStatus}-Aufzählung definiert, z. B. Valid, Invalid oder Undefined. Sie liefert einen Einblick, ob das Zertifikat die Validierungsprüfungen bestanden hat oder nicht.

**Returns:**
ValidationStatus-Element

### setMessage {#setMessage-java.lang.String-}
Stellt die mit dem Validierungsergebnis verbundene Nachricht dar. Die Eigenschaft Message liefert zusätzlichen Kontext oder Informationen zum Zustand des Validierungsergebnisses.

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

Liest den Status des Validierungsprozesses für ein Zertifikat. Die Eigenschaft Status gibt das Ergebnis der Zertifikatsvalidierung an. Mögliche Werte sind in der {@link ValidationStatus}-Aufzählung definiert, z. B. Valid, Invalid oder Undefined. Sie liefert einen Einblick, ob das Zertifikat die Validierungsprüfungen bestanden hat oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ValidationStatus-Element |
