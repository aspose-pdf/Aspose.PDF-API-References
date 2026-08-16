---
title: "SideBySideComparisonOptions"
linktitle: "SideBySideComparisonOptions"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс параметров для сравнения документов с выводом бок о бок."
type: docs
weight: 60
url: /ru/java/com.aspose.pdf.comparison.sidebysidecomparison/sidebysidecomparisonoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions, com.aspose.pdf.comparison.outputgenerator.IVentureLicenseTarget, com.aspose.pdf.comparison.sidebysidecomparison.SideBySideComparisonOptions

```
public class SideBySideComparisonOptions extends IVentureLicenseTarget
```

Представляет класс параметров для сравнения документов с выводом бок о бок.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SideBySideComparisonOptions](#SideBySideComparisonOptions--) | Создает экземпляр класса {@link SideBySideComparisonOptions}. |

## Методы

| Метод | Описание |
| --- | --- |
| [getAdditionalChangeMarks](#getAdditionalChangeMarks--) | Получает и задает свойство, определяющее, отображаются ли дополнительные маркеры изменений. Если установлено, отображаются метки изменений, которые отсутствуют на текущей странице, но присутствуют на другой странице. Если изменение находится между словами, метка может быть расположена не точно относительно пробельного символа. Значение по умолчанию — {@code false}. |
| [getComparisonArea1](#getComparisonArea1--) | Получает и задает область сравнения. Используется для первой страницы или документа в методе сравнения. Этот параметр нельзя задавать одновременно с параметрами {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) и {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonArea2](#getComparisonArea2--) | Получает и задает область сравнения. Используется для второй страницы или документа в методе сравнения. Этот параметр нельзя задавать одновременно с параметрами {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) и {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [getComparisonMode](#getComparisonMode--) | Получает и задает режим сравнения. Значение по умолчанию — {@link ComparisonMode#IgnoreSpaces}. |
| [getDeleteColor](#getDeleteColor--) | Получает цвет, используемый для пометки удаленного содержимого при боковом сравнении. Это свойство определяет визуальное представление удалений в результате сравнения. |
| [getExcludeAreas1](#getExcludeAreas1--) | Получает и задает области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно задавать вместе с {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя задавать вместе с параметром {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) . |
| [getExcludeAreas2](#getExcludeAreas2--) | Получает и задает области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно задавать вместе с {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя задавать вместе с параметром {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) . |
| [getExcludeTables](#getExcludeTables--) | Получает и задает параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя задавать одновременно с {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) и {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Значение по умолчанию — {@code false}. |
| [getInsertColor](#getInsertColor--) | Получает цвет, используемый для пометки вставленного содержимого при боковом сравнении. Это свойство определяет визуальное представление вставок в результате сравнения. |
| [setAdditionalChangeMarks](#setAdditionalChangeMarks-boolean-) | Получает и задает свойство, определяющее, отображаются ли дополнительные маркеры изменений. Если установлено, отображаются метки изменений, которые отсутствуют на текущей странице, но присутствуют на другой странице. Если изменение находится между словами, метка может быть расположена не точно относительно пробельного символа. Значение по умолчанию — {@code false}. |
| [setComparisonArea1](#setComparisonArea1-com.aspose.pdf.Rectangle-) | Получает и задает область сравнения. Используется для первой страницы или документа в методе сравнения. Этот параметр нельзя задавать одновременно с параметрами {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) и {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonArea2](#setComparisonArea2-com.aspose.pdf.Rectangle-) | Получает и задает область сравнения. Используется для второй страницы или документа в методе сравнения. Этот параметр нельзя задавать одновременно с параметрами {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) и {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) . |
| [setComparisonMode](#setComparisonMode-int-) | Получает и задает режим сравнения. Значение по умолчанию — {@link ComparisonMode#IgnoreSpaces}. |
| [setDeleteColor](#setDeleteColor-com.aspose.pdf.Color-) | Устанавливает цвет, используемый для пометки удаленного содержимого при боковом сравнении. Это свойство определяет визуальное представление удалений в результате сравнения. |
| [setExcludeAreas1](#setExcludeAreas1-com.aspose.pdf.Rectangle:A-) | Получает и задает области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно задавать вместе с {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя задавать вместе с параметром {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) . |
| [setExcludeAreas2](#setExcludeAreas2-com.aspose.pdf.Rectangle:A-) | Получает и задает области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно задавать вместе с {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя задавать вместе с параметром {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) . |
| [setExcludeTables](#setExcludeTables-boolean-) | Получает и задает параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя задавать одновременно с {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) и {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Значение по умолчанию — {@code false}. |
| [setInsertColor](#setInsertColor-com.aspose.pdf.Color-) | Устанавливает цвет, используемый для пометки вставленного содержимого при боковом сравнении. Это свойство определяет визуальное представление вставок в результате сравнения. |
| [setVentureLicense](#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-) |  |

### SideBySideComparisonOptions {#SideBySideComparisonOptions--}
```
public SideBySideComparisonOptions()
```

Создает экземпляр класса {@link SideBySideComparisonOptions}.

### getAdditionalChangeMarks {#getAdditionalChangeMarks--}
```
public final boolean getAdditionalChangeMarks()
```

Получает и задает свойство, определяющее, отображаются ли дополнительные маркеры изменений. Если установлено, отображаются метки изменений, которые отсутствуют на текущей странице, но присутствуют на другой странице. Если изменение находится между словами, метка может быть расположена не точно относительно пробельного символа. Значение по умолчанию — {@code false}.

**Returns:**
логическое значение

### getComparisonArea1 {#getComparisonArea1--}
```
public final Rectangle getComparisonArea1()
```

Получает и задает область сравнения. Используется для первой страницы или документа в методе сравнения. Этот параметр нельзя задавать одновременно с параметрами {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) и {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Экземпляр Rectangle

### getComparisonArea2 {#getComparisonArea2--}
```
public final Rectangle getComparisonArea2()
```

Получает и задает область сравнения. Используется для второй страницы или документа в методе сравнения. Этот параметр нельзя задавать одновременно с параметрами {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) и {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

**Returns:**
Экземпляр Rectangle

### getComparisonMode {#getComparisonMode--}
```
public final int getComparisonMode()
```

Получает и задает режим сравнения. Значение по умолчанию — {@link ComparisonMode#IgnoreSpaces}.

**Returns:**
Элемент ComparisonMode

### getDeleteColor {#getDeleteColor--}
```
public final Color getDeleteColor()
```

Получает цвет, используемый для пометки удаленного содержимого при боковом сравнении. Это свойство определяет визуальное представление удалений в результате сравнения.

**Returns:**
цвет, используемый для пометки удаленного содержимого при боковом сравнении.

### getExcludeAreas1 {#getExcludeAreas1--}
```
public final Rectangle [] getExcludeAreas1()
```

Получает и задает области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно задавать вместе с {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя задавать вместе с параметром {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) .

**Returns:**
массив экземпляров Rectangle

### getExcludeAreas2 {#getExcludeAreas2--}
```
public final Rectangle [] getExcludeAreas2()
```

Получает и задает области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно задавать вместе с {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя задавать вместе с параметром {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) .

**Returns:**
массив экземпляров Rectangle

### getExcludeTables {#getExcludeTables--}
```
public final boolean getExcludeTables()
```

Получает и задает параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя задавать одновременно с {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) и {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Значение по умолчанию — {@code false}.

**Returns:**
логическое значение

### getInsertColor {#getInsertColor--}
```
public final Color getInsertColor()
```

Получает цвет, используемый для пометки вставленного содержимого при боковом сравнении. Это свойство определяет визуальное представление вставок в результате сравнения.

**Returns:**
цвет, используемый для пометки вставленного содержимого при боковом сравнении.

### setAdditionalChangeMarks {#setAdditionalChangeMarks-boolean-}
```
public final void setAdditionalChangeMarks(boolean value)
```

Получает и задает свойство, определяющее, отображаются ли дополнительные маркеры изменений. Если установлено, отображаются метки изменений, которые отсутствуют на текущей странице, но присутствуют на другой странице. Если изменение находится между словами, метка может быть расположена не точно относительно пробельного символа. Значение по умолчанию — {@code false}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setComparisonArea1 {#setComparisonArea1-com.aspose.pdf.Rectangle-}
Получает и задает область сравнения. Используется для первой страницы или документа в методе сравнения. Этот параметр нельзя задавать одновременно с параметрами {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) и {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonArea2 {#setComparisonArea2-com.aspose.pdf.Rectangle-}
Получает и задает область сравнения. Используется для второй страницы или документа в методе сравнения. Этот параметр нельзя задавать одновременно с параметрами {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}), {@code ExcludeAreas1}({@link #getExcludeAreas1}/{@link #setExcludeAreas1(Rectangle[])}) и {@code ExcludeAreas2}({@link #getExcludeAreas2}/{@link #setExcludeAreas2(Rectangle[])}) .

### setComparisonMode {#setComparisonMode-int-}
```
public final void setComparisonMode(int value)
```

Получает и задает режим сравнения. Значение по умолчанию — {@link ComparisonMode#IgnoreSpaces}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | Элемент ComparisonMode |

### setDeleteColor {#setDeleteColor-com.aspose.pdf.Color-}
Устанавливает цвет, используемый для пометки удаленного содержимого при боковом сравнении. Это свойство определяет визуальное представление удалений в результате сравнения.

### setExcludeAreas1 {#setExcludeAreas1-com.aspose.pdf.Rectangle:A-}
Получает и задает области исключения. Используется для первой страницы или документа в методе сравнения. Этот параметр можно задавать вместе с {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя задавать вместе с параметром {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) .

### setExcludeAreas2 {#setExcludeAreas2-com.aspose.pdf.Rectangle:A-}
Получает и задает области исключения. Используется для второй страницы или документа в методе сравнения. Этот параметр можно задавать вместе с {@code ExcludeTables}({@link #getExcludeTables}/{@link #setExcludeTables(boolean)}). Этот параметр нельзя задавать вместе с параметром {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}) .

### setExcludeTables {#setExcludeTables-boolean-}
```
public final void setExcludeTables(boolean value)
```

Получает и задает параметр, определяющий, исключаются ли таблицы из сравнения. Этот параметр нельзя задавать одновременно с {@code ComparisonArea1}({@link #getComparisonArea1}/{@link #setComparisonArea1(Rectangle)}) и {@code ComparisonArea2}({@link #getComparisonArea2}/{@link #setComparisonArea2(Rectangle)}). Значение по умолчанию — {@code false}.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | логическое значение |

### setInsertColor {#setInsertColor-com.aspose.pdf.Color-}
Устанавливает цвет, используемый для пометки вставленного содержимого при боковом сравнении. Это свойство определяет визуальное представление вставок в результате сравнения.

### setVentureLicense {#setVentureLicense-com.aspose.pdf.engine.licensemanagement.VentureLicense-}
