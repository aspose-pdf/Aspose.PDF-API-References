---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Справочник API Aspose.PDF для Java"
description: "Когда PDF‑файл (обычно имеющий фиксированную разметку) конвертируется, движок конвертации пытается выполнить группировку и многоуровневый анализ для восстановления оригинального документа."
type: docs
weight: 1250
url: /ru/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

Когда PDF‑файл (обычно имеющий фиксированную разметку) конвертируется, движок конвертации пытается выполнить группировку и многоуровневый анализ, чтобы восстановить намерения автора оригинального документа и получить результат в потоковом макете. Это свойство настраивает эту конвертацию для того или иного желаемого метода распознавания содержимого.

## Поля

| Поле | Описание |
| --- | --- |
| [Fixed](#Fixed) | Этот режим быстрый и хорошо сохраняет оригинальный внешний вид страниц, но, к сожалению, многие читалки EPUB не поддерживают XHTML с фиксированной разметкой. |
| [Flow](#Flow) | Полный режим распознавания: движок пытается выполнить группировку и многоуровневый анализ, чтобы восстановить намерения автора оригинального документа и создать XHTML в потоковом макете. |
| [PdfFlow](#PdfFlow) | Основная идея этой конвертации основана на сохранении "естественного" порядка отображения контента, формируемого при обработке PDF‑документов. |

## Методы

| Метод | Описание |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Возвращает константу перечисления этого типа с указанным именем. |
| [values](#values--) | Возвращает массив, содержащий константы этого типа перечисления в порядке их объявления. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Этот режим быстрый и хорошо сохраняет оригинальный внешний вид страниц, но, к сожалению, многие читалки EPUB не поддерживают XHTML с фиксированной разметкой.

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Полный режим распознавания: движок пытается выполнить группировку и многоуровневый анализ, чтобы восстановить намерения автора оригинального документа и создать XHTML в потоковом макете.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

Основная идея этой конвертации основана на сохранении "естественного" порядка отображения контента, формируемого при обработке PDF‑документов.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Возвращает константу перечисления этого типа с указанным именем.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Возвращает массив, содержащий константы этого типа перечисления в порядке их объявления.

**Returns:**
массив, содержащий константы этого типа перечисления в порядке их объявления
