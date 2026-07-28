---
title: "ExtractImageMode"
linktitle: "ExtractImageMode"
second_title: "Aspose.PDF för Java API-referens"
description: "Definierar olika lägen som kan användas vid extrahering av bilder från dokument."
type: docs
weight: 1360
url: /sv/java/com.aspose.pdf/extractimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ExtractImageMode > com.aspose.pdf.ExtractImageMode, java.lang.Enum < ExtractImageMode >, com.aspose.pdf.ExtractImageMode

**All Implemented Interfaces:**
Serializable, Comparable < ExtractImageMode >

```
public enum ExtractImageMode extends Enum < ExtractImageMode >
```

Definierar olika lägen som kan användas vid extrahering av bilder från dokument.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [ActuallyUsed](#ActuallyUsed) | Definierar bildextraktionsläge där endast de bilder som faktiskt visas på en sida extraheras. |
| [DefinedInResources](#DefinedInResources) | Definierar bildextraktionsläge där alla bilder som definierats i resurser för en viss sida extraheras. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### ActuallyUsed {#ActuallyUsed}
```
public static final ExtractImageMode ActuallyUsed
```

Definierar bildextraktionsläge där endast de bilder som faktiskt visas på en sida extraheras.

### DefinedInResources {#DefinedInResources}
```
public static final ExtractImageMode DefinedInResources
```

Definierar bildextraktionsläge där alla bilder som definierats i resurser för en viss sida extraheras.

### getByValue {#getByValue-int-}
```
public static ExtractImageMode getByValue(int value)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static ExtractImageMode [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
