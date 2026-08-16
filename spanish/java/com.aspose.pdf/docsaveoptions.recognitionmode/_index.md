---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto. Use el modo RecognitionMode.Textbox cuando el documento resultante no vaya a ser muy pesado."
type: docs
weight: 1050
url: /es/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Permite controlar cómo se convierte un documento PDF en un documento de procesamiento de texto. Use el modo RecognitionMode.Textbox cuando el documento resultante no va a ser editado intensamente. Los cuadros de texto son fáciles de modificar cuando no hay mucho que hacer. Use el modo RecognitionMode.Flow cuando el documento de salida necesita una edición adicional. Los párrafos y líneas de texto en el modo flujo permiten una fácil modificación del texto, pero los objetos de formato no compatibles se verán peor que en el modo RecognitionMode.Textbox.

## Campos

| Campo | Descripción |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Un modo Flow alternativo que admite el reconocimiento de tablas. |
| [Flow](#Flow) | Modo de reconocimiento completo, el motor realiza agrupación y análisis multinivel para restaurar la intención del autor del documento original y producir un documento lo más editable posible. |
| [Textbox](#Textbox) | Este modo es rápido y bueno para preservar al máximo el aspecto original del archivo PDF, pero la editabilidad del documento resultante podría ser limitada. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Un modo Flow alternativo que admite el reconocimiento de tablas.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Modo de reconocimiento completo, el motor realiza agrupación y análisis multinivel para restaurar la intención del autor del documento original y producir un documento lo más editable posible.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Este modo es rápido y bueno para preservar al máximo el aspecto original del archivo PDF, pero la editabilidad del documento resultante podría ser limitada.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
