---
title: "HeadingLevels"
linktitle: "HeadingLevels"
second_title: "Справочник API Aspose.PDF для Java"
description: "Представляет класс для работы с уровнями заголовков на основе размера шрифта."
type: docs
weight: 20
url: /ru/java/com.aspose.pdf.markdownoptions/headinglevels/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.markdownoptions.HeadingLevels

```
public class HeadingLevels extends Object
```

Представляет класс для работы с уровнями заголовков на основе размера шрифта.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HeadingLevels](#HeadingLevels--) | Создаёт новый экземпляр класса HeadingLevels. |
| [HeadingLevels](#HeadingLevels-double-) | Создаёт новый экземпляр класса HeadingLevels. |

## Методы

| Метод | Описание |
| --- | --- |
| [addLevels](#addLevels-java.lang.Iterable-) | Добавляет уровни заголовков. |
| [estimateLevel](#estimateLevel-double-) | Оценивает возможный уровень заголовка. Если fontSize не найден в списке уровней, будет возвращён уровень, ближайший к этому значению размера шрифта. Если fontSize находится за пределами минимального и максимального уровней заголовков, указанных в параметрах, метод вернёт false. |
| [findLevel](#findLevel-double-int:A-) | Находит уровень для соответствующего размера шрифта. Ищет точное совпадение. |
| [getAllLevels](#getAllLevels--) | Получает все уровни заголовков. |

### HeadingLevels {#HeadingLevels--}
```
public HeadingLevels()
```

Создаёт новый экземпляр класса HeadingLevels.

### HeadingLevels {#HeadingLevels-double-}
```
public HeadingLevels(double threshold)
```

Создаёт новый экземпляр класса HeadingLevels.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| порог |  | Значение порога для сравнения размеров шрифтов. В пределах порога уровни заголовков считаются одинаковыми. Значение порога по умолчанию равно 0.01. |

### addLevels {#addLevels-java.lang.Iterable-}
Добавляет уровни заголовков.

### estimateLevel {#estimateLevel-double-}
```
public final int estimateLevel(double fontSize)
```

Оценивает возможный уровень заголовка. Если fontSize не найден в списке уровней, будет возвращён уровень, ближайший к этому значению размера шрифта. Если fontSize находится за пределами минимального и максимального уровней заголовков, указанных в параметрах, метод вернёт false.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSize |  | Размер шрифта. |

**Returns:**
Уровень заголовка.

### findLevel {#findLevel-double-int:A-}
```
public final boolean findLevel(double fontSize, int[] level)
```

Находит уровень для соответствующего размера шрифта. Ищет точное совпадение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSize |  | Размер шрифта. |
| уровень |  | Соответствующий уровень заголовка для заданного размера шрифта. |

**Returns:**
False, если fontSize не находится в указанном диапазоне.

### getAllLevels {#getAllLevels--}
```
public final com.aspose.ms.System.Collections.IEnumerable< Double > getAllLevels()
```

Получает все уровни заголовков.

**Returns:**
IEnumerable of Double
