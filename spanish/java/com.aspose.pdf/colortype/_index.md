---
title: "ColorType"
linktitle: "ColorType"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica el tipo de color de los elementos en la página."
type: docs
weight: 710
url: /es/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Especifica el tipo de color de los elementos en la página.

## Campos

| Campo | Descripción |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Tipo de color blanco y negro. |
| [Grayscale](#Grayscale) | Tipo de color escala de grises. |
| [Rgb](#Rgb) | Tipo de color RGB. |
| [Undefined](#Undefined) | Valor de tipo de color indefinido. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Devuelve el nombre de cadena para el valor del enum. </p> <hr> Ejemplo: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Tipo de color blanco y negro.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Tipo de color escala de grises.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

Tipo de color RGB.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Valor de tipo de color indefinido.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Devuelve el nombre de cadena para el valor del enum. </p> <hr> Ejemplo: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Valor del enum |

**Returns:**
Nombre del valor

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static ColorType [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
