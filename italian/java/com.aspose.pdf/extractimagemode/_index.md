---
title: "ExtractImageMode"
linktitle: "ExtractImageMode"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Definisce diverse modalità che possono essere utilizzate durante l'estrazione di immagini dai documenti."
type: docs
weight: 1360
url: /it/java/com.aspose.pdf/extractimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ExtractImageMode > com.aspose.pdf.ExtractImageMode, java.lang.Enum < ExtractImageMode >, com.aspose.pdf.ExtractImageMode

**All Implemented Interfaces:**
Serializable, Comparable < ExtractImageMode >

```
public enum ExtractImageMode extends Enum < ExtractImageMode >
```

Definisce diverse modalità che possono essere utilizzate durante l'estrazione di immagini dai documenti.

## Campi

| Campo | Descrizione |
| --- | --- |
| [ActuallyUsed](#ActuallyUsed) | Definisce la modalità di estrazione delle immagini in cui vengono estratte solo le immagini effettivamente visualizzate in una pagina. |
| [DefinedInResources](#DefinedInResources) | Definisce la modalità di estrazione delle immagini in cui vengono estratte tutte le immagini definite nelle risorse per una pagina specifica. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### ActuallyUsed {#ActuallyUsed}
```
public static final ExtractImageMode ActuallyUsed
```

Definisce la modalità di estrazione delle immagini in cui vengono estratte solo le immagini effettivamente visualizzate in una pagina.

### DefinedInResources {#DefinedInResources}
```
public static final ExtractImageMode DefinedInResources
```

Definisce la modalità di estrazione delle immagini in cui vengono estratte tutte le immagini definite nelle risorse per una pagina specifica.

### getByValue {#getByValue-int-}
```
public static ExtractImageMode getByValue(int value)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Restituisce la costante enum di questo tipo con il nome specificato.

### values {#values--}
```
public static ExtractImageMode [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
