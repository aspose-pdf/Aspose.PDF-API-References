---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa tipos de estrategias de reconocimiento de encabezados."
type: docs
weight: 30
url: /es/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Representa tipos de estrategias de reconocimiento de encabezados.

## Campos

| Campo | Descripción |
| --- | --- |
| [Auto](#Auto) | Proporciona una selección automática de la estrategia de reconocimiento de encabezados. Esta es la opción predeterminada. Si el documento contiene marcadores, se seleccionará la estrategia {@link HeadingRecognitionStrategy#Outlines}, de lo contrario {@link HeadingRecognitionStrategy#Heuristic}. |
| [Heuristic](#Heuristic) | Representa la estrategia de reconocimiento de encabezados mediante reglas heurísticas y estadísticas de tamaño de fuente. |
| [None](#None) | No reconocer encabezados. Esta opción puede ser útil en documentos con formato complejo. |
| [Outlines](#Outlines) | Representa la estrategia de reconocimiento de encabezados mediante contornos. |

### Auto {#Auto}
```
public static final int Auto
```

Proporciona una selección automática de la estrategia de reconocimiento de encabezados. Esta es la opción predeterminada. Si el documento contiene marcadores, se seleccionará la estrategia {@link HeadingRecognitionStrategy#Outlines}, de lo contrario {@link HeadingRecognitionStrategy#Heuristic}.

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Representa la estrategia de reconocimiento de encabezados mediante reglas heurísticas y estadísticas de tamaño de fuente.

### None {#None}
```
public static final int None
```

No reconocer encabezados. Esta opción puede ser útil en documentos con formato complejo.

### Outlines {#Outlines}
```
public static final int Outlines
```

Representa la estrategia de reconocimiento de encabezados mediante contornos.
