---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Cuando se convierte un archivo PDF (que normalmente tiene un diseño fijo), el motor de conversión intenta realizar agrupación y análisis multinivel para restaurar el documento original."
type: docs
weight: 1250
url: /es/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

Cuando se convierte un archivo PDF (que normalmente tiene un diseño fijo), el motor de conversión intenta realizar agrupación y análisis multinivel para restaurar la intención original del autor del documento y producir un resultado en diseño fluido. Esta propiedad ajusta esa conversión para este u otro método deseable de reconocimiento del contenido.

## Campos

| Campo | Descripción |
| --- | --- |
| [Fixed](#Fixed) | Este modo es rápido y bueno para preservar al máximo el aspecto original de las páginas, pero desafortunadamente muchos lectores EPUB no admiten xhtml con diseño fijo |
| [Flow](#Flow) | Modo de reconocimiento completo, el motor intenta realizar agrupación y análisis multinivel para restaurar la intención del autor del documento original y producir xhtml en diseño fluido. |
| [PdfFlow](#PdfFlow) | La idea principal de esta conversión se basa en guardar el orden \"natural\" de renderizado del contenido que se forma durante el procesamiento de documentos pdf. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Este modo es rápido y bueno para preservar al máximo el aspecto original de las páginas, pero desafortunadamente muchos lectores EPUB no admiten xhtml con diseño fijo

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Modo de reconocimiento completo, el motor intenta realizar agrupación y análisis multinivel para restaurar la intención del autor del documento original y producir xhtml en diseño fluido.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

La idea principal de esta conversión se basa en guardar el orden \"natural\" de renderizado del contenido que se forma durante el procesamiento de documentos pdf.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
