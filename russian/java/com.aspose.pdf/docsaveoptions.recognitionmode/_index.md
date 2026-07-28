---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Справочник API Aspose.PDF для Java"
description: "Позволяет контролировать, как PDF‑документ преобразуется в документ обработки текста. Используйте режим RecognitionMode.Textbox, когда результирующий документ не будет сильно изменяться."
type: docs
weight: 1050
url: /ru/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Позволяет контролировать, как PDF‑документ преобразуется в документ обработки текста. Используйте режим RecognitionMode.Textbox, когда результирующий документ не будет сильно отредактирован. Текстовые поля легко модифицировать, если требуется небольшое количество правок. Используйте режим RecognitionMode.Flow, когда выходному документу требуется дальнейшее редактирование. Абзацы и строки текста в режиме Flow позволяют легко изменять текст, но неподдерживаемые объекты форматирования будут выглядеть хуже, чем в режиме RecognitionMode.Textbox.

## Поля

| Поле | Описание |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Альтернативный режим Flow, поддерживающий распознавание таблиц. |
| [Flow](#Flow) | Полный режим распознавания: движок выполняет группировку и многоуровневый анализ, чтобы восстановить намерения автора оригинального документа и создать максимально редактируемый документ. |
| [Textbox](#Textbox) | Этот режим быстрый и хорошо сохраняет оригинальный вид PDF‑файла, но редактируемость полученного документа может быть ограничена. |

## Методы

| Метод | Описание |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Возвращает константу перечисления этого типа с указанным именем. |
| [values](#values--) | Возвращает массив, содержащий константы этого типа перечисления в порядке их объявления. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Альтернативный режим Flow, поддерживающий распознавание таблиц.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Полный режим распознавания: движок выполняет группировку и многоуровневый анализ, чтобы восстановить намерения автора оригинального документа и создать максимально редактируемый документ.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Этот режим быстрый и хорошо сохраняет оригинальный вид PDF‑файла, но редактируемость полученного документа может быть ограничена.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Возвращает константу перечисления этого типа с указанным именем.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Возвращает массив, содержащий константы этого типа перечисления в порядке их объявления.

**Returns:**
массив, содержащий константы этого типа перечисления в порядке их объявления
