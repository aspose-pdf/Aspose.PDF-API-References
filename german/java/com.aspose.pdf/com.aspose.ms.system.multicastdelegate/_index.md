---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die Ereignisse darstellt."
type: docs
weight: 740
url: /de/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Klasse, die Ereignisse darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-T-) | Füge einen weiteren Delegaten hinzu. |
| [assign](#assign-T-) | Füge nur den aktuellen Delegaten hinzu und lösche die anderen. |
| [clear](#clear--) | Delegatenliste leeren |
| [isEmpty](#isEmpty--) | Gibt true zurück, wenn die Liste der Handler leer ist |
| [remove](#remove-T-) | Delegaten aus der Liste löschen |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Füge einen weiteren Delegaten hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Delegat |  | Handler-Objekt |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Füge nur den aktuellen Delegaten hinzu und lösche die anderen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Delegat |  | Handler-Objekt |

### clear {#clear--}
```
public final void clear()
```

Delegatenliste leeren

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Gibt true zurück, wenn die Liste der Handler leer ist

**Returns:**
boolescher Wert

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Delegaten aus der Liste löschen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Delegat |  | Handler-Objekt |
