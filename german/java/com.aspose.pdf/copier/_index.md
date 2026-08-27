---
title: "Copier"
linktitle: "Copier"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse für Kopierobjekte."
type: docs
weight: 850
url: /de/java/com.aspose.pdf/copier/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Copier

```
public class Copier extends Object
```

Klasse für Kopierobjekte.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Copier](#Copier-com.aspose.pdf.engine.data.ITrailerable-) | Erstellt eine Instanz der Klasse Copier. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-) | Dupliziert IPdfPrimitive |
| [duplicate](#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-) | Erstellt eine Kopie des Objekts mit allen abhängigen Objekten. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | get Erlaube Wiederverwendung von Seiteninhalt |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | get Ignoriere beschädigte Objekte |
| [getRestrictedKeys](#getRestrictedKeys--) | get Eingeschränkte Schlüssel |
| [getReuseStreams](#getReuseStreams--) | get Wiederverwendung von Streams |
| [getUseStubs](#getUseStubs--) | Gibt an, ob Stubs während des Duplizierungsprozesses verwendet werden sollen. Ist die Option aktiviert, werden die Streams kopiert, andernfalls wird ein Link zum Quell-Stream verwendet. Dies verhindert das Schließen des kopierten Dokuments, spart jedoch beim Kopiervorgang und im Speicher. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | set Erlaube Wiederverwendung von Seiteninhalt |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Setze Ignoriere beschädigte Objekte |
| [setRestrictedKeys](#setRestrictedKeys-java.lang.String:A-) | set Eingeschränkte Schlüssel |
| [setReuseStreams](#setReuseStreams-boolean-) | set Wiederverwendung von Streams |
| [setUseStubs](#setUseStubs-boolean-) | Gibt an, ob Stubs während des Duplizierungsprozesses verwendet werden sollen. Ist die Option aktiviert, werden die Streams kopiert, andernfalls wird ein Link zum Quell-Stream verwendet. Dies verhindert das Schließen des kopierten Dokuments, spart jedoch beim Kopiervorgang und im Speicher. |

### Copier {#Copier-com.aspose.pdf.engine.data.ITrailerable-}
Erstellt eine Instanz der Klasse Copier.

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-}
Dupliziert IPdfPrimitive

### duplicate {#duplicate-com.aspose.pdf.engine.data.IPdfPrimitive-boolean-}
Erstellt eine Kopie des Objekts mit allen abhängigen Objekten.

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

get Erlaube Wiederverwendung von Seiteninhalt

**Returns:**
boolescher Wert

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

get Ignoriere beschädigte Objekte

**Returns:**
boolescher Wert

### getRestrictedKeys {#getRestrictedKeys--}
```
public String [] getRestrictedKeys()
```

get Eingeschränkte Schlüssel

**Returns:**
String[] array

### getReuseStreams {#getReuseStreams--}
```
public boolean getReuseStreams()
```

get Wiederverwendung von Streams

**Returns:**
boolescher Wert

### getUseStubs {#getUseStubs--}
```
public boolean getUseStubs()
```

Gibt an, ob Stubs während des Duplizierungsprozesses verwendet werden sollen. Ist die Option aktiviert, werden die Streams kopiert, andernfalls wird ein Link zum Quell-Stream verwendet. Dies verhindert das Schließen des kopierten Dokuments, spart jedoch beim Kopiervorgang und im Speicher.

**Returns:**
boolescher Wert

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

set Erlaube Wiederverwendung von Seiteninhalt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Setze Ignoriere beschädigte Objekte

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRestrictedKeys {#setRestrictedKeys-java.lang.String:A-}
set Eingeschränkte Schlüssel

### setReuseStreams {#setReuseStreams-boolean-}
```
public void setReuseStreams(boolean value)
```

set Wiederverwendung von Streams

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUseStubs {#setUseStubs-boolean-}
```
public void setUseStubs(boolean value)
```

Gibt an, ob Stubs während des Duplizierungsprozesses verwendet werden sollen. Ist die Option aktiviert, werden die Streams kopiert, andernfalls wird ein Link zum Quell-Stream verwendet. Dies verhindert das Schließen des kopierten Dokuments, spart jedoch beim Kopiervorgang und im Speicher.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
