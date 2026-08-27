---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa tipos de estratégias de reconhecimento de cabeçalho."
type: docs
weight: 30
url: /pt/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Representa tipos de estratégias de reconhecimento de cabeçalho.

## Campos

| Campo | Descrição |
| --- | --- |
| [Auto](#Auto) | Fornece uma seleção automática da estratégia de reconhecimento de cabeçalho. Esta é a opção padrão. Se o documento contiver marcadores, a estratégia {@link HeadingRecognitionStrategy#Outlines} será selecionada, caso contrário {@link HeadingRecognitionStrategy#Heuristic}. |
| [Heuristic](#Heuristic) | Representa a estratégia de reconhecimento de cabeçalho por meio de regras heurísticas e estatísticas de tamanho de fonte. |
| [None](#None) | Não reconheça cabeçalhos. Esta opção pode ser útil em documentos com formatação complexa. |
| [Outlines](#Outlines) | Representa a estratégia de reconhecimento de cabeçalho por meio de contornos. |

### Auto {#Auto}
```
public static final int Auto
```

Fornece uma seleção automática da estratégia de reconhecimento de cabeçalho. Esta é a opção padrão. Se o documento contiver marcadores, a estratégia {@link HeadingRecognitionStrategy#Outlines} será selecionada, caso contrário {@link HeadingRecognitionStrategy#Heuristic}.

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Representa a estratégia de reconhecimento de cabeçalho por meio de regras heurísticas e estatísticas de tamanho de fonte.

### None {#None}
```
public static final int None
```

Não reconheça cabeçalhos. Esta opção pode ser útil em documentos com formatação complexa.

### Outlines {#Outlines}
```
public static final int Outlines
```

Representa a estratégia de reconhecimento de cabeçalho por meio de contornos.
