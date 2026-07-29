---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt das Ergebnis eines Serialisierungsprozesses für Formularfelder dar."
type: docs
weight: 1390
url: /de/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Stellt das Ergebnis eines Serialisierungsprozesses für Formularfelder dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Initialisiert eine neue Instanz der {@link FieldSerializationResult}-Klasse. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Initialisiert eine neue Instanz der {@link FieldSerializationResult}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Ruft die Fehlermeldungen ab, die mit dem Serialisierungsprozess verbunden sind. Wert: Eine Menge von Fehlermeldungen. |
| [getFieldFullName](#getFieldFullName--) | Ruft den vollständigen Namen des Feldes ab. Wert: Der vollständige Name des Feldes. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Ruft den Status der Formularfeld-Serialisierung ab. Wert: Der Serialisierungsstatus des Formularfeldes. |
| [getWarningMessages](#getWarningMessages--) | Ruft die Warnmeldungen ab, die mit dem Serialisierungsprozess verbunden sind. Wert: Eine Menge von Warnmeldungen. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Aktualisiert den Serialisierungsstatus und fügt eine Meldung zur entsprechenden Menge hinzu. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Initialisiert eine neue Instanz der {@link FieldSerializationResult}-Klasse.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Initialisiert eine neue Instanz der {@link FieldSerializationResult}-Klasse.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Ruft die Fehlermeldungen ab, die mit dem Serialisierungsprozess verbunden sind. Wert: Eine Menge von Fehlermeldungen.

**Returns:**
HashSet von String-Instanz

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Ruft den vollständigen Namen des Feldes ab. Wert: Der vollständige Name des Feldes.

**Returns:**
String Wert

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Ruft den Status der Formularfeld-Serialisierung ab. Wert: Der Serialisierungsstatus des Formularfeldes.

**Returns:**
FieldSerializationStatus-Element

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Ruft die Warnmeldungen ab, die mit dem Serialisierungsprozess verbunden sind. Wert: Eine Menge von Warnmeldungen.

**Returns:**
HashSet von String-Instanz

### updateStatus {#updateStatus-int-java.lang.String-}
Aktualisiert den Serialisierungsstatus und fügt eine Meldung zur entsprechenden Menge hinzu.
