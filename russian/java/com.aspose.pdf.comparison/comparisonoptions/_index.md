---
title: "ComparisonOptions"
linktitle: "ComparisonOptions"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс параметров сравнения PDF‑документов."
type: docs
weight: 10
url: /ru/java/com.aspose.pdf.comparison/comparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.ComparisonOptions

```
public class ComparisonOptions extends Object
```

Представляет класс параметров сравнения PDF‑документов.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ComparisonOptions](#ComparisonOptions--) | Создает экземпляр класса {@link ComparisonOptions}. |

## Методы

| Метод | Описание |
| --- | --- |
| [getEditOperationsOrder](#getEditOperationsOrder--) | Получает и задает порядок операций редактирования. |
| [getExcludeAreas1](#getExcludeAreas1--) | Получает и задает области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно установить вместе с {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя установить вместе с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [getExcludeAreas2](#getExcludeAreas2--) | Получает и задает области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно установить вместе с {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя установить вместе с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [getExtractionArea](#getExtractionArea--) | Получает и задает прямоугольную область, в которой будет сравниваться текст страниц. Этот параметр нельзя установить вместе с {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) и { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) параметрами. |
| [isExcludeTables](#isExcludeTables--) | Получает и задает параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя установить одновременно с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). Значение по умолчанию — {@code false}. |
| [setEditOperationsOrder](#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-) | Получает и задает порядок операций редактирования. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Получает и задает области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно установить вместе с {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя установить вместе с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Получает и задает области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно установить вместе с {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя установить вместе с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). |
| [setExcludeTables](#setExcludeTables-boolean-) | Получает и задает параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя установить одновременно с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). Значение по умолчанию — {@code false}. |
| [setExtractionArea](#setExtractionArea-com.aspose.pdf.Rectangle-) | Получает и задает прямоугольную область, в которой будет сравниваться текст страниц. Этот параметр нельзя установить вместе с {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) и { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) параметрами. |

### ComparisonOptions {#ComparisonOptions--}
```
public ComparisonOptions()
```

Создает экземпляр класса {@link ComparisonOptions}.

### getEditOperationsOrder {#getEditOperationsOrder--}
```
public final EditOperationsOrder getEditOperationsOrder()
```

Получает и задает порядок операций редактирования.

**Returns:**
Элемент EditOperationsOrder

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Получает и задает области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно установить вместе с {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя установить вместе с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

**Returns:**
массив экземпляров Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Получает и задает области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно установить вместе с {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя установить вместе с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

**Returns:**
массив экземпляров Rectangle

### getExtractionArea {#getExtractionArea--}
```
public final Rectangle getExtractionArea()
```

Получает и задает прямоугольную область, в которой будет сравниваться текст страниц. Этот параметр нельзя установить вместе с {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) и { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) параметрами.

**Returns:**
Экземпляр Rectangle

### isExcludeTables {#isExcludeTables--}
```
public final boolean isExcludeTables()
```

Получает и задает параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя установить одновременно с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). Значение по умолчанию — {@code false}.

**Returns:**
логическое значение

### setEditOperationsOrder {#setEditOperationsOrder-com.aspose.pdf.comparison.EditOperationsOrder-}
Получает и задает порядок операций редактирования.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Получает и задает области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно установить вместе с {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя установить вместе с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Получает и задает области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно установить вместе с {@code ExcludeTables}({@link #isExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя установить вместе с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}).

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Получает и задает параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя установить одновременно с параметром {@code ExtractionArea}({@link #getExtractionArea}/{@link #setExtractionArea(Rectangle)}). Значение по умолчанию — {@code false}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setExtractionArea {#setExtractionArea-com.aspose.pdf.Rectangle-}
Получает и задает прямоугольную область, в которой будет сравниваться текст страниц. Этот параметр нельзя установить вместе с {@code ExcludeTables}({ #getExcludeTables}/{ #setExcludeTables(boolean)}), {@code ExcludeAreas1}({ #getExcludeAreas1}/{ #setExcludeAreas1(Rectangle[])}) и { ExcludeAreas2}({ #getExcludeAreas2}/{ #setExcludeAreas2(Rectangle[])}) параметрами.
