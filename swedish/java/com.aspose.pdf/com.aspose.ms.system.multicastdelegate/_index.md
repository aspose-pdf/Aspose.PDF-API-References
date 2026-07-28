---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar händelser."
type: docs
weight: 740
url: /sv/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Klass som representerar händelser.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-T-) | Lägg till en delegat till. |
| [assign](#assign-T-) | Lägg bara till den aktuella delegaten och rensa övriga. |
| [clear](#clear--) | Rensa delegatlistan |
| [isEmpty](#isEmpty--) | Returnerar true om listan med hanterare är tom |
| [remove](#remove-T-) | Ta bort delegat från listan |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Lägg till en delegat till.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| delegat |  | Hanterarobjekt |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Lägg bara till den aktuella delegaten och rensa övriga.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| delegat |  | Hanterarobjekt |

### clear {#clear--}
```
public final void clear()
```

Rensa delegatlistan

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Returnerar true om listan med hanterare är tom

**Returns:**
booleskt värde

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Ta bort delegat från listan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| delegat |  | Hanterarobjekt |
