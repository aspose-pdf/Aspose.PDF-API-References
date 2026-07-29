---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Proporciona configuraciones para la funcionalidad de autoetiquetado en documentos PDF. La clase {@link AutoTaggingSettings} permite configurar opciones para el etiquetado automático del contenido PDF. It."
type: docs
weight: 230
url: /es/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

Proporciona configuraciones para la funcionalidad de autoetiquetado en documentos PDF. La clase {@link AutoTaggingSettings} permite configurar opciones para el etiquetado automático del contenido PDF. Incluye propiedades para habilitar o deshabilitar el autoetiquetado, especificar una estrategia para el reconocimiento de encabezados y definir niveles de encabezado basados en tamaños de fuente.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getDefault](#getDefault--) | Obtiene la configuración predeterminada para la funcionalidad de autoetiquetado en documentos PDF. La configuración predeterminada habilita el autoetiquetado y utiliza la estrategia automática para el reconocimiento de encabezados. Estas configuraciones pueden usarse como una configuración base para la conversión de formato PDF u otras operaciones que requieran el etiquetado automático del contenido PDF. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | Obtiene o establece un valor que indica si la funcionalidad de autoetiquetado está habilitada. Cuando está habilitada, la funcionalidad de autoetiquetado genera automáticamente contenido etiquetado para el documento PDF, lo que puede mejorar la accesibilidad y la estructura. |
| [getHeadingLevels](#getHeadingLevels--) | Obtiene o establece los niveles de encabezado utilizados para determinar la estructura de los encabezados en un documento PDF. La propiedad {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permite configurar el mapeo de tamaños de fuente a niveles de encabezado. Esto se utiliza durante el proceso de autoetiquetado para identificar y asignar los niveles de encabezado apropiados según el tamaño de fuente de los elementos de texto en el documento. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Obtiene o establece la estrategia utilizada para reconocer encabezados en el documento durante el autoetiquetado. La propiedad {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina cómo se identifican los encabezados en el documento. Las estrategias disponibles incluyen reconocer encabezados basados en esquemas, análisis heurístico o detección automática. Establecer esta propiedad a {@link HeadingRecognitionStrategy#None} desactiva el reconocimiento de encabezados. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | Obtiene o establece un valor que indica si la funcionalidad de autoetiquetado está habilitada. Cuando está habilitada, la funcionalidad de autoetiquetado genera automáticamente contenido etiquetado para el documento PDF, lo que puede mejorar la accesibilidad y la estructura. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | Obtiene o establece los niveles de encabezado utilizados para determinar la estructura de los encabezados en un documento PDF. La propiedad {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permite configurar el mapeo de tamaños de fuente a niveles de encabezado. Esto se utiliza durante el proceso de autoetiquetado para identificar y asignar los niveles de encabezado apropiados según el tamaño de fuente de los elementos de texto en el documento. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Obtiene o establece la estrategia utilizada para reconocer encabezados en el documento durante el autoetiquetado. La propiedad {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina cómo se identifican los encabezados en el documento. Las estrategias disponibles incluyen reconocer encabezados basados en esquemas, análisis heurístico o detección automática. Establecer esta propiedad a {@link HeadingRecognitionStrategy#None} desactiva el reconocimiento de encabezados. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

Obtiene la configuración predeterminada para la funcionalidad de autoetiquetado en documentos PDF. La configuración predeterminada habilita el autoetiquetado y utiliza la estrategia automática para el reconocimiento de encabezados. Estas configuraciones pueden usarse como una configuración base para la conversión de formato PDF u otras operaciones que requieran el etiquetado automático del contenido PDF.

**Returns:**
Instancia de AutoTaggingSettings

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

Obtiene o establece un valor que indica si la funcionalidad de autoetiquetado está habilitada. Cuando está habilitada, la funcionalidad de autoetiquetado genera automáticamente contenido etiquetado para el documento PDF, lo que puede mejorar la accesibilidad y la estructura.

**Returns:**
valor booleano

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

Obtiene o establece los niveles de encabezado utilizados para determinar la estructura de los encabezados en un documento PDF. La propiedad {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permite configurar el mapeo de tamaños de fuente a niveles de encabezado. Esto se utiliza durante el proceso de autoetiquetado para identificar y asignar los niveles de encabezado apropiados según el tamaño de fuente de los elementos de texto en el documento.

**Returns:**
Instancia de HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Obtiene o establece la estrategia utilizada para reconocer encabezados en el documento durante el autoetiquetado. La propiedad {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina cómo se identifican los encabezados en el documento. Las estrategias disponibles incluyen reconocer encabezados basados en esquemas, análisis heurístico o detección automática. Establecer esta propiedad a {@link HeadingRecognitionStrategy#None} desactiva el reconocimiento de encabezados.

**Returns:**
Elemento HeadingRecognitionStrategy

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

Obtiene o establece un valor que indica si la funcionalidad de autoetiquetado está habilitada. Cuando está habilitada, la funcionalidad de autoetiquetado genera automáticamente contenido etiquetado para el documento PDF, lo que puede mejorar la accesibilidad y la estructura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
Obtiene o establece los niveles de encabezado utilizados para determinar la estructura de los encabezados en un documento PDF. La propiedad {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) permite configurar el mapeo de tamaños de fuente a niveles de encabezado. Esto se utiliza durante el proceso de autoetiquetado para identificar y asignar los niveles de encabezado apropiados según el tamaño de fuente de los elementos de texto en el documento.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Obtiene o establece la estrategia utilizada para reconocer encabezados en el documento durante el autoetiquetado. La propiedad {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) determina cómo se identifican los encabezados en el documento. Las estrategias disponibles incluyen reconocer encabezados basados en esquemas, análisis heurístico o detección automática. Establecer esta propiedad a {@link HeadingRecognitionStrategy#None} desactiva el reconocimiento de encabezados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento HeadingRecognitionStrategy |
