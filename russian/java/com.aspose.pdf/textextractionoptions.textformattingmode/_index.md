---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Справочник API Aspose.PDF для Java"
description: "Определяет различные режимы, которые могут использоваться при преобразовании PDF‑документа в текст. См. класс {@code TextDevice}."
type: docs
weight: 5070
url: /ru/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

Определяет различные режимы, которые могут использоваться при преобразовании PDF‑документа в текст. См. класс {@code TextDevice}.

## Поля

| Поле | Описание |
| --- | --- |
| [Flatten](#Flatten) | Представляет содержимое PDF с позиционированием текстовых фрагментов по их координатам. По сути это аналог режима \"Raw\". Однако в то время как \"Raw\" ориентирован на сохранение структуры текстовых фрагментов (операторов) в документе, \"Flatten\" ориентирован на сохранение текста в порядке его чтения. |
| [MemorySaving](#MemorySaving) | Извлечение с экономией памяти. Практически аналогично режиму 'Raw', но работает немного быстрее и использует меньше памяти. |
| [Pure](#Pure) | Представляет содержимое PDF с небольшим набором процедур форматирования. |
| [Raw](#Raw) | Отображать содержимое PDF как есть, т. е. без форматирования. |

### Flatten {#Flatten}
```
public static final int Flatten
```

Представляет содержимое PDF с позиционированием текстовых фрагментов по их координатам. По сути это аналог режима \"Raw\". Однако в то время как \"Raw\" ориентирован на сохранение структуры текстовых фрагментов (операторов) в документе, \"Flatten\" ориентирован на сохранение текста в порядке его чтения.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

Извлечение с экономией памяти. Практически аналогично режиму 'Raw', но работает немного быстрее и использует меньше памяти.

### Pure {#Pure}
```
public static final int Pure
```

Представляет содержимое PDF с небольшим набором процедур форматирования.

### Raw {#Raw}
```
public static final int Raw
```

Отображать содержимое PDF как есть, т. е. без форматирования.
