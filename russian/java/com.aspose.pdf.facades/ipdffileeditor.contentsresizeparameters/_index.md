---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Справочник API Aspose.PDF для Java"
description: "Класс для указания параметров изменения размера страницы. Позволяет задавать следующие параметры: размер результирующей страницы (ширина, высота) в единицах пространства по умолчанию или в процентах от исходных страниц."
type: docs
weight: 300
url: /ru/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Класс для указания параметров изменения размера страницы. Позволяет задавать следующие параметры: размер результирующей страницы (ширина, высота) в единицах пространства по умолчанию или в процентах от размера исходных страниц; левый, верхний, нижний и правый поля в единицах пространства по умолчанию или в процентах от размера исходной страницы; некоторые значения могут быть оставлены null для автоматического расчёта. Эти значения будут вычислены из оставшегося размера страницы после расчёта явно указанных значений. Например: если ширина страницы = 100, а новая ширина страницы указана как 60 единиц, то левое и правое поля рассчитываются автоматически: (100 - 60) / 2 = 15. Этот класс используется в методе ResizeContents.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Создаёт параметры изменения размера, где все значения установлены в "auto". Позднее при необходимости можно задать поля и размер содержимого. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Создаёт параметры изменения размера, где все значения установлены в "auto". Позднее при необходимости можно задать поля и размер содержимого. |

## Методы

| Метод | Описание |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Создаёт параметры изменения размера с указанным размером содержимого. |
| [contentSizePercent](#contentSizePercent-double-double-) | Создаёт параметры изменения размера с указанным размером содержимого в процентах от размера исходной страницы. Поля рассчитываются автоматически. |
| [getBottomMargin](#getBottomMargin--) | Получает или задаёт нижнее поле результирующей страницы. |
| [getContentsHeight](#getContentsHeight--) | Получает или задаёт высоту содержимого исходной страницы на результирующей странице. |
| [getContentsWidth](#getContentsWidth--) | Получает или задаёт ширину содержимого исходной страницы на результирующей странице. |
| [getLeftMargin](#getLeftMargin--) | Получает или задаёт левое поле результирующей страницы. |
| [getRightMargin](#getRightMargin--) | Получает или задаёт правое поле результирующей страницы. |
| [getTopMargin](#getTopMargin--) | Получает или задаёт верхнее поле результирующей страницы. |
| [isChangeMediaBox](#isChangeMediaBox--) | Получает, следует ли корректировать MediaBox PDF‑страницы во время операции изменения размера. Значение по умолчанию — {@code false}. Установка этого параметра включает подгонку MediaBox к значению CropBox во время изменения размера. |
| [margins](#margins-double-double-double-double-) | Создаёт параметры изменения размера с указанным значением полей. Размер содержимого рассчитывается автоматически. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Создаёт параметры изменения размера. Поля задаются в процентах от размера исходной страницы. |
| [pageResize](#pageResize-double-double-) | Создаёт параметры изменения размера страницы. |
| [pageResizePct](#pageResizePct-double-double-) | Создаёт параметры изменения размера страницы. Новые размеры задаются в процентах. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задаёт нижнее поле результирующей страницы. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Устанавливает, следует ли корректировать MediaBox PDF‑страницы во время операции изменения размера. Значение по умолчанию — {@code false}. Установка этого параметра включает подгонку MediaBox к значению CropBox во время изменения размера. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задаёт высоту содержимого исходной страницы на результирующей странице. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задаёт ширину содержимого исходной страницы на результирующей странице. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задаёт левое поле результирующей страницы. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задаёт правое поле результирующей страницы. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Получает или задаёт верхнее поле результирующей страницы. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Создаёт параметры изменения размера, где все значения установлены в "auto". Позднее при необходимости можно задать поля и размер содержимого.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Создаёт параметры изменения размера, где все значения установлены в "auto". Позднее при необходимости можно задать поля и размер содержимого.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Создаёт параметры изменения размера с указанным размером содержимого.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина |  | Новая ширина содержимого. |
| высота |  | Новая высота содержимого. |

**Returns:**
Возвращает новые параметры изменения размера.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Создаёт параметры изменения размера с указанным размером содержимого в процентах от размера исходной страницы. Поля рассчитываются автоматически.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина |  | Новая ширина содержимого в процентах. |
| высота |  | Новая высота содержимого в процентах. |

**Returns:**
Новые параметры изменения размера.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Получает или задаёт нижнее поле результирующей страницы.

**Returns:**
Объект ContentsResizeValue

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Получает или задаёт высоту содержимого исходной страницы на результирующей странице.

**Returns:**
Объект ContentsResizeValue

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Получает или задаёт ширину содержимого исходной страницы на результирующей странице.

**Returns:**
Объект ContentsResizeValue

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Получает или задаёт левое поле результирующей страницы.

**Returns:**
Объект ContentsResizeValue

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Получает или задаёт правое поле результирующей страницы.

**Returns:**
Объект ContentsResizeValue

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Получает или задаёт верхнее поле результирующей страницы.

**Returns:**
Объект ContentsResizeValue

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Получает, следует ли корректировать MediaBox PDF‑страницы во время операции изменения размера. Значение по умолчанию — {@code false}. Установка этого параметра включает подгонку MediaBox к значению CropBox во время изменения размера.

**Returns:**
нужно ли корректировать MediaBox страницы PDF во время операции изменения размера.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Создаёт параметры изменения размера с указанным значением полей. Размер содержимого рассчитывается автоматически.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| слева |  | Левый отступ. |
| справа |  | Правый отступ. |
| сверху |  | Верхний отступ. |
| снизу |  | Нижний отступ. |

**Returns:**
Созданы параметры изменения размера.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Создаёт параметры изменения размера. Поля задаются в процентах от размера исходной страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| слева |  | Левый отступ (в процентах от ширины страницы). |
| справа |  | Правый отступ (в процентах от высоты страницы). |
| сверху |  | Верхний отступ (в процентах от высоты страницы). |
| снизу |  | Нижний отступ (в процентах от высоты страницы). |

**Returns:**
Возвращает новые параметры изменения размера.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Создаёт параметры изменения размера страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ширина |  | Новая ширина страницы в единицах. |
| высота |  | Новая высота страницы в единицах. |

**Returns:**
Новые параметры изменения размера.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Создаёт параметры изменения размера страницы. Новые размеры задаются в процентах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| widthPct |  | Новая ширина страницы в процентах. |
| heightPct |  | Новая высота страницы в процентах. |

**Returns:**
Новые параметры изменения размера.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Получает или задаёт нижнее поле результирующей страницы.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Устанавливает, следует ли корректировать MediaBox PDF‑страницы во время операции изменения размера. Значение по умолчанию — {@code false}. Установка этого параметра включает подгонку MediaBox к значению CropBox во время изменения размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение |  | нужно ли корректировать MediaBox страницы PDF во время операции изменения размера. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Получает или задаёт высоту содержимого исходной страницы на результирующей странице.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Получает или задаёт ширину содержимого исходной страницы на результирующей странице.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Получает или задаёт левое поле результирующей страницы.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Получает или задаёт правое поле результирующей страницы.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Получает или задаёт верхнее поле результирующей страницы.
