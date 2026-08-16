---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Describe el tipo de coordenada de página. MediaBox = 0 CropBox = 1"
type: docs
weight: 3350
url: /es/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

Describe el tipo de coordenada de página. MediaBox = 0 CropBox = 1

## Campos

| Campo | Descripción |
| --- | --- |
| [CropBox](#CropBox) | El CropBox define la región a la que se recortará el contenido de la página. |
| [MediaBox](#MediaBox) | El MediaBox se utiliza para especificar el ancho y la altura de la página. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

El CropBox define la región a la que se recortará el contenido de la página.

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

El MediaBox se utiliza para especificar el ancho y la altura de la página.

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static PageCoordinateType [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
