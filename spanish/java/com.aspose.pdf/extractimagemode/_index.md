---
title: "ExtractImageMode"
linktitle: "ExtractImageMode"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Define diferentes modos que pueden usarse al extraer imágenes de documentos."
type: docs
weight: 1360
url: /es/java/com.aspose.pdf/extractimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ExtractImageMode > com.aspose.pdf.ExtractImageMode, java.lang.Enum < ExtractImageMode >, com.aspose.pdf.ExtractImageMode

**All Implemented Interfaces:**
Serializable, Comparable < ExtractImageMode >

```
public enum ExtractImageMode extends Enum < ExtractImageMode >
```

Define diferentes modos que pueden usarse al extraer imágenes de documentos.

## Campos

| Campo | Descripción |
| --- | --- |
| [ActuallyUsed](#ActuallyUsed) | Define el modo de extracción de imágenes en el que solo se extraen aquellas imágenes que se muestran realmente en una página. |
| [DefinedInResources](#DefinedInResources) | Define el modo de extracción de imágenes en el que se extraen todas las imágenes definidas en los recursos de una página en particular. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### ActuallyUsed {#ActuallyUsed}
```
public static final ExtractImageMode ActuallyUsed
```

Define el modo de extracción de imágenes en el que solo se extraen aquellas imágenes que se muestran realmente en una página.

### DefinedInResources {#DefinedInResources}
```
public static final ExtractImageMode DefinedInResources
```

Define el modo de extracción de imágenes en el que se extraen todas las imágenes definidas en los recursos de una página en particular.

### getByValue {#getByValue-int-}
```
public static ExtractImageMode getByValue(int value)
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
public static ExtractImageMode [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
