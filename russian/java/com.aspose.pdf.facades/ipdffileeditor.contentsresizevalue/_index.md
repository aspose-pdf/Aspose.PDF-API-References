---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Справочник API Aspose.PDF для Java"
description: "Значение отступа или размера содержимого, указанное в процентах от единиц пространства по умолчанию. Этот класс используется в ContentsResizeParameters."
type: docs
weight: 310
url: /ru/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Значение отступа или размера содержимого, указанное в процентах от единиц пространства по умолчанию. Этот класс используется в ContentsResizeParameters.

## Методы

| Метод | Описание |
| --- | --- |
| [auto](#auto--) | Инициализирует автоматически вычисленное значение. |
| [getValue](#getValue--) | Получает указанное значение. Используйте свойство Unit, чтобы получить единицы измерения значения. |
| [isPercent](#isPercent--) | Возвращает true, если значение выражено в процентах; False, если значение выражено в единицах по умолчанию. |
| [percents](#percents-double-) | Инициализирует значение в процентах. |
| [setPercentValue](#setPercentValue-double-) | Устанавливает значение в процентах от размера страницы. |
| [setUnitValue](#setUnitValue-double-) | Устанавливает значение в единицах пространства по умолчанию. |
| [units](#units-double-) | Инициализирует значение в единицах пространства по умолчанию. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Инициализирует автоматически вычисленное значение.

**Returns:**
Новый экземпляр значения.

### getValue {#getValue--}
```
public final double getValue()
```

Получает указанное значение. Используйте свойство Unit, чтобы получить единицы измерения значения.

**Returns:**
double значение

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Возвращает true, если значение выражено в процентах; False, если значение выражено в единицах по умолчанию.

**Returns:**
логическое значение

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Инициализирует значение в процентах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | Значение в процентах. |

**Returns:**
Новый экземпляр значения.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Устанавливает значение в процентах от размера страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | double значение |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Устанавливает значение в единицах пространства по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | double значение |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Инициализирует значение в единицах пространства по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | Значение в единицах. |

**Returns:**
Новый экземпляр значения.
