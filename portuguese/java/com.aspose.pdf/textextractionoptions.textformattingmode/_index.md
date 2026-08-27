---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Referência da API Aspose.PDF para Java"
description: "Define diferentes modos que podem ser usados ao converter documento pdf em texto. Veja a classe {@code TextDevice}."
type: docs
weight: 5070
url: /pt/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

Define diferentes modos que podem ser usados ao converter documento pdf em texto. Veja a classe {@code TextDevice}.

## Campos

| Campo | Descrição |
| --- | --- |
| [Flatten](#Flatten) | Representa o conteúdo PDF com fragmentos de texto posicionados por suas coordenadas. É basicamente semelhante ao modo "Raw". Mas enquanto o "Raw" foca em preservar a estrutura dos fragmentos de texto (operadores) em um documento, o "Flatten" foca em manter o texto na ordem em que é lido. |
| [MemorySaving](#MemorySaving) | Extração com economia de memória. É quase o mesmo que o modo 'Raw', mas funciona um pouco mais rápido e usa menos memória. |
| [Pure](#Pure) | Representa o conteúdo PDF com um pouco de rotinas de formatação. |
| [Raw](#Raw) | Representa o conteúdo PDF como está, ou seja, sem formatação. |

### Flatten {#Flatten}
```
public static final int Flatten
```

Representa o conteúdo PDF com fragmentos de texto posicionados por suas coordenadas. É basicamente semelhante ao modo "Raw". Mas enquanto o "Raw" foca em preservar a estrutura dos fragmentos de texto (operadores) em um documento, o "Flatten" foca em manter o texto na ordem em que é lido.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

Extração com economia de memória. É quase o mesmo que o modo 'Raw', mas funciona um pouco mais rápido e usa menos memória.

### Pure {#Pure}
```
public static final int Pure
```

Representa o conteúdo PDF com um pouco de rotinas de formatação.

### Raw {#Raw}
```
public static final int Raw
```

Representa o conteúdo PDF como está, ou seja, sem formatação.
