---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar resultatet av en serialiseringsprocess för ett formulärfält."
type: docs
weight: 1390
url: /sv/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Representerar resultatet av en serialiseringsprocess för ett formulärfält.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Initierar en ny instans av klassen {@link FieldSerializationResult}. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Initierar en ny instans av klassen {@link FieldSerializationResult}. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Hämtar felmeddelandena som är associerade med serialiseringsprocessen. Värde: En uppsättning felmeddelanden. |
| [getFieldFullName](#getFieldFullName--) | Hämtar fältets fullständiga namn. Värde: Fältets fullständiga namn. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Hämtar status för formulärfältets serialisering. Värde: Serialiseringsstatus för formulärfältet. |
| [getWarningMessages](#getWarningMessages--) | Hämtar varningsmeddelandena som är associerade med serialiseringsprocessen. Värde: En uppsättning varningsmeddelanden. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Uppdaterar serialiseringsstatusen och lägger till ett meddelande i lämplig uppsättning. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Initierar en ny instans av klassen {@link FieldSerializationResult}.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Initierar en ny instans av klassen {@link FieldSerializationResult}.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Hämtar felmeddelandena som är associerade med serialiseringsprocessen. Värde: En uppsättning felmeddelanden.

**Returns:**
HashSet av String-instans

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Hämtar fältets fullständiga namn. Värde: Fältets fullständiga namn.

**Returns:**
String värde

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Hämtar status för formulärfältets serialisering. Värde: Serialiseringsstatus för formulärfältet.

**Returns:**
FieldSerializationStatus-element

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Hämtar varningsmeddelandena som är associerade med serialiseringsprocessen. Värde: En uppsättning varningsmeddelanden.

**Returns:**
HashSet av String-instans

### updateStatus {#updateStatus-int-java.lang.String-}
Uppdaterar serialiseringsstatusen och lägger till ett meddelande i lämplig uppsättning.
