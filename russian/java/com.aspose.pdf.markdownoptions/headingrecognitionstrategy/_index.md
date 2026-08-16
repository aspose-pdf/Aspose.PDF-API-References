---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет типы стратегий распознавания заголовков."
type: docs
weight: 30
url: /ru/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Представляет типы стратегий распознавания заголовков.

## Поля

| Поле | Описание |
| --- | --- |
| [Auto](#Auto) | Обеспечивает автоматический выбор стратегии распознавания заголовков. Это вариант по умолчанию. Если документ содержит закладки, будет выбрана стратегия {@link HeadingRecognitionStrategy#Outlines}, иначе {@link HeadingRecognitionStrategy#Heuristic}. |
| [Heuristic](#Heuristic) | Представляет стратегию распознавания заголовков с помощью эвристических правил и статистики размеров шрифта. |
| [None](#None) | Не распознавать заголовки. Эта опция может быть полезна в сложных форматированных документах. |
| [Outlines](#Outlines) | Представляет стратегию распознавания заголовков с помощью контуров. |

### Auto {#Auto}
```
public static final int Auto
```

Обеспечивает автоматический выбор стратегии распознавания заголовков. Это вариант по умолчанию. Если документ содержит закладки, будет выбрана стратегия {@link HeadingRecognitionStrategy#Outlines}, иначе {@link HeadingRecognitionStrategy#Heuristic}.

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Представляет стратегию распознавания заголовков с помощью эвристических правил и статистики размеров шрифта.

### None {#None}
```
public static final int None
```

Не распознавать заголовки. Эта опция может быть полезна в сложных форматированных документах.

### Outlines {#Outlines}
```
public static final int Outlines
```

Представляет стратегию распознавания заголовков с помощью контуров.
