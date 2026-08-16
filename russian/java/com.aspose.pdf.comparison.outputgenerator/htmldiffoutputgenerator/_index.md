---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс для генерации HTML‑представления различий текстов. Удалённые разрывы строк обозначаются знаком - абзаца."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Представляет класс для генерации HTML‑представления различий текстов. Удалённые разрывы строк обозначаются знаком - абзаца.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Создает экземпляр класса {@link HtmlDiffOutputGenerator}. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Создает экземпляр класса {@link HtmlDiffOutputGenerator}. |

## Методы

| Метод | Описание |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [generateOutput1](#generateOutput1-java.util.List-) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Генерирует вывод на основе различий между текстами и сохраняет его в файл. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Получает массив с именами кодировок. |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Получает и задаёт строку в стиле CSS для операции Delete. Пример: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Получает и задаёт строку в стиле CSS для операции Equal. Пример: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Получает и задаёт строку в стиле CSS для операции Insert. Пример: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Получает или задаёт стиль text-decoration: line-through для операции delete. Значение по умолчанию — {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Получает и задаёт строку в стиле CSS для операции Delete. Пример: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Получает и задаёт строку в стиле CSS для операции Equal. Пример: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Получает и задаёт строку в стиле CSS для операции Insert. Пример: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Получает или задаёт стиль text-decoration: line-through для операции delete. Значение по умолчанию — {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Создает экземпляр класса {@link HtmlDiffOutputGenerator}.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Создает экземпляр класса {@link HtmlDiffOutputGenerator}.

### generateOutput {#generateOutput-java.util.List-}
Генерирует вывод на основе различий между текстами и сохраняет его в файл.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Генерирует вывод на основе различий между текстами и сохраняет его в файл.

### generateOutput1 {#generateOutput1-java.util.List-}
Генерирует вывод на основе различий между текстами и сохраняет его в файл.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Генерирует вывод на основе различий между текстами и сохраняет его в файл.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Получает массив с именами кодировок.

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Получает и задаёт строку в стиле CSS для операции Delete. Пример: color: #003300; background-color: #ccff66;

**Returns:**
строковое значение

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Получает и задаёт строку в стиле CSS для операции Equal. Пример: color: #003300; background-color: #ccff66;

**Returns:**
строковое значение

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Получает и задаёт строку в стиле CSS для операции Insert. Пример: color: #003300; background-color: #ccff66;

**Returns:**
строковое значение

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Получает или задаёт стиль text-decoration: line-through для операции delete. Значение по умолчанию — {@code False}.

**Returns:**
логическое значение

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Получает и задаёт строку в стиле CSS для операции Delete. Пример: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Получает и задаёт строку в стиле CSS для операции Equal. Пример: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Получает и задаёт строку в стиле CSS для операции Insert. Пример: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Получает или задаёт стиль text-decoration: line-through для операции delete. Значение по умолчанию — {@code False}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |
