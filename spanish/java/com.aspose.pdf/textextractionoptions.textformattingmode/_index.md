---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Define diferentes modos que pueden usarse al convertir un documento pdf a texto. Vea la clase {@code TextDevice}."
type: docs
weight: 5070
url: /es/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

Define diferentes modos que pueden usarse al convertir un documento pdf a texto. Vea la clase {@code TextDevice}.

## Campos

| Campo | Descripción |
| --- | --- |
| [Flatten](#Flatten) | Representa el contenido PDF con fragmentos de texto posicionados por sus coordenadas. Es básicamente similar al modo "Raw". Pero mientras "Raw" se centra en preservar la estructura de los fragmentos de texto (operadores) en un documento, "Flatten" se centra en mantener el texto en el orden en que se lee. |
| [MemorySaving](#MemorySaving) | Extracción con ahorro de memoria. Es casi igual al modo 'Raw' pero funciona ligeramente más rápido y usa menos memoria. |
| [Pure](#Pure) | Representa el contenido PDF con un poco de rutinas de formato. |
| [Raw](#Raw) | Representa el contenido PDF tal cual, es decir, sin formato. |

### Flatten {#Flatten}
```
public static final int Flatten
```

Representa el contenido PDF con fragmentos de texto posicionados por sus coordenadas. Es básicamente similar al modo "Raw". Pero mientras "Raw" se centra en preservar la estructura de los fragmentos de texto (operadores) en un documento, "Flatten" se centra en mantener el texto en el orden en que se lee.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

Extracción con ahorro de memoria. Es casi igual al modo 'Raw' pero funciona ligeramente más rápido y usa menos memoria.

### Pure {#Pure}
```
public static final int Pure
```

Representa el contenido PDF con un poco de rutinas de formato.

### Raw {#Raw}
```
public static final int Raw
```

Representa el contenido PDF tal cual, es decir, sin formato.
