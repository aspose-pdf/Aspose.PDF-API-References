---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "La enumeración de modos de comparación."
type: docs
weight: 10
url: /es/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

La enumeración de modos de comparación.

## Campos

| Campo | Descripción |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | Se ignoran todos los espacios. Los cambios se buscan solo en palabras. |
| [Normal](#Normal) | Modo normal. Solo se tienen en cuenta los espacios dentro de fragmentos de texto (dependiendo de la forma en que se genera el documento). |
| [ParseSpaces](#ParseSpaces) | El modo es similar al normal, pero intenta tener en cuenta el espaciado visual entre fragmentos de texto basado en la distancia. Reconocer la cantidad de espacios entre fragmentos puede no ser preciso porque depende en gran medida de cómo se generan los documentos. Si los documentos se crean con diferentes generadores, pueden existir inexactitudes al comparar los espacios entre fragmentos de texto. Esta opción puede producir resultados que, aunque lógicos, difieren de los resultados de comparación esperados cuando se aplica a documentos con una estructura compleja. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

Se ignoran todos los espacios. Los cambios se buscan solo en palabras.

### Normal {#Normal}
```
public static final int Normal
```

Modo normal. Solo se tienen en cuenta los espacios dentro de fragmentos de texto (dependiendo de la forma en que se genera el documento).

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

El modo es similar al normal, pero intenta tener en cuenta el espaciado visual entre fragmentos de texto basado en la distancia. Reconocer la cantidad de espacios entre fragmentos puede no ser preciso porque depende en gran medida de cómo se generan los documentos. Si los documentos se crean con diferentes generadores, pueden existir inexactitudes al comparar los espacios entre fragmentos de texto. Esta opción puede producir resultados que, aunque lógicos, difieren de los resultados de comparación esperados cuando se aplica a documentos con una estructura compleja.
