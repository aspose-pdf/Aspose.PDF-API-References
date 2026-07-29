---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Descrive il tipo di coordinate della pagina. MediaBox = 0 CropBox = 1"
type: docs
weight: 3350
url: /it/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

Descrive il tipo di coordinate della pagina. MediaBox = 0 CropBox = 1

## Campi

| Campo | Descrizione |
| --- | --- |
| [CropBox](#CropBox) | Il CropBox definisce l'area a cui devono essere ritagliati i contenuti della pagina. |
| [MediaBox](#MediaBox) | Il MediaBox è usato per specificare la larghezza e l'altezza della pagina. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Restituisce la costante enum di questo tipo con il nome specificato. |
| [values](#values--) | Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate. |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

Il CropBox definisce l'area a cui devono essere ritagliati i contenuti della pagina.

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

Il MediaBox è usato per specificare la larghezza e l'altezza della pagina.

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
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
public static PageCoordinateType [] values()
```

Restituisce un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate.

**Returns:**
un array contenente le costanti di questo tipo enum, nell'ordine in cui sono dichiarate
